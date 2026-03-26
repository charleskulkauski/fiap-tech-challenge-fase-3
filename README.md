# 🏥 Medical Virtual Assistant - Tech Challenge Fase 3

Este repositório contém o desenvolvimento de um Assistente Médico Inteligente que utiliza **Fine-Tuning de LLMs**, **RAG (Retrieval-Augmented Generation)** e **LangGraph** para auxiliar profissionais de saúde na tomada de decisão.

## 🚀 Tecnologias Utilizadas
- **Model:** Phi-3.5-mini-instruct (via Unsloth)
- **Orquestração:** LangGraph & LangChain
- **Vector DB:** ChromaDB
- **Embeddings:** HuggingFace (all-MiniLM-L6-v2)
- **Técnicas:** LoRA, 4-bit Quantization, Prompt Engineering

## 🛠️ Funcionalidades
1. **Anonimização de Dados:** Processamento de dados sensíveis seguindo a LGPD.
2. **Base de Conhecimento:** Recuperação de protocolos hospitalares via RAG.
3. **Fluxo de Decisão:** Grafo de estados que coordena a pesquisa e a geração da resposta.
4. **Logs de Auditoria:** Rastreabilidade completa das ações do assistente.

## 📁 Estrutura do Projeto
- `notebook.ipynb`: Implementação completa do pipeline.
- `fictitious_data/`: Base de dados utilizada para o treinamento e RAG.
- `assistente_medico_audit.log`: Logs gerados durante a execução.

## ⚙️ Como Executar
1. Instale as dependências: `pip install -r requirements.txt`
2. Configure o ambiente (recomenda-se GPU para o Fine-Tuning).
3. Execute as células do notebook para carregar o modelo e iniciar o assistente.

> **Aviso:** Este sistema é uma ferramenta de auxílio. Toda e qualquer sugestão deve ser validada por um médico credenciado.
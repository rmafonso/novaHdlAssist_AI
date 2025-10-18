# novaHdlAssist_AI

Este projeto implementa um sistema de Retrieval Augmented Generation (RAG) projetado para ajudar programadores VHDL. Ele utiliza documentos PDF contendo informações sobre VHDL como base de conhecimento para responder a perguntas através de um modelo de linguagem.

## Funcionalidades

*   Extração de texto de documentos PDF.
*   Divisão do texto em pedaços para processamento.
*   Criação de embeddings para os pedaços de texto.
*   Armazenamento dos embeddings e metadados numa base de dados vetorial (Chroma DB).
*   Recuperação de pedaços relevantes com base numa consulta do utilizador.
*   Geração de respostas informadas pelo contexto recuperado usando um modelo de linguagem (GROQ).

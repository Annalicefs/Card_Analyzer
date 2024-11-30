# Analisador de Imagens de Cartão de Crédito

Este projeto é uma aplicação web desenvolvida com **Streamlit** que permite aos usuários enviar imagens de cartões de crédito e extrair informações relevantes usando o **Azure Cognitive Services for Document Intelligence**.

## Funcionalidades

- **Envio de imagens de cartão de crédito** (formatos PNG, JPG, JPEG).
- **Armazenamento seguro de imagens** no **Azure Blob Storage**.
- **Análise de imagens** utilizando o **Azure Cognitive Services for Document Intelligence** para extrair:
  - Nome do Titular do Cartão
  - Número do Cartão
  - Data de Vencimento
  - Banco Emissor
- Exibição das informações extraídas para o usuário.
- **Tratamento de erros** para uploads de arquivos e chamadas de API.

## Tecnologias Utilizadas

- **Streamlit**: Para a interface da aplicação web.
- **Azure Blob Storage**: Para armazenamento seguro das imagens.
- **Azure Cognitive Services for Document Intelligence**: Para extração de informações do cartão de crédito.
- **Python**: Para desenvolvimento do back-end e integração com APIs do Azure.

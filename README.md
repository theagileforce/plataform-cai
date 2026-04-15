# 🚀 Datarisk ChurnAI Platform

Bem-vindos ao repositório central da plataforma de Churn Preditivo e Agêntico.

## 📌 Documentação Oficial
* O Documento de Arquitetura Técnica (Clean Architecture, AWS, RLS) encontra-se em: `docs/arquitetura/Documento_Arquitetura.md`.
* Os contratos de API do MVP (Swagger/OpenAPI) encontram-se em: `docs/api/openapi.yaml`.

## 💻 Como subir o ambiente de desenvolvimento local (Sprint 0)
Para iniciar os desenvolvimentos sem depender da infraestrutura em nuvem, utilize o Docker. O nosso ambiente local inclui o PostgreSQL (com `pgvector`) populado com as 39 tabelas iniciais e o MinIO (simulando o AWS S3).

1. Abra o terminal na raiz deste projeto.
2. Navegue até a pasta de infraestrutura local:
   ```bash
   cd infra/local

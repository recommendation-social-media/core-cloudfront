# Recommendation Social Media APP Core CloudFront

**Descrição:**

Contém a infra do CloudFront provisionado para conectar o front-end com o API Gateway.

**Variáveis de ambiente necessárias:**

- **AWS_ACCESS_KEY_ID:** AWS access key ID.
- **AWS_SECRET_ACCESS_KEY:** AWS secret access key.

**Deploy da infraestrutura:**

```bash
 terraform apply -var-file="./variables/dev.tfvars"
```
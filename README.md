# Cadastro API

API REST para gerenciamento de cadastros com notificação por e-mail após 2 minutos.

## Funcionalidades
- Criar, listar, buscar, atualizar e deletar cadastros
- Notificação por email com atraso

## Requisitos
- Docker + Compose
- AWS CLI configurado
- Terraform instalado

## Implantação
```bash
git clone https://github.com/seu-usuario/cadastro-api.git
cd cadastro-api
terraform init && terraform apply
docker-compose up --build
```

## Observabilidade
- Prometheus + Grafana
- Jaeger para tracing
- Logs via CloudWatch (ou ELK)

## TLS
- Certificados gerenciados via ACM no API Gateway

# Projeto OdontoFast

## Instruções para Deploy

### Requisitos
- Docker e Docker Compose instalados
- Acesso à VM provisionada na Azure

### Como executar

1. Clone este repositório na sua máquina virtual:
```bash
git clone https://github.com/sousa-sara/odontofast-devops-backend

cd projeto-odontofast
```

Execute o Docker Compose:

```bash
docker-compose up -d
```

## Testes

Acesse o backend em http://191.232.161.85:8080

### 5. Verificações Finais:
- Verifique se todos os contêineres estão sendo executados com o comando:

```bash
  docker ps
```

# Aula 02 - Workloads Básicos no Kubernetes

🎥 Vídeo da aula:  
https://www.youtube.com/watch?v=xXUhepb5Ccc

## Conteúdo abordado

Nesta aula, aprendemos sobre os principais recursos básicos de workloads no Kubernetes:

- **Pod**: É a menor unidade do Kubernetes. Ele pode conter um ou mais containers e compartilha recursos como rede e armazenamento.
- **ReplicaSet**: Garante que sempre haja um número fixo de réplicas de um Pod rodando.
- **Deployment**: Gerencia réplicas e permite atualizações fáceis dos Pods.
- **Service**: Expõe os Pods para acesso interno ou externo.

## Estrutura

- `pod/` → Exemplo de criação de um Pod simples.
- `replicaset/` → Exemplo de ReplicaSet com múltiplas réplicas.
- `deployment/` → Exemplo de Deployment com atualização controlada.
- `service/` → Exemplo de Service integrando com os Pods.

## Como aplicar os exemplos

### Pod

```bash
kubectl apply -f pod/pod.yaml
```

### Replicaset

```bash
kubectl apply -f replicaset/rs.yaml
```

### Deployment

```bash
kubectl apply -f deployment/deploy.yaml
```

### Service

```bash
kubectl apply -f service/deploy.yaml,service/service.yaml
```
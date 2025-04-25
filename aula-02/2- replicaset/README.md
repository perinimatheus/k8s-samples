## 📌 O que é um ReplicaSet?
O **ReplicaSet** garante que sempre haja um número fixo de réplicas de um Pod rodando.

## 🛠 Características:
- Mantém um número específico de Pods ativos.
- Se um Pod falhar, um novo é criado automaticamente.
- Usa **selectors** para gerenciar os Pods.

## 🚀 Como aplicar?
```sh
kubectl apply -f rs.yaml
```

## 📖 Mais sobre ReplicaSets:
[Documentação Oficial](https://kubernetes.io/pt-br/docs/concepts/workloads/controllers/replicaset/)
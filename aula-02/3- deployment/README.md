## 📌 O que é um Deployment?
O **Deployment** gerencia réplicas e permite atualizações fáceis dos Pods.

## 🛠 Características:
- Usa um **ReplicaSet** internamente.
- Permite **atualizações sem downtime**.
- Garante que sempre haja um número mínimo de réplicas.

## 🚀 Como aplicar?
```sh
kubectl apply -f deploy.yaml
```

## 📖 Mais sobre Deployments:
[Documentação Oficial](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/)

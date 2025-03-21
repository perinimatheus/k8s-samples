# Exemplo: Pod no Kubernetes

## 📌 O que é um Pod?
Um **Pod** é a menor unidade do Kubernetes. Ele pode conter um ou mais containers e compartilha recursos como rede e armazenamento.

## 🛠 Características:
- Criado diretamente sem necessidade de ReplicaSet ou Deployment.
- Não se replica automaticamente (se for deletado, não será recriado).
- IP pode mudar a cada reinicialização.

## 🚀 Como aplicar?
```sh
kubectl apply -f pod.yaml
```

## 📖 Mais sobre Pods:
[Documentação Oficial](https://kubernetes.io/docs/concepts/workloads/pods/)
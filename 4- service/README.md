## 📌 O que é um Service?
O **Service** expõe Pods e permite que eles sejam acessados dentro ou fora do cluster.

## 🛠 Tipos de Service:
- **ClusterIP** (padrão) – Disponível apenas dentro do cluster.
- **NodePort** – Exposto externamente via IP do nó.
- **LoadBalancer** – Usa um balanceador de carga externo.

## 🚀 Como aplicar?
```sh
kubectl apply -f .
```

## 📖 Mais sobre Services:
[Documentação Oficial](https://kubernetes.io/docs/concepts/services-networking/service/)
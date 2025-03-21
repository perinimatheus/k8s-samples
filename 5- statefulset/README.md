## 📌 O que é um StatefulSet?
O **StatefulSet** é um controlador que gerencia pods com **identidade persistente**. Ele é usado para aplicações que precisam de um nome fixo, armazenamento persistente ou ordem de inicialização específica.

## 🛠 Características:
- Cada pod tem um nome único (`pod-0`, `pod-1`, `pod-2`).
- Mantém a ordem de inicialização e desligamento dos pods.
- Usado para bancos de dados e aplicações stateful (MongoDB, PostgreSQL, etc.).
- Normalmente usado com **PersistentVolumeClaims (PVCs)**.

## 🚀 Como aplicar?
```sh
kubectl apply -f sts.yaml
```

## 📖 Mais sobre StatefulSet:
[Documentação Oficial](https://kubernetes.io/docs/concepts/workloads/controllers/statefulset/)
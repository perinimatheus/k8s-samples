## 📌 O que é um DaemonSet?
O **DaemonSet** garante que **um pod seja executado em cada nó do cluster**. Ele é ideal para processos que precisam rodar em todos os nós, como logs, monitoramento e networking.

## 🛠 Características:
- Cada nó do cluster recebe um pod automaticamente.
- Usado para serviços de **monitoramento (Prometheus, Fluentd)** e **rede (Calico, Cilium)**.
- Se um nó novo entrar no cluster, ele recebe um pod automaticamente.

## 🚀 Como aplicar?
```sh
kubectl apply -f ds.yaml
```

## 📖 Mais sobre DaemonSet:
[Documentação Oficial](https://kubernetes.io/docs/concepts/workloads/controllers/daemonset/)
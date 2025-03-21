# Exemplos de Kubernetes

Bem-vindo ao repositório de exemplos práticos de Kubernetes! Aqui você encontrará diferentes recursos do Kubernetes organizados em pastas separadas, cada uma contendo um exemplo funcional e um README explicativo.

## Objetivo  
Este repositório tem como finalidade ajudar no aprendizado e prática do Kubernetes, fornecendo exemplos prontos para serem aplicados em um cluster.

## Estrutura do Repositório  
Cada pasta contém um exemplo específico, com um arquivo YAML e um README explicando o funcionamento.

| Diretório      | Descrição                                          |
|----------------|----------------------------------------------------|
| `pod`           | Exemplo de um Pod simples.                        |
| `replicaset`    | Uso de ReplicaSet para manter múltiplos Pods.      |
| `deployment`    | Gerenciamento de Pods com Deployment.             |
| `service`       | Exemplo de Service para expor aplicações no Kubernetes. |
| `statefulset`   | Exemplo de StatefulSet para aplicações stateful.  |
| `daemonset`     | Execução de Pods em todos os nós do cluster com DaemonSet. |
| `cronjob`       | Agendamento de tarefas recorrentes com CronJob.   |

## Como usar?  
Para aplicar qualquer um dos exemplos, basta usar o comando:

```sh
kubectl apply -f <caminho-do-arquivo>.yaml
```

Exemplo:

```sh
kubectl apply -f pod/pod.yaml
```

Para visualizar os recursos criados:

```sh
kubectl get all
```

## Recursos úteis  
- [Documentação oficial do Kubernetes](https://kubernetes.io/docs/)
- [Instalando o K3s para testes locais](https://docs.k3s.io/quick-start)
- [Comandos básicos do kubectl](https://kubernetes.io/docs/reference/kubectl/)

---

Dica: Se precisar de mais exemplos ou melhorias, fique à vontade para contribuir!

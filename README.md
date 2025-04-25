# Exemplos de Kubernetes - Curso do Básico

Bem-vindo ao repositório de exemplos práticos de Kubernetes! Aqui você encontrará recursos organizados por aula, cada uma contendo exemplos funcionais e um `README.md` explicando o conteúdo.

## 🎯 Objetivo

Este repositório tem como finalidade ajudar no aprendizado e prática de Kubernetes, seguindo a trilha das aulas do curso do básico ao avançado.

## 📁 Estrutura do Repositório

Cada diretório representa uma aula do curso, contendo arquivos YAML dos recursos estudados e explicações sobre seu funcionamento.

| Diretório    | Conteúdo Principal                                                                 |
|--------------|-------------------------------------------------------------------------------------|
| `aula-02`    | Conceitos básicos: Pod, ReplicaSet, Deployment, Service.                           |
| `aula-03`    | Probes (liveness/readiness), recursos (CPU/memória), variáveis de ambiente.        |
| `aula-04`    | Secrets, CronJob, DaemonSet.                                                        |
| `aula-05`    | StatefulSet e estrutura do projeto final.                                           |

## ▶️ Como usar?

Para aplicar os exemplos no seu cluster Kubernetes (recomenda-se o uso de [K3s](https://docs.k3s.io/quick-start)):

```bash
kubectl apply -f <caminho-do-arquivo>.yaml
```

## Exemplo:

```bash
kubectl apply -f aula-02/pod/pod.yaml
```

## Para verificar os recursos aplicados:

```bash
kubectl get all
```

## 🔗 Recursos úteis

- [Documentação oficial do Kubernetes](https://kubernetes.io/docs/)
- [Instalando o K3s para testes locais](https://docs.k3s.io/quick-start)
- [Comandos básicos do kubectl](https://kubernetes.io/docs/reference/kubectl/)
- [Kubernetes Cheat Sheet (kubectl)](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)
# Aula 04 - Recursos Avançados

## Conteúdo abordado

Nesta aula, exploramos recursos mais avançados e específicos no Kubernetes:

- **Secrets**: Armazenam dados sensíveis como senhas e tokens de forma segura.
- **CronJob**: Agendamento de tarefas recorrentes, como scripts e backups.
- **DaemonSet**: Garante que um Pod seja executado em todos (ou alguns) nós do cluster.

## Pastas e exemplos

- `secrets/` → Criação de um Pod que consome variáveis sensíveis via Secret.
- `cronjob/` → Tarefa que imprime a data a cada minuto.
- `daemonset/` → Executa o agente Fluentd em todos os nós.

## Comandos úteis

Criar recursos:

### Secrets:

```bash
kubectl apply -f secrets/secret-pod.yaml
```

### Cronjob:

```bash
kubectl apply -f cronjob/cronjob.yaml
```

### Daemonset:

```bash
kubectl apply -f daemonset/daemonset.yaml
```
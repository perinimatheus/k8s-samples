## 📌 O que é um CronJob?
O **CronJob** agenda e executa tarefas automaticamente em horários definidos, semelhante ao cron do Linux.

## 🛠 Características:
- Executa Jobs em intervalos programados.
- Útil para backups, limpeza de logs e outras tarefas recorrentes.
- Baseado na sintaxe de cron (`* * * * *` para agendamentos).

## 🚀 Como aplicar?
```sh
kubectl apply -f cronjob.yaml
```

## 📖 Mais sobre Cronjob:
[Documentação Oficial](https://kubernetes.io/docs/concepts/workloads/controllers/cron-jobs/)
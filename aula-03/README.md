# Aula 03 - Configurações de Pods

🎥 Vídeos da aula:  
- [Resources no Pod](https://www.youtube.com/watch?v=WzQbGuVNr7c)  
- [Liveness e Readiness](https://www.youtube.com/watch?v=sJgp20_GKIs)  
- [Explicação adicional](https://www.youtube.com/watch?v=IPqb6033sqE)  

## Conteúdo abordado

- **Recursos (requests e limits)**: Define os limites e garantias de CPU/memória para o Pod.
- **Probes (Liveness e Readiness)**: Verificações de saúde do container.
- **Variáveis de Ambiente**: Permite customizar o comportamento do container via env vars.

## Pastas e exemplos

- `resources/` → Pod com requests e limits de CPU/memória.
- `liveness-readiness/` → Pod com probes configuradas.
- `env-variables/` → Pod com variáveis de ambiente definidas.

## Comandos úteis

Aplicar os arquivos:

### Resources:

```bash
kubectl apply -f resources/pod-with-resources.yaml
```

### Liveness and Readiness:

```bash
kubectl apply -f liveness-readiness/pod-with-probes.yaml
```

### Environment Variables:

```bash
kubectl apply -f env-variables/pod-env.yaml
```
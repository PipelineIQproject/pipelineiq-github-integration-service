# PipelineIQ GitHub Integration Service

Independent repository staging folder for the PipelineIQ GitHub integration service.

## Build

```bash
docker build -t nimeshsv814/pipelineiq-github-integration-service:v1.0.0 -f services/github-integration-service/Dockerfile .
```

## Run

This service expects PipelineIQ environment variables from Kubernetes ConfigMap and Key Vault secrets.

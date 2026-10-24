# finance-core-api

Piloto da migração GitOps. O overlay só deve ser referenciado por uma Argo CD Application após a pipeline publicar um `image-patch.yaml` com imagem por digest. Nunca use `latest`.

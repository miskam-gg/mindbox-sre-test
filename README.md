# Тестовое задание Mindbox на позицию SRE

## файлы в этом репозитории

- **deployment.yaml**: определяет Deployment и Horizontal Pod Autoscaler (HPA) для веб-приложения.
- **service.yaml**: определяет Service для предоставления доступа к веб-приложению внутри кластера.
- **ingress.yaml** : настраивает Ingress для доступа к приложению извне через HTTP/HTTPS.
- **configmap.yaml** : содержит конфигурационные данные для приложения.
- **secret.yaml** : содержит конфиденциальные данные, такие как пароли и ключи API.
- **persistent-volume.yaml** : настраивает постоянное хранилище для приложения.
- **persistent-volume-claim.yaml** : запрашивает постоянное хранилище из Persistent Volume (PV).

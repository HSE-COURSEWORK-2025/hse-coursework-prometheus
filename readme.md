# HSE Coursework: Prometheus

Этот репозиторий содержит манифесты и скрипты для деплоя Prometheus в Kubernetes-кластере.

![](https://github.com/HSE-COURSEWORK-2025/hse-coursework-prometheus/blob/master/prometheus_demo.jpg)

## Структура
- `prometheus-k8s.yaml` — манифесты для деплоя Prometheus, PVC и сервиса
- `deploy.sh` — автоматический деплой Prometheus
- `stop.sh` — удаление всех ресурсов Prometheus из кластера

## Быстрый старт
1. Запустите деплой:
   ```bash
   ./deploy.sh
   ```
2. Для удаления:
   ```bash
   ./stop.sh
   ```

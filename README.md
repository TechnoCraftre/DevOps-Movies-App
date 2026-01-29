

/*
┌────────────┐
│ Developer  │
│ (Git Push) │
└─────┬──────┘
      │
      ▼
┌────────────┐
│  GitHub    │
│  Repo      │
└─────┬──────┘
      │ Webhook
      ▼
┌────────────┐
│ Jenkins CI │
│ (on AWS)  │
└─────┬──────┘
      │ Build & Push
      ▼
┌────────────┐
│ Docker Hub │
│ / ECR     │
└─────┬──────┘
      │ Deploy
      ▼
┌────────────┐
│ Kubernetes │
│ Cluster    │
└─────┬──────┘
      │ Metrics
      ▼
┌────────────┐
│ Prometheus │
└─────┬──────┘
      │ Visualize
      ▼
┌────────────┐
│ Grafana    │
└────────────┘

*/

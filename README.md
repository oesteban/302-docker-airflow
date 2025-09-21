# 302-docker-airflow

Project structure:

```Text
├─ afni/
│  └─ Dockerfile                 # Neuroimaging image with AFNI
├─ airflow/
│  └─ Dockerfile                 # Airflow image with docker provider
├─ docker-compose.yaml
├─ .env                          # convenience env (see below)
├─ dags/
│  └─ neuro_pipeline.py          # DAG using ``DockerOperator``
├─ logs/                         # (created by compose)
└─ plugins/                      # (empty unless you need plugins)
```

# Python3-Docker-Template

Created with reference to [this document](https://qiita.com/reflet/items/4b3f91661a54ec70a7dc)

1. Docker-build

```bash
docker-compose up -d --build
```

1. GCF Deploy

```bash
gcloud functions deploy hello_world --trigger-http --runtime=python37
```
# 📊 Traffic Repo

Este repositório centraliza métricas de tráfego dos meus projetos hospedados no GitHub.  
Os dados são coletados automaticamente via **GitHub Actions** e armazenados na branch `traffic-data`.

## 🔎 Projetos monitorados
- [challenge-forum-hub](https://github.com/mpbmarcio/challenge-forum-hub)
- [quarkus-kafka-payments](https://github.com/mpbmarcio/quarkus-kafka-payments)
- [events-api](https://github.com/mpbmarcio/events-api)
- [erp-mpb](https://github.com/mpbmarcio/erp-mpb)

## ⚙️ Como funciona
- Workflow `traffic.yml` roda semanalmente (domingo à meia-noite).
- Coleta dados de **clones** e **views** de cada repositório.
- Salva os resultados em arquivos separados por data dentro da branch `traffic-data`.

## 📂 Estrutura dos logs
```
  logs/
  ├── challenge-forum-hub-2026-05-07.txt
  ├── quarkus-kafka-payments-2026-05-07.txt
  ├── events-api-2026-05-07.txt
  └── erp-mpb-2026-05-07.txt
```
Cada arquivo contém:
- Data da coleta
- Nome do repositório
- Estatísticas de clones e views

---

> ℹ️ Este repositório é usado apenas para fins de monitoramento e organização interna.

# ELK (Elasticsearch + Logstash + Kibana) 7.6.2 + Docker

<img src="https://images.contentstack.io/v3/assets/bltefdd0b53724fa2ce/blt280217a63b82a734/5bbdaacf63ed239936a7dd56/elastic-logo.svg" alt="ELK" width="400" align="right" />

```
docker-compose up -d
```

* User: `elastic` Password: `Kaique@23`
* Elasticsearch: http://localhost:9200
* Kibana: http://localhost:5601
* Para demonstração do logstash, consulte confs em logstash/confdir `logstash/conf` dir
* CSV usado para carregar dados está em `logstash/csv` dir
* Para configuração de elasticsearch, consulte `elasticsearch.yml` em `elasticsearch/config` dir
* Pesquisa de teste `http://localhost:9200/_search`


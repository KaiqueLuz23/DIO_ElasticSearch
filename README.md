# ELK (Elasticsearch + Logstash + Kibana) 7.16.2 + Docker

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

# Download Winlogbeat para Windows 
* Link:
https://www.youtube.com/watch?v=MQ1b5eyQgxE&t=2s
1- https://www.elastic.co/guide/en/beats/winlogbeat/current/winlogbeat-installation-configuration.html
2- https://www.elastic.co/pt/downloads/beats/winlogbeat
* Habilitar a execução de scripts do PowerShell:
1- https://qastack.com.br/superuser/106360/how-to-enable-execution-of-powershell-scripts
```
Start-Service winlogbeat
```
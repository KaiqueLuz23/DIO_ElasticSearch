# ELK (Elasticsearch + Logstash + Kibana) 7.6.2 with Docker

<img src="https://images.contentstack.io/v3/assets/bltefdd0b53724fa2ce/blt280217a63b82a734/5bbdaacf63ed239936a7dd56/elastic-logo.svg" alt="ELK" width="400" align="right" />

```
docker-compose up -d
```

* User `elastic` and password `123change...`
* Elasticsearch: http://localhost:9200
* Kibana: http://localhost:5601
* For logstash demo, see confs in `logstash/conf` dir
* CSV used to load data is in `logstash/csv` dir
* For elasticsearch configuration, see `elasticsearch.yml` in `elasticsearch/config` dir
* Search for test `http://localhost:9200/_search`


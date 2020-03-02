## EFK with docker-compose
# How to run
1. Clone this project
2. Use this command on path that contain efk_cluster/docker-compose.yml
```bash
	docker-compose up -d
```
3. Access Kibana at http://localhost:5601
4. Check Elasticsearch node health at http://localhost:9200/_cat/nodes?v&pretty

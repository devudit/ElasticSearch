# ElasticSearch
Elastic search local setup with docker

1. `git clone git@github.com:devudit/ElasticSearch.git`

2. go to ElasticSearch directory and run `docker compose up --build` . This command will create images and runs two containers for Kibana and elastic search.

3. Open `http://localhost:5701/` in browser. This will open the Kibana frontend. 

4. Elasticsearch is running in `9200`. We can call elastic search APIs to {HTTP METHOD} localhost:9300

Example :- `GET localhost:9300/_search?q=test`
1. Install Docker and Docker Compose
2. wget https://raw.githubusercontent.com/starkandwayne/concourse-tutorial/master/docker-compose.yml
docker-compose up -d
3. Download fly from http://127.0.0.1:8080/
4. `cd ../basic-pipeline`
5. `fly -t tutorial set-pipeline -c pipeline.yml -p hello-world`

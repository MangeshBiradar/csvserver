Commands executed

docker pull infracloudio/csvserver:latest


docker images

docker pull prom/prometheus:v2.22.0

docker images

docker run -it -d -p 9393:9393 infracloudio/csvserver:latest bash

vi Dockerfile

docker build -t csvserver-new .

docker run -dit -p 9393:9300 -e CSVSERVER_BORDER=Orange csvserver-new

curl -o ./part-1-output http://localhost:9393/raw

docker logs b2bbd9ac41cc >& part-1-logs

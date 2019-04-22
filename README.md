# mySQL
mySQL docker image


docker build -t mysql:dev2 -f Dockerfile .
docker run -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD=Pa$$w0rd mysql:dev2

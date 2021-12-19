docker build -t mat121/harpoondemo:1.0 .

docker run -itd --name mycontainer --publish 8080:80 mat121/harpoondemo:1.0

`http://localhost:8080`
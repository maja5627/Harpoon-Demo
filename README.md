docker build -t mat121/harpoondemo:1.0 .

docker run -itd --name mycontainer --publish 8080:80 mat121/harpoondemo:1.0

this will run the index.html locally on port 8080

`http://localhost:8080`

pkg update && pkg install wget curl openjdk-17

cd ../

java -jar v.war --server.port=9090 (9090可以替换成任意端口)

打开浏览器，访问 localhost:8080

# customd_httpd

## イメージの作成
- docker build -t myimage01 .

## イメージを利用する
- docker run -dit --name webcontent_docker -p 8080:80 myimage01
- http://localhost:8080

## 後始末
- docker stop webcontent_docker
- docker rm webcontent_docker
- docker image rm myimage01
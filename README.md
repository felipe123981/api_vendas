# api_vendas
Usage: 
/home/api-vendas$ npm install 
/home/api-vendas$ docker run --name postgres -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
/home/api-vendas$ docker run --name redis -p 6379:6379 -d -t redis:alpine

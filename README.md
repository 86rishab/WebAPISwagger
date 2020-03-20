# Swagger.NetCore
Implemented Swagger documentation in .Net Core web APIs


build command
=============
dotnet publish -c Release 

docker build 
============
docker build -t webapiswagger .

docker run command
==================
docker run -p 9090:9090 --name webapiswagger webapiswagger

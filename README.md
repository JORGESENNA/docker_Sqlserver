# docker_Sqlserver
Usando Docker  SQLServer 

#instagram
https://www.instagram.com/j.h.senna/

#Linkedin
https://www.linkedin.com/in/jorge-henrique-b32a5229/


Creditos(Garagem do Código)
https://www.youtube.com/watch?v=G18LUcEAkIc
Como usar o SQL Server com o Docker?



1- https://hub.docker.com/_/microsoft-mssql-server

👇 Prompt de comando como administrador

docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=#Sa123456" -p 1433:1433 -d mcr.microsoft.com/mssql/server:2022-latest

image.png
2- Verifique se a imagem do MSSQL foi inserido no Docker Desktop
image.png

3- Verifique o containers
image.png

4- entre no containers 
image.png

5- Acesse o Banco de dados  com  Microsoft SQL Server Manament Studio

image.png

image.png
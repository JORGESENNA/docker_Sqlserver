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

👇 Prompt de comando como administrador e troque a senha por uma mais dificil para não dar error
docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=#Sa123456" -p 1433:1433 -d mcr.microsoft.com/mssql/server:2022-latest

![image](https://user-images.githubusercontent.com/39027687/210172755-4cd29a03-d680-49b9-8175-361064c074ed.png)

2- Verifique se a imagem do MSSQL foi inserido no Docker Desktop
![image](https://user-images.githubusercontent.com/39027687/210172643-5f3943eb-e39d-4219-9905-239250bdf03a.png)

3- Verifique o containers
![image](https://user-images.githubusercontent.com/39027687/210172665-b91d9f78-27f3-41f4-bd7e-12a59ec6c2c7.png)

4- entre no containers 
![image](https://user-images.githubusercontent.com/39027687/210172688-6bb35729-dedf-4cff-9c1d-cc77a6a83474.png)

5- Acesse o Banco de dados  com  Microsoft SQL Server Manament Studio

![image](https://user-images.githubusercontent.com/39027687/210172782-1a8234d5-a9c7-40b6-b53c-a265e835c3f1.png)

![image](https://user-images.githubusercontent.com/39027687/210172774-07452134-bbde-4de1-a0e2-937003b6a7a7.png)




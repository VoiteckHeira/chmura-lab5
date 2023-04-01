# chmura-lab5

<h1>Technologie chmurowe </br> lab 5</h1>
Komenda w systemie Ubuntu do zbudowania obrazu przy uzyciu pliku Dockerfilev2 o nazwie app: </br>
<i>docker build --build-arg VERSION=1.0 -f Dockerfilev2 -t app:latest .</i>

Komenda w systemie Ubuntu do zbudowania kontenera dziajcego na porcie 8080 o nazwie app: </br>
<i>docker run -d --name app -p 8080:8080 app</i>

Port w przegladarce: http://localhost:8080

Komenda w systemie Ubuntu do zbudowania obrazu przy uzyciu pliku Dockerfilev3 o nazwie app: </br>
<i>docker build --build-arg VERSION=1.0 -f Dockerfilev3 -t app:latest . </i>

Komenda w systemie Ubuntu do zbudowania kontenera dziajcego na porcie 8080 o nazwie app: </br>
<i>docker run -d --name app -p 8080:8080 app</i>


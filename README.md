# github.com/VoiteckHeira/chmura-lab5

<h1>Technologie chmurowe </br> lab 5</h1>

Nalezy wejsc do folder w zaleznosci od tego ktory etap chcemy sprawdzic poprzez komende</br>
<i>cd etap1</i> lub <i>cd etap2</i>

<h3>ETAP 1</h3>
Etap pierwszy jest zawarty w folderze <b>etap1</b>. Zawiera on 3 pliki:</br>
<ul>
 <li>Dockerfilev2</li>
  <li>package.json</li>
  <li>app.js</li>
 </ul>
</br>
Ponizej podaje komendy do stworzenia obrazu oraz uruchomienia kontenera:</br>
</br>

Komenda w systemie Ubuntu do zbudowania obrazu przy uzyciu pliku Dockerfilev2 o nazwie app: </br>
<i>docker build --build-arg VERSION=1.0 -f Dockerfilev2 -t app:latest .</i>

Komenda w systemie Ubuntu do zbudowania kontenera dziajcego na porcie 8080 o nazwie app: </br>
<i>docker run -d --name app -p 8080:8080 app</i>

Port w przegladarce: http://localhost:8080</br>

Komenda do ewentualnego pozbycia sie obrazu i kontenera: </br>
<i>docker stop app && docker rm app && docker rmi app</i></br>

<h3>ETAP 2</h3>


Komenda w systemie Ubuntu do zbudowania obrazu przy uzyciu pliku Dockerfilev3 o nazwie app: </br>
<i>docker build --build-arg VERSION=1.0 -f Dockerfilev3 -t app:latest . </i>

Komenda w systemie Ubuntu do zbudowania kontenera dziajcego na porcie 8080 o nazwie app: </br>
<i>docker run -d --name app -p 8080:8080 app</i>


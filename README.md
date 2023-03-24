1-http://localhost:8080/info sin comprension
![imagen1](https://raw.githubusercontent.com/belchus/desafio-16/master/docs/respuestas/sincomprension.png)

1-http://localhost:8080/info con comprension
![imagen1](https://raw.githubusercontent.com/belchus/desafio-16/master/docs/respuestas/concomprension.png)

2-Se implementa winston para el sistema de loggeo y devuelve las peticiones en sus respectivos archivos

3-Se trabaja sobre la ruta 8080 con el metodo FORK realizando el test con --prof de node.js,Luego se analizan los resultados de la performance en ambos casos usando Artillery con 50 conexiones concurrentes de 20 request cada una.
Acontinuacion los resultados
![imagen1](https://raw.githubusercontent.com/belchus/desafio-16/master/docs/respuestas/artillery.png)
![imagen1](https://raw.githubusercontent.com/belchus/desafio-16/master/docs/respuestas/art2.png)

4-se utiliza la linea de codigo: autocannon -c 100 -d 20 "http://localhost:8080/info"
![imagen1](https://raw.githubusercontent.com/belchus/desafio-16/master/docs/respuestas/autocannon.png)

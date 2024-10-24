## Tarea 1.3 Instalación de zonas secundarias.


### 1 - Tomaremos a máquina darthsidious, e configuraremola para ser servidor secundario, tanto da zona primaria de resolución directa como de resolución inversa. Captura os ficheiros de configuración en ambalas dúas máquinas. Fai unha captura onde se vexa o reinicio da máquina darthsidious, no que se vexa no log dos dous equipos e que se fixo a transferencia de zona.


Contenido del fichero **de configuración de "tarea_13-darthvader-1"**

![](./images/2024-10-20_22-56-01.png)


Contenido del fichero **de configuración de "tarea_13-darthsidious-1"**

![](./images/2024-10-20_22-56-07.png)


**Fichero db.starwars.lan**

![](./images/2024-10-20_23-32-30.png)


`docker logs -f tarea_13-darthvader-1`

![](./images/2024-10-20_23-02-00.png)



`docker logs -f tarea_13-darthsidious-1`


![](./images/2024-10-20_23-02-06.png)



### 2 - Engade un rexistro tipo A (Chewbacca 192.168.20.28) na zona de resolución directa e tamén na de resolución inversa.  Fai unha captura no momento do reinicio do equipo darthvader, no que se vexa o log dos dous equipos e que se amose que se fixo a transferencia de zona. Adxunta tamén unha captura do ficheiro de zona no servidor secundario.

Contenido del fichero **de zona del servidor secundario**

![](./images/2024-10-20_23-32-19.png)


**captura no momento do reinicio do equipo darthvader**

![](./images/2024-10-20_23-42-16.png)


### 3 - Comproba que o servidor secundario pode resolver ese nome.

![](./images/2024-10-20_23-50-36.png)



### 4 -  Fai os cambios necesarios para que as trasferencias se fagan de forma segura empregando chaves.  Repite as capturas e vídeos do punto 2, engadindo o rexistro r2d2 (192.168.20.29)

**chaves**

![](./images/2024-10-20_23-52-53.png)



![](./images/2024-10-20_23-54-15.png)




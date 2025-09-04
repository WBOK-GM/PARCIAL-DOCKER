# PARCIAL-DOCKER
Parcial Distribuidos Docker

Ejercicio 1 – Imagen personalizada

Crea una imagen custom basada en alpine:3.20 que:
1. Instale curl.
2. Copie un archivo mensaje.txt (creado por usted en el host) al directorio
/app dentro de la imagen.
3. Defina como CMD la instrucción para mostrar el contenido del archivo al
ejecutar un contenedor.

<img width="712" height="365" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2018-53-01.png" />

<img width="712" height="365" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2018-51-52.png" />

Ejercicio 2 – Persistencia con volúmenes

Cree un contenedor de postgres:16-alpine que use un named volume,
este volumen deberá ser llamado con la siguiente nomenclatura:
nombre-apellido-código, para almacenar los datos.

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2018-41-31.png" />

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-02-42.png" />

Cree una tabla llamada parcial con al menos dos registros de prueba,
pueden usar la estructura que quieran.

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-05-57.png" />

Elimine el contenedor y vuelva a levantar uno nuevo que use el mismo
volumen.
4. Verifique que los datos de la tabla siguen disponibles ([pueden usar psql en la
terminal para verificar esto, para ello deben ingresar al contenedor con
(docker exec -it nombre_contenedor sh o bash)

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-06-55.png" />

Ejercicio 3 – Bind mount y edición en vivo

En el host, cree un directorio web con un archivo index.html que contenga
su nombre y código estudiantil.

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-21-43.png" />

Ejecute un contenedor de nginx:alpine que sirva ese archivo mediante un
bind mount de solo lectura.

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-15-26.png" />
Acceda en el navegador a http: /localhost:8080 y capture la
evidencia.

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-18-08.png" />

Modifique el index.html en su host (agregue una línea con su calificación
del curso hasta la fecha, comentarios o feedback).

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-19-11.png" />

Refresque la página y capture la evidencia del cambio.

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-19-21.png" />

Ejercicio 4 – Exploración de contenedores

 Ejecuta un contenedor basado en su imagen personalizada del Ejercicio 1
en modo interactivo con sh.  

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-36-53.png" />

Dentro del contenedor:
○ Cree un archivo nuevo llamado notas.txt en /app.
○ Muestre la ruta de trabajo con pwd.
○ Liste los archivos para demostrar que existen tanto mensaje.txt
como notas.txt.

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-33-22.png" />

El archivo notas.txt se elimina puesto que no tiene persistencia en un volumen.
<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-36-53.png" />

Ejercicio 5 – Redis con Dockerfile

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-46-43.png" />

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-47-03.png" />

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-49-22.png" />

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-55-01.png" />



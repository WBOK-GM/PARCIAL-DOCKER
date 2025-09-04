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

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-21-43.png" />

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-15-26.png" />

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-18-08.png" />

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-19-11.png" />

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-19-21.png" />

Ejercicio 4 – Exploración de contenedores

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-36-53.png" />

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-33-22.png" />

El archivo notas.txt se elimina puesto que no tiene persistencia en un volumen.

Ejercicio 5 – Redis con Dockerfile

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-46-43.png" />

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-47-03.png" />

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-49-22.png" />

<img width="1042" height="163" alt="image" src="https://github.com/WBOK-GM/PARCIAL-DOCKER/blob/main/images/Screenshot%20From%202025-09-03%2019-55-01.png" />



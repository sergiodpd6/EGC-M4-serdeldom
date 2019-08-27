# Enunciado del ejercicio práctico de EGC en Septiembre 2019. 
***
## IMPORTANTE
* El(los) ejercicio(s) se podrá(n) realizar desde los ordenadores de los alumnos y desde los del aula de prácticas y se permite la consulta de contenidos externos. **Realice los cambios en orden secuencial.**

* Se deberá tomar un screenshot después de cada uno de los pasos que estén indicados con el icono :camera:, mostrando la salida de la consola y el comando introducido. En el caso de herramientas gráficas o de herramientas web, se tomarán las capturas de pantallas de las mismas. 

* Una vez terminado el ejercicio
**Cree un .zip de la carpeta local** del repositorio con el nombre UVUS-git.zip Cree otro zip con los contenidos de una carpeta screenshots APELLIDOS-NOMBRE-screnshots.zip donde almacenará las capturas de pantalla que las llamará X.Y siendo X el ejercicio e Y el punto en el que esta, por ejemplo A.03. 

* Posteriormente se subirán a https://hdvirtual.us.es/discovirt/index.php/s/cEesn9HLJ2ssWtL (password: ThisIsThePassword) los archívos comprimidos. Asímismo se completará la entrega en la url https://opina.us.es/opina/c/476046 (password: ThisIsThePassword). **La modificación de cualquier contenido del repositorio (wiki, issues o código) una vez entregado el examen implicará el suspenso del alumno. Antes de dejar la sala de la prueba, avisar al profesor para verificar que todo está correctamente enviado.**


## Ejecicio A
1. Realice un fork de este repositorio con el nombre EGC-M4-"uvus".
2. Clone el repositorio del cual ha hecho el fork. :camera:
3. Cree una nueva rama llamada desarrollo en el repositorio. :camera:
4. "Salte" a la rama recien creada. :camera:
5. En el código de DECIDE del repositio existe un error. Identifique el error ejecutando en su máquina el código.
6. Cree una "issue" en el fork del repositorio para reportar el error según las recomendaciones vistas en clase.  :camera:
7. Realice las modificaciones necesarias para corregir el error.
8. Haga commit de los cambios en la rama de desarrollo. :camera:
9. Cree los archivos y configure travis para que pase todas las pruebas en la versión 3.7 y 3.6 de python.
10. Haga commit los archivos necesarios para el funcionamiento de travis.
11. Refleje los cambios del repositorio en el repositorio remoto que creó en el primer paso.  :camera:
12. Prepare travis para que ejecute los tests cuando se realice algún cambio en la rama master.:camera:
13. Salte a la rama master del repositorio. 
14. Cree un archivo para travis para pasar las pruebas en la versión 2 y 3.6 de python. :camera:
15. Haga commit de los cambios realizados.:camera:
16. Haga merge de la rama de desarrollo con la rama master del repositorio y asocielo a la issue del Ejercicio A.:camera:
17. Elimine la rama desarrollo tanto en local como en remoto. :camera:
18. Actualice solo las referencias a los cambios remotos. :camera:
19. Realice los cambios necesarios en los archivos de docker para que despliegue este repositorio. :camera:
20. Haga commit de los cambios realizados.:camera:
21. Realice los cambios necesarios en los archivos de docker para solucionar el error al desplegar la base de datos en la rama de desarrollo. Elimine antes todas las imagenes existentes en su instalación de docker :camera:
22. Configure y añada los archivos necesarios para desplegar DECIDE en Heroku cada nueva versión subida al master del mismo.:camera:
23. Despliegue la aplicacion en Heroku. :camera:
24. Haga commit de los cambios realizados.:camera:

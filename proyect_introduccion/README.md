##  Instituto Tecnológico de Tijuana
    ## Depto de Sistemas y Computación
    ## Ing. En Sistemas Computacionales
    ## 1. Introduccion
    ## Autor : Juan Eduardo Gonzalez Vejar  #20212934
    ## Repositorio: pdd_projects 
    ## Fecha de revisión:    
    ## Objetivo del programa: Introduccion a los servicios de aws y Asciinema
    ## Descripcion (detallada): A partir de este proyecto se hara un acercamiento a los servicios de aws y el uso de las instancias para trabajar con un entorno ubuntu a traves de una conexion ssh desde nuestra computadora o cualquier otra         de manera remota, tambien del uso de asciinema para poder capturar en video todas los comandos empleados    

# INTRODUCCION
## Creacion de la instancia y ejecucion de la misma a traves de ssh
### Al entrar a AWS nos saldra esta ventana, seleccionamos EC2
![Imagen](https://github.com/EduardoGV117/pdd_projects/blob/main/proyect_introduccion/imagenes/Imagen1.png)
### configuramos la instancia a como la necesitamos (solo creamos la llave pem, elegimos ubuntu y potencia)
### le damos click en donde dice "correcto: el lanzamiento de la instancia se inicio correctamente" en esos numeros que salen despues le damos click
![Imagen](https://github.com/EduardoGV117/pdd_projects/blob/main/proyect_introduccion/imagenes/Imagen2.png)
### una vez ahi buscamos en el lado izquierdo las direcciones ip elesticas y asignamos una y le damos en asignar
![Imagen](https://github.com/EduardoGV117/pdd_projects/blob/main/proyect_introduccion/imagenes/Imagen3.png)
### al estar asignada corectamente la asociamos en el boton "asociar esta direccion IP elastica
![Imagen](https://github.com/EduardoGV117/pdd_projects/blob/main/proyect_introduccion/imagenes/Imagen4.png)
### en esta ventana donde dice instancia seleccionamos nuestra instancia ubuntu y le damos asociar
![Imagen](https://github.com/EduardoGV117/pdd_projects/blob/main/proyect_introduccion/imagenes/Imagen5.png)
### Ahora si ya estaria todo para conectarnos, esa nueva ip elastica sera fija en la cual ya con la misma podremos acceder a nuestro server ubuntu desde ssh. Procedemos a abrir cmd
![Imagen](https://github.com/EduardoGV117/pdd_projects/blob/main/proyect_introduccion/imagenes/Imagen6.png)
### En cmd primero buscamos la carpeta donde esta el archivo de la llave pem, en este caso es downloads (descargas) asi que ponemos "CD downloads" y despues el codigo de conexion que es "ssh -i pddllave.pem ubuntu@54.89.12.244 y le damos enter y nos conectara 
![Imagen](https://github.com/EduardoGV117/pdd_projects/blob/main/proyect_introduccion/imagenes/Imagen7.png)

## Instalacion de asciinema y configuracion inicial de la terminal
### Se mostrara un asciinema con todo el proceso:
[![grabacion asciinema](https://asciinema.org/a/njgaFztT9GP2UGDGBfe9ooCWB)](https://asciinema.org/a/njgaFztT9GP2UGDGBfe9ooCWB)

## Ya con configuracion en la terminal de ubuntu y corriendo un programa en c++ el cual despliega un saludo y una frase motivacional aleatoria
![Imagen](https://github.com/EduardoGV117/pdd_projects/blob/main/proyect_introduccion/imagenes/introduccion_imagen.png)


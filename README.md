# Como-funciona-la-seguiridad
Trabajo con apuntes de seguridad 2ºSMR



# Tema 1

### Seguridad informática
![Foto seguridad](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRUCJimdqTIA5hgrEvGdkKE32JGqykinAUkjw&s)

__Siempre que entramos en internet nos exponemos a a las amenazas y siempre intentamos evitar ser atacados__


### ***Objetivos***


* Confidencialidad: Que se garantice la privacidad para las personas autorizadas a dicha información.

* Disponibilidad: Que siempre se puedan acceder a los datos en todo momento.

* Integridad: Que los datos no serán modificados desde el inicio sin autorización. 

* No repudio: Que las dos partes sean quien dicen ser. 

Objetivos de la seguirdad informatica (que se utiliza)

    Autenticación: Identificar el emisor de un mensaje, creador de un documento, un equipo...
    
    Autorización: Controlar el acceso de los usuarios a zonas equipo y servicios. 
   
    Encriptación: Ocultar la información

    Copias de seguridad:
   
    Firewall: Intentos de conecxión no deseados 
    
    S. Proxys: Intermediario entre red de una empresa y otra externa
    
    Firma electronica: Garantizar la identidad de una persona 
    
    Leyes: Obligan a las empresas a asegurar la protección de datos personales

## Clasificacón de la seguridad
### Seguirdad fisica y lógica 

![Mas Seguridad](https://www.nicklauschildrens.org/NCH/media/img/general/kid-staring-at-gun.jpg?ext=.jpg)

#### Fisica
* Incendios 
    ~~~~
    Mobiliario ignifugo 
    Sistema antiinciendios
    Detector de humo
    ~~~~
* Inundaciones
    ~~~~
    Evitar ubicaciones con facilidad de entrada de aguas 
    Impermeabilizar paredes
    ~~~~
* Robos
    ~~~~
    Proteger mediante puertas, cámaras de seguirdad, vigilantes...
    ~~~~
* Señales electromagnéticas
    ~~~~
    Evitar ubicaciones con facilidad de entradas de señales electromagneticas 
    Usar filtros o cableado especial, fibra óptica.
    ~~~~
* Apagones
    ~~~~
    Utilizar SAI para tener tiempos suficientes para poder tener tiempo para reaccionar.
    ~~~~
* Sobrecargas eléctricas
    ~~~~
    Poner filtros de tensión para estabilizar la señal electrica 
    ~~~~
* Desastres naturales
    ~~~~
    No se puede hacer nada, pero si estar alerta informandose en organismos que informon estos. 
    ~~~~

#### Logica 

* Robos
~~~~
Cifrar la informacion 
Utilizar constraseñas para evitar el acceso a la infomración
S. Biometricos.
~~~~ 
* Perdida de información 
~~~~
Copias de seguridad
Sistemas tolerantes a fallos (RAID) 
Uso de discos redundantes (Repiten la información en muchos sitios)
~~~~
* Perdida de integridad en la información 
~~~~
Programas de chequeo de equipo (Sandra 2000)
Firma digital 
Instrucciones del S.O 
~~~~
* Entrada de virus
~~~~
Tener un antivirus actualizado 
~~~~
* Ataques desde la red
~~~~
Firewall, monitorización y uso de proxys
~~~~
* Modificaciones no autorizadas
~~~~
Uso de contraseñas dificiles
Listas de acceso 
Cifrar documentación
~~~~

## Seguridad activa y pasiva 

### Activa

* Conjunto de medidas que previenen evitar daños de S.I

|***Tecnicas*** | ***Que previene***|
| --- | --- |
|__Uso de contraseñas__ | Personas no autorizadas
|__Listas de control de acceso__| Personal no autorizado 
|__Encriptación__| No poder interpretar información 
|__Uso de software de seguridad informática__| Prevenir virus informáticos y de entradas indeseadas
|__Firmas y certificados digitales__ | Comprobar la procedencia 
|__Sistemas de ficheros con toleracia a fallos__| Prevenir fallos de integridad en caso de apagones
|__Cuotas de disco__| Previene que os usuarios que hagan un uso indebido de la capacidad de disco 


### Pasiva 

* La seguridad pasiva complenta la seguridad activa.

|***Tecnicas***| ***Como minimiza***|
|---|---|
Conjunto de discos redundantes | Podemos restaurar informacion 
|SAI|Una vez que la corriente se pierde utilizamos la baterias del SAI|
|Realizacion de copias de seguridad|A partir de las copias realizadas podemos informacion en caso de perdidas de datos| 


## Amenazas y fraudes en los sistemas de la información

Todo aquello que es propiedad de la 
empresa se denomina __*activo*__. Un activo es tanto el mobiliario de la oficina, como los equipos informáticos, como 
los datos que se manejan. Cualquier daño que se produzca sobre estos activos tendrá un impacto en la 
empresa.

__Por eso hay que hacer un plan de actuación__

* Identificar los activos, es decir, los elementos que la empresa quiere proteger 

* Formación de los trabajadores con seguridad

* Concienciación de la importancia de la seguridad

### Vulnerabilidad

Las vulnerabilidades de un sistema son una puerta abierta para posibles ataques

| Calificación | Definición|
|---|---|
|Critica|Porpaacion de un gusano de internet |
|Importante|Puede poner en peligro la confidencialidad, de datos de los usuarios|
|Moderada|Se puede recucir el impacto como configuraciones predeterminadas|
|Baja|Impacto es minimo|

#### Para mas información pincha en el siguiente enlance


[Informacion en seguridad](https://es.wikipedia.org/wiki/Seguridad_inform%C3%A1tica)
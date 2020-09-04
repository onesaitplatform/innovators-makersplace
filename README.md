# innovators-makersplace
Market Place IoT para Makers 3D contra el Covid-19 

Espacio público en el que compartir diseños 3D que puedan ayudar a la construcción de materiales para la lucha contra el covid e interactuar entre ellos a futuro. Dirigido a:

- Protección de personal sanitario (mascaras, viseras, pantallas, respiradores, etc)

- Vigilancia (piezas de drones, soporte para cámaras, etc..)

- Social (juguetes, artículos para escuelas, prótesis, etc..)


¿Qué podemos hacer con el market que hemos creado para el concurso?
- Nos autenticamos como usuario registrado.
- Podemos acceder al catálogo de diseños subidos y sus valoraciones por los usuarios de la web.
- Podemos ver en detalle estos diseños, en esta pantalla se pueden valorar y descargar.
- Tenemos la opción de compartir nuestras propias creaciones, asignandoles un nombre, una descripción corta, un resumen, subir una imagen y un fichero con la información del diseño.




Pasos seguidos para el desarrollo del proyecto:

En el entorono Lab se han creado dos Ontologías:
1.	Marketplace3DAsset: Contiene los modelos 3D y su información
![alt text](https://github.com/onesaitplatform/innovators-makersplace/blob/master/recursos/dom1.png)

2.	Marketplace3DComments: Contiene una entrada por cada valoración y comentario
![alt text](https://github.com/onesaitplatform/innovators-makersplace/blob/master/recursos/dom2.png)

Se ha creado un proyecto web:
market3d: la plataforma aloja de manera gratuita el proyecto web en el entorno cloudlab, por lo que es facil desarrollar y poder hacer un prototipo, como el que hemos subido.
![alt text](https://github.com/onesaitplatform/innovators-makersplace/blob/master/recursos/login.png)

Para la comunicación entre el proyecto web y las ontologías se han creado dos apis, apartir de la herramienta de la plataforma FlowEngine, pudiendo crear de manera sencilla flujos de entrada, tratamiento y salida de la información sin necesidad de crear un backend fuera de la onesait plataform
![alt text](https://github.com/onesaitplatform/innovators-makersplace/blob/master/recursos/flownengine2.png)
![alt text](https://github.com/onesaitplatform/innovators-makersplace/blob/master/recursos/flownengine3.png)


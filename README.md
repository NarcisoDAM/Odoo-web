# Funcionalidad del módulo web de odoo.

Este módulo permite al usuario de Odoo crear una página web sencilla para su negocio, del tipo que sea, y que esta implemente diversas funcionalidades que vamos a repasar a continuación y vienen dadas por defecto en Odoo.
En este trabajo vamos a explorar estas funcionalidades desde el punto de vista del usuario web, y no desde el punto tecnico del diseño o funcionalidad tecnica de cada sub-módulo del módulo web, por lo que no será un documento de información técnica sino mas bien una guía sencilla de las utilidades que nos ofrece.
Para organizarnos mejor, voy a repasar la estructura y funcionalidad basandome en un web generada de ejemplo mediante el contenido demo de Odoo. Y la estructura de este documento irá dada según la estructura de esta web de ejemplo.

![inicio-contenido](https://imgur.com/19LCamc.jpg)

En nuestra web de demostración, se nos da una estructura separada por diferentes páginas, cada una con unas funcionalidades bien definidas. La página de inicio en este caso, nos serviría para mostrar la información relevante de nuestro sitio web, como por ejemplo el producto que vendemos, servicio, o a qué se dedica nuestra compañía. Aquí podemos ver nuestro ejemplo:

![inicio](https://imgur.com/lgAs9Gf.jpg)

##### Bloques de estructura
Dentro de los bloques que Odoo nos ofrece para diseñar nuestra web, los bloques de tipo estructura son los que predominan en nuestra página de inicio, este tipo de bloques nos ayuda a exponer nuestra información de manera clara y según ciertos diseños, para elegir el que mas se adapte a nuestras necesidades, pudiendo mostrar nuestra información en forma de lista, de banner, de links o referencias, etc. Veámos algunos ejemplos:

- **Banner:** muestra la información que queremos, en este caso, un título, con una breve descripción y un enlace para contactar y poder ampliar información o contratar un servicio/comprar un producto.
![inicio-banner](https://imgur.com/kh5IuLO.jpg)
- **Number:** Este plugin podría ser como un contador de lo que queramos. Por ejemplo, para indicar el número de cursos que hay alojados en nuestra web o cualquier otra cosa.
![inicio-number](https://imgur.com/IFNV6Bg.jpg)
- **Masonry:** Otra forma de estructurar nuestro contenido, con una imagen principal y un apartado de tipo cuadrícula donde podrás escribir lo que quieras, añadir imagenes, etc.
![inicio-masonry](https://imgur.com/Exg7UGy.jpg)

Como podemos observar, los bloques de tipo estructura limitan su funcionalidad a mostrar información, pero dado que todos los bloques tienen este mismo fin, no creemos necesario incluirlos todos como ejemplo para evitar redundancias. 

##### Bloques de características
Este tipo de bloques nos permite exponer las características de nuestro producto o servicio de manera clara. Y en base a estas características también realizar comparaciones entre productos y precios por ejemplo.

- **Comparación:** Éste bloque nos permite comparar por ejemplo, diferentes ofertas de subscripción, o comparar diferentes versiones de un producto en venta para decidir en la compra de este o no. 
![caracteristicas-comparacion](https://imgur.com/sduQtGJ.jpg)
- **Steps:** crea guías con pasos claros y sencillos para realizar cualquier acción. Por ejemplo, en nuestro caso tenemos una muestra de como hacer para comprar en la tienda, mostrando la informacion mediante nuestro bloque "steps".
![caracteristicas-steps](https://imgur.com/OlqpgIP.jpg)
- **Tabla de contenido:** con este bloque podemos mostrar una tabla de contenido que haga referencia a cualquier parte de nuestra web, lo cual siempre es un bueno de cara al usuario para poder acceder al contenido deseado de manera rápida.
![caracteristicas-tabla-contenido](https://imgur.com/8QhWjUQ.jpg)

Al igual que con los bloques de tipo estructura, los bloques de tipo características se encargan de mostrar la información en con una estructura que facilita su exposicion al usuario.

##### Contenido dinámico

Los bloques de contenido dinámico nos ofrecen la posibilidad de añadir a nuestra página web contenido que se va modificando con el tiempo. Un ejemplo de esto podría ser el bloque encargado de mostrar los mensajes del foro de nuestra página web.

- **Contacto:** Con este bloque se despliega un formulario de contacto que se puede utilizar con la finalidad que uno quiera, para consultar sobre servicios, productos, etc.
![dinamico-contacto](https://imgur.com/2gtfe0v.jpg)
- **Contador:** El contador podría mostrar la cuenta atrás hasta la fecha en la que se va a celebrar un evento, o la fecha en la que sale a la venta un nuevo producto. 
![dinamico-contador](https://imgur.com/YBzLgis.jpg)
- **Facebook:** Pues como su propio nombre indica, este bloque nos permite añadir a nuestra web un pequeño botón donde podremos enlazar el perfil de facebook de nuestra compañia para facilitar su acceso a nuestros usuarios/clientes.
![dinamico-facebook](https://imgur.com/7F8kdR9.jpg)

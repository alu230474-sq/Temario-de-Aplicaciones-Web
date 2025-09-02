# Temario-de-Aplicaciones-Web
Accede a GitHub y crea un repositorio llamado Temario de Aplicaciones Web con el archivo README en donde investigarás con imágenes los temas propuestos.
![Uploading image.png…]()

# Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.  
# 1.-Introducción al desarrollo web 
El desarrollo web nació de la mano de Tim Berners-Lee en 1989 en el CERN, quien creó la World Wide Web, el primer navegador y el primer sitio web en 1991. La evolución pasó por la Web 1.0 (estática y basada en HTML básico), la Web 2.0 (interactividad, CSS, JavaScript y la consolidación de la colaboración), y la Web 3.0 (más dinámica, con inteligencia artificial y personalización).  

Las aplicaciones web estáticas entregan contenido fijo sin interacciones complejas, mientras que las dinámicas generan contenido personalizado y responden a usuarios en tiempo real. Las Single-Page Applications (SPA) ofrecen una experiencia fluida cargando el contenido dinámicamente sin recargar la página entera, y las Progressive Web Apps (PWA) combinan características web y nativas, funcionando sin conexión, ofreciendo notificaciones push y siendo más rápidas.  
 
# 2.Arquitectura de aplicaciones web  
En informática, el modelo cliente-servidor es un sistema de comunicación donde un dispositivo o programa (el cliente) inicia una solicitud de un servicio o recurso, y un dispositivo o programa potente (el servidor) procesa esa solicitud y devuelve la respuesta al cliente.  

La arquitectura de tres capas es un patrón de diseño de software que organiza una aplicación en tres niveles lógicos e interconectados: la capa de presentación (la interfaz de usuario), la capa de lógica de aplicación (o de negocio), y la capa de acceso a datos. Este enfoque busca la separación de responsabilidades para mejorar la escalabilidad, el mantenimiento y la flexibilidad de la aplicación.  

REST es un estilo arquitectónico para crear APIs, mientras que el diseño API-First es un enfoque de desarrollo que prioriza el diseño de la API antes de escribir código.  

# 3. -Lenguajes y tecnologías fundamentales  
HTML es el lenguaje fundamental para crear páginas web. Su propósito es estructurar y dar formato al contenido de un sitio web, definiendo elementos como párrafos, imágenes, enlaces, videos y tablas, para que un navegador web pueda mostrarlos correctamente.

CSS es un lenguaje que define la apariencia de los elementos HTML en una página web, controlando su diseño visual, como colores, tipografías, márgenes y el diseño general de la página.

JavaScript (JS) es un lenguaje de programación versátil usado principalmente para dar interactividad y contenido dinámico a las páginas web.

PHP es un lenguaje de programación de código abierto del lado del servidor, utilizado principalmente para crear sitios web dinámicos y aplicaciones web.

MySQL es un Sistema de Gestión de Bases de Datos Relacionales de código abierto que permite almacenar, gestionar y consultar datos organizados en tablas de filas y columnas, utilizando el Lenguaje de Consulta Estructurado (SQL).

# 4.-Control de versiones  
Git es un sistema de control de versiones, una herramienta que permite rastrear cambios y gestionar el historial de un proyecto, funcionando de manera local en tu computadora. Por otro lado, GitHub es una plataforma web que utiliza Git para ofrecer un servicio de alojamiento de repositorios en la nube, facilitando la colaboración en equipo, el trabajo remoto y proporcionando herramientas de gestión de proyectos, como la gestión de incidencias y la revisión de código.  

Un flujo de trabajo con ramas, merge y pull requests es una práctica común en el desarrollo de software con Git donde los desarrolladores crean ramas separadas (branches) para trabajar en nuevas funciones o correcciones, hacen "pull requests" para proponer que sus cambios se unan (merge) a la rama principal, permitiendo la revisión de código y la colaboración antes de que se integren los cambios en el código base principal.  

# Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web  
# 1.-Diseño e implementación del frontend  
Una maquetación (o wireframe) es el esqueleto de un diseño que se enfoca en la estructura y el flujo, mientras que un mockup es una representación visual más detallada y estática que incluye la apariencia estética como colores, tipografía e imágenes.  

Una API (interfaz de programación de aplicaciones) es un conjunto de reglas y definiciones que permite que dos aplicaciones de software diferentes se comuniquen entre sí, actuando como un puente para el intercambio de datos y servicios. Permite a las aplicaciones enviar y recibir información de manera estandarizada, facilitando la creación de aplicaciones más complejas al no tener que desarrollar todas sus funcionalidades desde cero.  

# 2.-Diseño e implementación del backend  
Un servidor es un ordenador potente (hardware) o un programa (software) que proporciona recursos, servicios y datos a otras computadoras o dispositivos, conocidos como "clientes", a través de una red como Internet.  
 
El manejo de peticiones y respuestas HTTP implica que un cliente (como un navegador web) envía una petición a un servidor, que luego responde. Las peticiones incluyen un método HTTP (GET, POST, etc.) y la dirección del recurso, mientras que las respuestas contienen un código de estado (como 200 OK o 404 No encontrado) y el recurso solicitado, si lo hay, o un mensaje de error. Este intercambio es la base del modelo cliente-servidor en la web.  
 
Para conectarte a una base de datos MySQL necesitas: el nombre del servidor, el puerto, el nombre de usuario y la contraseña de la base de datos, y la capacidad de acceder al esquema y las tablas deseadas.  

Para conectarte a una base de datos PostgreSQL, utiliza el cliente de línea de comandos psql ingresando el comando psql -U tu_usuario -d tu_base_de_datos o una herramienta gráfica como DBeaver o pgAdmin, introduciendo los detalles de la conexión: nombre de host, número de puerto, nombre de usuario y contraseña.  

En la Interfaz web de MongoDB Atlas, busque el clúster al que conectarse y haga clic en el botón “Conectar“ junto a su nombre. En la siguiente pantalla, seleccione el método que está utilizando para conectarse a MongoDB y se le proporcionará una cadena de conexión adecuada para su clúster.  

# 3.-Bases de datos  
 El modelado de datos es el proceso de crear una representación visual de los datos y sus interconexiones, que sirve para estructurar, almacenar y acceder a la información de manera clara y eficiente.  
 
 Los ORMs (Object Relational Mappings) o Mapeadores de Objetos Relacionales son una alternativa frente al SQL tradicional de las bases de datos, porque a través de este modelo de información no tendrás que seguir utilizando el SQL.  

CRUD (Create, Read, Update, Delete) es un acrónimo que describe las cuatro operaciones fundamentales de persistencia de datos: Crear (añadir nuevos datos), Leer (recuperar o ver datos existentes), Actualizar (modificar datos existentes) y Eliminar (borrar datos).  

# 4.-Seguridad básica en aplicaciones web  
La validación en el lado del cliente es una verificación inicial y una característica importante para garantizar una buena experiencia de usuario; mediante la detección de datos no válidos en el lado del cliente, el usuario puede corregirlos de inmediato.  

La autenticación verifica que una persona o sistema es quien dice ser, usando factores como contraseñas o biometría, mientras que la autorización determina a qué recursos y con qué nivel de acceso tiene permiso ese usuario una vez que su identidad ha sido confirmada.   

# Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional  
# 1. -Integración de frontend y backend  
La interfaz de usuario (UI) de frontend es la parte de un sitio web o aplicación con la que los usuarios interactúan directamente, todo lo que se ve y experimenta en el lado del cliente, como menús, botones, imágenes y diseño.  

La Application Programming Interface (API) es un conjunto de patrones que forman parte de una interfaz que permite la creación de plataformas de una forma más sencilla y práctica para desarrolladores.  

Los clientes envían solicitudes a los servidores, especificando acciones y datos. Respuestas: Los servidores procesan las solicitudes y envían las respuestas correspondientes, incluyendo códigos de estado y datos . Al dominar estos fundamentos, los desarrolladores backend pueden crear aplicaciones web eficientes y fiables.  

# 2.- Almacenamiento en Servidor  
Los tipos de servidor se pueden clasificar por su función, como los servidores web, que alojan sitios web; servidores de base de datos, que almacenan información; servidores de correo, que gestionan emails; o servidores de archivos, que comparten documentos. También pueden clasificarse por su arquitectura, incluyendo servidores dedicados, que tienen recursos exclusivos; servidores compartidos, que comparten recursos entre varios usuarios; y servidores virtuales, que emulan múltiples servidores físicos en uno solo.  

Un servidor es el equipo físico o virtual que aloja los datos y archivos de un sitio web, mientras que un servicio de hosting o alojamiento es el alquiler de un espacio y los recursos de ese servidor para publicar el sitio en Internet.  

Los principales proveedores de servicios de almacenamiento, tanto personales como empresariales, incluyen a gigantes como Google Drive (Google Workspace), Microsoft OneDrive y Dropbox, además de otras opciones como pCloud, iCloud, Box y MEGA, cada uno con características y enfoques diferentes, como la integración con sus suites de productos, el enfoque en la seguridad o la colaboración para empresas.   

# 3.-Optimización y rendimiento  
La optimización de recursos (imágenes y scripts) es el proceso de hacerlos lo más pequeños y eficientes posible para mejorar la velocidad y el rendimiento de un sitio web. Las técnicas incluyen la compresión de imágenes, el uso de formatos modernos como WebP, la carga diferida (lazy loading), la minificación y concatenación de scripts, y el uso de CDNs para distribuir el contenido.  
  
El despliegue de aplicaciones web es el proceso de transferir y configurar una aplicación desde un entorno de desarrollo a un entorno de producción, haciéndola pública y accesible a los usuarios finales. Este proceso incluye la instalación y configuración de servidores, bases de datos, y la implementación del código, y es una etapa crucial del ciclo de vida del desarrollo de software que requiere un plan bien estructurado para asegurar la estabilidad y escalabilidad de la aplicación.  

CI/CD (Integración Continua y Despliegue/Entrega Continua) es un conjunto de prácticas de desarrollo de software que automatizan la integración y el despliegue de código, permitiendo lanzamientos de software más rápidos y confiables al reducir tareas manuales y probar automáticamente los cambios.  

La documentación de proyectos es la colección de todos los documentos y materiales escritos que describen los objetivos, alcance, presupuesto, riesgos y metodologías de un proyecto. Su propósito es asegurar la transparencia, facilitar la comunicación y la toma de decisiones informadas, y servir como registro histórico para el seguimiento del proyecto a lo largo de su ciclo de vida.  

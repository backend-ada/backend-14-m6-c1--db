<h1 align="center"> BASES DE DATOS </h1>
<h3 align="center"> ¿Qué son los datos?  </h3>

![Base de datos](https://fotografias.lasexta.com/clipping/cmsimages01/2019/01/16/79CA7660-6216-4CF0-961F-A217BD3045F2/97.jpg?crop=725,408,x137,y0&width=1600&height=900&optimize=high&format=webply)

En el transcurso de los últimos años, los datos se convirtieron en el nuevo petróleo, el "oro negro" que mueve al mundo. Toda la tecnología, aplicaciones y dispositivos que usamos a diario están diseñados para recoletar y procesar datos. Hay un mercado paralelo ENORME que comercia grandes masas datos, si les interesa saber más, lean el artículo en la sección de _LINKS_ que se llama **Big Data**.

En los capítulos de la serie **Black Mirror**, la tecnología cumple un rol fundamental y determinante. En el capítulo _Nosedive_, se muestra en forma de "ficción" lo que sucede hace algunos años en el sistema de vigilancia masiva de China. En este, la vida diaria de las personas está en gran parte determinada por datos: según su inclinación política, comentarios y publicaciones que hagan al respecto en una gran red social controlada por el estado, la libertad que las personas tienen de obtener ciertos trabajos, acceder al transporte público, comprar en ciertos lugares, etc., está directamente determinada por su puntaje social resultado de su actividad en esta red. Es decir, que hacer comentarios en contra del gobierno puede hacer que la persona pierda acceso a su cuenta bancaria.

Por poner otro caso, en las fábricas industriales modernas, se instalan un montón de dispositivos electrónicos conectados en red, capaces de obtener datos físicos tales como la medición de temperatura, consumo eléctrico, o cualquier dato obtenido de algún sistema de medición electrónico, y se envian a un servidor central para su procesamiento y visualización en tiempo real, desde cualquier parte del mundo. Se logra así el despliegue de un "sistema nervioso" que centraliza todos los datos y permite tomar decisiones basados en datos concretos reales. Esto ayuda muchísimo a mejorar la eficacia y eficiencia en la producción.

Los datos entonces no existen solamente para ser almacenados, sino que se los puede interpretar y usar para determinar las acciones a realizar. Por eso se dice que los datos son el nuevo petróleo, el "oro negro", cuánto más datos tienen las empresas, mejor pueden segmentar su publicidad, mejores decisiones comerciales pueden tomar, etc. El almacenar y gestionar los datos es EL gran negocio de las bases de datos.

#### ¿Qué son las bases de datos?

Las bases de datos son conjuntos organizados de información relacionada que se encuetra agrupada y estructurada, con un fin determinado. Es importante recalcar que **datos** NO es sinónimo de información. Los datos por sí solos no tienen un signifcado en particular hasta que se les da un contexto. Por ejemplo, los libros de una biblioteca, las películas de un cineclub, etc...

Modernamente, las bases de datos están almacenadas y organizadas electrónicamente, usando los llamados **Sistemas Gestores de Bases de Datos** o **DBMS**, por las siglas en inglés de **DataBase Management System**, para gestionarlas. Un **DBMS** es un software encargado de guardar los datos, asegurar su integridad y ofrecer una interfaz para poder interactuar con ellos a través de consultas. Los gestores más usados son los relacionales o **RDBMS**, **R**elational **D**ata**B**ase **M**anagement **S**ystem.

#### Origen del modelo relacional

En 1970, Edgar Frank "Ted" Codd, define el modelo relacional. Este modelo busca estructurar cómo se guarda la información, cómo se consulta y evitar redundancias en la información, es decir, que los datos no se repitan.

Supongamos que una alumna de ADA está inscripta en tres cursos. Entonces, la tenemos guardada en "Backend", en "Frontend" y en "Bases de Datos".

¿No sería mejor que cada grupo de datos esté en un único lugar y que los relacionemos de alguna forma? Por ejemplo, todas las alumnas por un lado, y en otro todos los cursos. Entonces, relacionamos esos datos, de forma tal de poder consultar esa relación entre "Alumnas" y "Cursos", y ver qué alumnas están en cada curso, o que cursos tienen inscriptas tales alumnas.

![DB TABLES](https://i.ibb.co/X2pYtfT/tablas.png)

Ese es el modelo relacional, que agrupa la información a través de tablas. Las tablas, como las de Excel, están compuestas de registros y campos. Los registros hacen referencia a una entidad, es decir, a una alumna o curso siguiendo con el ejemplo anterior. El nombre de cada entidad de cada tabla sería un campo, así como su ID, etc. De esta manera se estructuran los datos en el modelo relacional.

#### ¿Qué es SQL?

Las bases de datos que siguen este modelo, se denominan bases de datos relacionales. **IBM** desarrolló un lenguaje de consultas estructurado llamado **Structured English Query Language** y sus iniciales eran **SEQUEL**. Años después, evolucionaron el lenguaje y lo denominaron **SQL**, **Structured Query Language**.

**SQL** es un lenguaje que nos permite consultar la información de una base de datos relacional. De ahí el “estructurado”. Primero se le da una estructura a los datos para luego consultarlos. SQL nos permite manipular los datos, no solamente consultarlos, sino también escribirlos, modificarlos, eliminarlos, y también diseñar la estructura de la base de datos.

En 1977, los ingenieros de la época crean Oracle, que es el primer sistema gestor de bases de datos relacionales comercial del mundo. Hasta ahora, Oracle es una de las empresas más importantes del mundo. Es la segunda empresa desarrolladora del software con mayor valuación. Ellos se encargan de desarrollar soluciones para empresas. Oracle es para el mundo corporativo. No solamente se encarga de hacer base de datos. Hoy en día, Oracle hace Cloud Computing, Machine Learning, soluciones con blockchain, etc.

En 1989, Microsoft lanza su respuesta a Oracle llamada SQL Server, un sistema de gestión de bases de datos relacionales pensada en empresas. No está pensada en el usuario final. No está pensada en que tú crees tu base de datos en tu máquina. Aunque luego también sacaron una versión express, que es una versión gratis (limitada), pero que puedes utilizarla para hacer algunas pruebas o proyectos pequeños.

En 1995, en el contexto de los años de la explosión de la web, del open source, del desarrollo de sistemas de gestores de base de datos open source, aparece MySQL: un RDBMS que se integra muy bien con PHP. Y como PHP era el lenguaje más importante de la web, MySQL será la base de datos más importante en el mundo web, fácil para comenzar, con una curva de aprendizaje sencilla y, además, muy rápida en sus consultas. No requiere configurar demasiadas cosas.

En 1996, aparece PostgreSQL, el sistema gestor de base de datos que cumple con varios estándares y trae procedimientos almacenados, trigger, funciones y cosas que MySQL no tenía. Además, está inspirado en Oracle, por lo tanto, es bastante sencillo migrar base de datos de PostgreSQL a Oracle. Eso hace que sea una base de datos más poderosa y repito, preferida por quienes buscan más consistencia en los datos. Si quieres aprender PostgreSQL, tenemos un curso en EDteam, que te enseña desde cero, hasta crear tu primer proyecto.

En los años 2000, la década de las redes sociales, de los buscadores y de los smartphones, aparecen dos bases de datos importantes. La primera es SQLite, un RDBMS más ligero y más pequeño, para usos tal vez más específicos. Además, tiene una gran peculiaridad y es que no usa la arquitectura del cliente-servidor, sino que guarda los datos en archivos, que están dentro del mismo programa. Es un paradigma diferente. Entonces, es base de datos en archivos. El uso más común de SQLite, son las aplicaciones móviles, particularmente en los casos en los que es necesario guardar información en el teléfono. Ya sea para trabajar en modo offline o guardar alguna información importante que necesites para que la aplicación funcione.

La otra es MariaDB, que es un MySQL 100% libre, sin versión paga. Tiene algunas mejoras, obviamente, pero en esencia, es un MySQL open source. Es 100% compatible con MySQL, así que cualquier cosa que hagas con MySQL, la podés hacer. Si tenés un sistema o aplicación corriendo sobre MySQL, puedes migrarlo tranquilamente a MariaDB.

<h3 align="center"> Ejemplo práctico: ¿Cómo modelar un base de datos? </h3>

Supongamos que una clienta nos pide desarrollar un sistema que permita ordenar los datos de las empleadas de su centro de estética. Comenzó primero haciendo trabajos de _manicure_ para su amigos y conocidos, pero al cabo de un año se expandió inesperadamente llegando a contratar a 10 empleadas. Al no preever esta situación, tuvo que remitirse unos cuantos meses a sus apuntes que recopiló de manera manual en su agenda personal.

Luego de entrevistarla, sacamos en limpio que lo que ella necesita YA, es organizar los datos de sus empledas en un solo lugar, y además tener bien en claro la especialidad de cada empleda.

Cada empleada debe tener la siguiente información asociada: nombre, servicio en la que es especialista, fecha en la que comenzó a trabajar y su número de celular. Los servicios que el local ofrece son: semi permanente simple, semi permanente con diseño, capping, uñas en gel, uñas en gel con diseño.

#### Diagrama Entidad-Relación | Entity-Relationship Diagram (ERD)

El primer paso necesario para empezar a modelar nuestro software que le permita al cliente el acceso cómodo y rápido a su información, es el de abstraer sus necesidades, desarrollar las tablas con los datos y establecer las relaciones entre ellas. A este proceso se lo conoce como modelado/diseño, y el objetivo es desarrollar el **Diagrama Entidad Relación (ERD)**. El proceso más dificil puede ser el de determinar cómo y dónde organizar los datos, por lo que uno de estos diagramas nos puede ayudar a simplificar mucho nuestro trabajo.

Los diagramas nos muestran de qué entidades está compuesta nuestra BBDD, los atributos que tienen, las relaciones entre las entidades y la cardinalidad. Veamos qué es cada cosa:

![ERD](https://i.ibb.co/X3LRnTM/erd.png)

En el diagrama podemos ver:

-   Entidades: cada diagrama que representa cada una de las tablas, **"Empleadas"** y **"Servicios".**
-   Atributos: cada dato relativo a cada entidad: nombre, id, fecha_inicio, servicio_id, celular, etc.
-   Relaciones: en este caso en particular, los datos que están relacionados son los IDs de la tabla **"Servicios"**, con la columna servicio_id de **"Empleadas"**.
-   Cardinalidad: hace referencia al tipo de relación, que en este caso es de **"uno a muchos"** ó **"1:N"**. Más adelante vamos a ver bien este punto, por ahora tengamos presente que cada empleada puede ofrecer sólamente un servicio, y que cada servicio puede ser ofrecido por una o varias empleadas.

Las tablas que vamos a generar nos van a quedar más o menos así:

![TABLAS](https://i.ibb.co/FsVpB4y/tablas-II.png)

<h1 align="center"> LINKS </h1>

-   [Black Mirror: Nosedive](https://www.youtube.com/watch?v=EcspUD0kF7g)
-   [Cómo los algoritmos configuran nuestro mundo](https://www.youtube.com/watch?v=sLd-SxE7__8)
-   [Big Data](https://www.forbesargentina.com/innovacion/el-negocio-datos-consiste-famoso-big-data-n13621)

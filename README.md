# Basics-DB #
### Fundamentos de Bades de Datos ###
***
- Las **Bases de Datos** surgen de la idea de tener un espacio dónde poder almacenar de una forma mucho más eficiente toda la información de nuestros proyectos. Anteriormente este almacenamiento era en papel, y aunque a la fecha algunas empresas por temas de regulación lo siguen haciendo en parte así, el tener una **Base de Datos** ha permitido tener mucho más control de la información.

- Los **datos no son información**. Solo en el momento que creamos un reporte que contenga ciertos datos, éstos se convierten en información.

- **DBMS** = Data Base Management System o **SGBD** = Sistemas de Gestión de Bases de Datos.

### Tipos de Bases de Datos y sus aplicaciones en la industria ###
***
Las **Bases de Datos** se pueden dividir en:

- **Bases de Datos Relacionales**
- **Bases de Datos no Relacionales**

**Bases de Datos Relacionales** empresariales (más importantes)

- **DB2**
- **SQL Server**
- **Oracle**

Algunas **Bases de Datos Relacionales** comunes:

- MariaDB: Es una distribución de Bases de Datos que deriva de MySQL.
- PostrgreSQL: Esta es una Base de Datos comunitaria pero tiene una versión entreprise que tiene soporte.

Algunas Bases de **Datos No Relacionales** comunes:

- **Redis:** Una Base de Datos que en la actualidad se trabaja mucho.
- **neo4j:** Es una Base de Datos basada en nodos. Está centrada en grafos que nos va a permitir encontrar relaciones entre objetos. Muy común en eCommerce.
- **Cassandra:** Es una Base de Datos muy importante del proyecto Apache. Trabaja con grandes volúmenes de datos.
- **MongoDB:** Es una Base de Datos en NoSQL que se basa en trabajar en varias instancias.

### Visión general de los datos ###
***
**¿Qué es un dato?**

Un dato es algo que nos va a permitir describir un objeto. Ese objeto global lo vamos a poder llamar “Entidad”. Una entidad puede estar llena de datos.

Existen **3 niveles de Abstracción** en las **Bases de Datos:**

- **Conceptual:** Se tiene que empezar a modelar una Base de Datos dependiendo de lo que se quiere hacer basado en los conceptos de “entidad” y “relación”.
- **Lógico:** El diagrama lógico nos va a resolver ciertas dudas de consistencia, para evitar crear loops o evitar que tenga cosas que no tengan sentido en nuestro proyecto.
- **Físico:** Es finalmente cómo lo va a ver la Base de Datos.

### Tipos de Datos ###
***
Igual que en cualquier lenguaje de programación, existen variables en las **Bases de Datos:**

- **Caracteres:** Pueden ser desde letras hasta caracteres especiales.
- **Numérico:** Del 0 al 9 pero con una longitud especial.
- **Varchar:** Caracteres con un formato más variable.
- **Imagen**
- **Fecha:** Generalmente van acompañadas de una hora.
- **Moneda:** esto facilita todo si se trabaja con diferentes denominaciones.
- **Texto:** Variables que tienen mayor tamaño que un char o que un varchar.
- **Bit:** Se puede trabajar con 1 y 0 o también con verdadero y falso.
- **Decimal**

**Esquema** = Es la estructura lógica que va a tener una Base de Datos.

**Instancia** = Contenido de partículas que tiene una Base de Datos en un instante de tiempo.

¿Qué debemos esperar para modelar una **Base de Datos**?
- Los datos.
- La relación que existe entre los datos.
- Restricciones de los datos.

Existen 3 cosas para poder hacer la descripción de una **Base de Datos:**

- **DML** = Data Manipulation Language o Lenguaje de Manipulación de Datos.
- **DDL** = Data Definition Language o Lenguaje de Definición de Datos.
- **SQL** = Structured Query Language o Lenguaje de Consulta Estructurada.

**Otros tipos de Bases de Datos:**

- Bases de Datos Relacionales
- Basadas en Objetos Relacionales
- XML
- NoSQL
- In-Memory

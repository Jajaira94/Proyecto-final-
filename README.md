El tema dado a escoger fue Gestion de Mascotas en donde se podra visualizar la Aplicación CRUD desarrollada en Java Swing con conexión MySQL.
- - - - - - - - - - - - - -  - - - - - - - - - - - - - -  - - - - - - - - - - - - - - 
Las herramientas que se utilizo fueron:
*Java SE* 
*MySQL*
*JDBC*
*IntelliJ IDEA*
*GitHub*
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 
Primero comence por el diceño en Figma donde realice las pantallas:

Ingreso de cuenta (usuario, contraseña, Ingresar).

Menú Administrador (gestionar dueño, gestionar mascotas, gestionar controles medicos, gestionar reportes).

Menú caja (registro de mascota, registro de controles, registro de factura).

Registro de  Mascota (dueño, nombre de mascota, especie, raza, guardar).
- - - - - - - - - - - - - - - -  - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 
Siguiente punto fue el Diagrama UML

Usuario (id, usuario, contraseña, ingresar)

Dueño (id, nombre, teléfono, dirección)

Mascota (id, nombre, especie, raza, edad, dueño)

ControlMedico (id, mascota, fecha, diagnóstico, tratamiento)
- - - - - - - -- - - - - - - - - - - - - -- - - - - - - - - - - - - - - - - - - - - - - - - - - 
Continue con la Implementación en Java Swing
- - - - - - - - - - - - - - - - - - - - - - -  - - - - - - - - - - - - - - - - - - - - -  --  --  -
La utilizacion de base de datos en MySQL en donde se crearon 5 tablas 

-La tabla de usuarios- (id, nombre_usuario, contraseña, rol)
**(01, Emily Lozada, 2018, admin)**
**(02, Bryan Cisneros, 2021, cajero)**

-Tabla de dueños- 
-Tabla de mascotas-
-Tabla de controles medicos-
-Tabla de facturas-
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
Implementación en Java Swing con conexión a MySQL
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 
Creacion de CRUDS (dueños, mascotas y controles medicos)
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
Terminamos con Main.Java
- - - - - - - - - - - - - - - - - - - - - - - -  -

**Video de la ejecucion del programa**
https://www.loom.com/share/37078dfdf0284145aa67c1090c5ded41?sid=a68d0ce0-de4e-4e2c-9ea3-fda0d0aceb99

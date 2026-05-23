# Hotel Alura - Sistema de Gestión de Reservas / Hotel Reservation Management System

[English version below](#english)

---

## Español

### Descripción del Proyecto
El proyecto **Hotel Alura** es un sistema de gestión diseñado para administrar las reservas y los huéspedes de un hotel. Este software proporciona una interfaz gráfica intuitiva que permite al personal del hotel gestionar operaciones diarias de manera eficiente y centralizada, eliminando el uso de papel y optimizando los procesos administrativos.

### Problema que Resuelve
La gestión manual de reservas y datos de huéspedes es propensa a errores, pérdida de información y desorganización. Este sistema centraliza toda la información en una base de datos segura, permitiendo registrar, buscar, modificar y eliminar datos de manera rápida y precisa. 

### Tecnologías Utilizadas
* **Java:** Lenguaje principal de desarrollo.
* **Java Swing:** Para la creación de la interfaz gráfica de usuario (GUI).
* **JDBC (Java Database Connectivity):** Para la conexión e interacción con la base de datos.
* **MySQL:** Sistema de gestión de bases de datos relacionales utilizado para el almacenamiento persistente.
* **Patrón de Arquitectura MVC (Modelo-Vista-Controlador):** Para una organización escalable y mantenible del código.

### Características Principales
* Autenticación de usuarios (Login).
* Registro, edición y eliminación de reservas.
* Registro, edición y eliminación de datos de huéspedes, vinculados a sus reservas.
* Búsqueda de registros en la base de datos desde la interfaz de la aplicación.

### Cómo Usar e Instalar
1. **Requisitos Previos:** Asegúrate de tener instalado Java Development Kit (JDK) 8 o superior y MySQL.
2. **Configuración de Base de Datos:** 
   * Crea una base de datos en MySQL para el hotel.
   * Ejecuta los scripts de creación de tablas correspondientes para `huespedes` y `reservas`.
   * Actualiza las credenciales de tu base de datos (usuario y contraseña) dentro de la configuración de conexión JDBC en el proyecto.
3. **Ejecución:** 
   * Abre el proyecto en tu IDE favorito (Eclipse, IntelliJ IDEA o NetBeans).
   * Añade el conector MySQL (Driver JDBC) a las dependencias/librerías de tu proyecto (estos se encuentran dentro de la carpeta `JARS`).
   * Compila y ejecuta la clase principal desde la vista de inicio de sesión para lanzar la aplicación.

---

<a name="english"></a>
## English

### Project Description
The **Alura Hotel** project is a management system designed to handle hotel reservations and guests. This software provides an intuitive graphical interface that allows hotel staff to manage daily operations efficiently and centrally, eliminating paper-based processes and optimizing administrative workflows.

### Problem Solved
Manual management of reservations and guest data is prone to errors, information loss, and disorganization. This system centralizes all information in a secure database, allowing users to register, search, modify, and delete data quickly and accurately.

### Technologies Used
* **Java:** Primary programming language.
* **Java Swing:** Used for building the Graphical User Interface (GUI).
* **JDBC (Java Database Connectivity):** Used for connecting and interacting with the database.
* **MySQL:** Relational database management system for persistent data storage.
* **MVC (Model-View-Controller) Architecture Pattern:** Employed for scalable and maintainable code structure.

### Key Features
* User Authentication (Login system).
* Registration, modification, and deletion of reservations.
* Registration, modification, and deletion of guest data, linked to their reservations.
* Database record searching directly from the application interface.

### How to Use and Install
1. **Prerequisites:** Ensure you have Java Development Kit (JDK) 8 or higher and MySQL installed on your system.
2. **Database Setup:**
   * Create a MySQL database for the hotel.
   * Run the corresponding table creation scripts for `guests` and `reservations`.
   * Update your database credentials (username and password) within the JDBC connection settings in the project.
3. **Execution:**
   * Open the project in your preferred IDE (Eclipse, IntelliJ IDEA, or NetBeans).
   * Add the MySQL connector (JDBC Driver) to your project's dependencies/libraries (these can be found inside the `JARS` folder).
   * Compile and run the main class from the login view to launch the application.

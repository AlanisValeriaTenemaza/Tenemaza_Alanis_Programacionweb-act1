UNIVERSIDAD DE LAS FUERZAS ARMADAS ESPE

nOMBRE ALANIS TENEMAZA

## Descripción
La aplicación de gestión de tareas permite a los usuarios crear, leer, actualizar y eliminar tareas de manera eficiente. Está diseñada para ser utilizada en el hogar y consta de dos partes principales: un backend basado en Express con MySQL y un frontend desarrollado con Stencil y TypeScript.

## Instrucciones

### Backend


1. **Instalar las Dependencias**
   - Se Ejecuto el siguiente comando para instalar todas las dependencias necesarias:
     ```bash
     npm install
     ```

2. **Configurar la Base de Datos MySQL**
   - Se Creo una base de datos llamada `tareas_db` en el servidor MySQL. 
     ```sql
     CREATE DATABASE tareas_db;

     USE tareas_db;

     CREATE TABLE tareas (
         id INT AUTO_INCREMENT PRIMARY KEY,
         titulo VARCHAR(255) NOT NULL,
         descripcion TEXT,
         completado BOOLEAN DEFAULT FALSE,
         fecha_creacion TIMESTAMP DEFAULT CURRENT_TIMESTAMP
     );
     ```

3. **Iniciar el Servidor**
   - Se Ejecuto el siguiente comando para iniciar el servidor backend:
     ```bash
     npm start
     ```

### Frontend

1. **Instalacion las Dependencias**
   -  Se Navego al directorio del frontend y ejecuta el siguiente comando para instalar todas las dependencias necesarias:
     ```bash
     cd task-manager-frontend
     npm install
     ```

2. **Inicio del Servidor de Desarrollo**
   - Se Ejecuto el siguiente comando para iniciar el servidor de desarrollo del frontend:
     ```bash
     npm start
     ```



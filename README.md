# Backend-OpticaMiroo

---

# **Instrucciones para la configuración y ejecución del backend (Spring Boot)**

## **1. Iniciar XAMPP**

Asegúrate de tener **XAMPP instalado y en ejecución**.
En el panel de control de XAMPP:

* Activa **Apache**
* Activa **MySQL**

El backend necesita que MySQL esté funcionando para poder conectarse a la base de datos.

---

## **2. Crear el esquema en MySQL**

Con MySQL activo:

1. Abre **phpMyAdmin** (o cualquier cliente MySQL).
2. Crea un nuevo esquema (base de datos) llamado:

```
base
```

Este esquema será utilizado por el backend.

---

## **3. Verificar o crear las tablas**

Revisa el esquema `base`:

* Si las tablas necesarias **ya existen**, no tienes que hacer nada.
* Si **no existen**, ejecuta el **script SQL** proporcionado para crear las tablas y datos iniciales.

Esto asegura que la aplicación tenga la estructura mínima para funcionar.

---

## **4. Ejecutar el backend (Spring Boot) con VS Code**

1. Abre el proyecto del backend en **Visual Studio Code**.

2. Asegúrate de tener instalada la extensión:

   **Spring Boot Extension Pack**
   (incluye el **Spring Boot Dashboard**)

3. En la barra lateral de VS Code, busca el panel:

   **Spring Boot Dashboard**

4. Dentro del panel, selecciona tu aplicación Spring Boot y presiona:

   **Run** (▶️)

La aplicación iniciará y se conectará automáticamente a la base de datos `base`.


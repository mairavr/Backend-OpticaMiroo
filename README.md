# Backend-OpticaMiroo

---

# **Instrucciones para la configuración y ejecución del backend (Spring Boot)**

## **1. Iniciar XAMPP**

Asegúrate de tener **XAMPP instalado y en ejecución**.
En el panel de control de XAMPP activa:

* **Apache**
* **MySQL**

El backend necesita MySQL para conectarse correctamente a la base de datos.

---

## **2. Crear el esquema en MySQL**

Con MySQL activo:

1. Abre **phpMyAdmin** (o tu cliente MySQL preferido).
2. Crea un nuevo esquema con el nombre:

```
base
```

Este será el esquema utilizado por el backend.

---

## **3. Verificar o crear las tablas**

Ingresa al esquema `base` y revisa si ya existen las tablas necesarias.

* Si **ya existen**, continúa al siguiente paso.
* Si **no existen**, ejecuta el **script SQL** correspondiente para generar la estructura de la base de datos (tablas, relaciones y datos iniciales).

Esto garantiza que la aplicación tenga la estructura necesaria para funcionar.

---

## **4. Ejecutar el backend (Spring Boot) desde VS Code**

1. Abre la carpeta del proyecto backend en **Visual Studio Code**.

2. Asegúrate de tener instalada la extensión:

   **Spring Boot Extension Pack**
   (incluye el **Spring Boot Dashboard**)

3. En la barra lateral de VS Code, localiza el panel:

   **Spring Boot Dashboard**

4. Selecciona tu aplicación Spring Boot y presiona:

   **Run** (▶️)

Esto iniciará el servidor backend, el cual se conectará automáticamente a la base de datos `base`.

---

## **5. Credenciales de prueba**

Puedes usar los siguientes usuarios de prueba para iniciar sesión en el sistema:

### **Administrador**

```
Correo: carlos.munoz@opticamiroo.cl
Contraseña: cmunozmiroo123
```

### **Cliente**

```
Correo: juan.perez@opticamiroo.cl
Contraseña: Jperez#2025
```

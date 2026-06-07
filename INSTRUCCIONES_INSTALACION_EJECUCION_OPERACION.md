# Instrucciones de instalacion, ejecucion y operacion

**Proyecto:** VetCare - Sistema de Gestion Veterinaria  
**Integrante:** Ochoa Castro Fernando  
**Grupo:** 2-2  
**Repositorio:** https://github.com/Fer8acc/VetCare_Fernand2  
**Fecha:** 06 de junio de 2026

## 1. Requisitos

Para ejecutar el sistema se necesita:

- Windows.
- XAMPP instalado.
- Apache y MySQL activos.
- Navegador web.
- Acceso a phpMyAdmin.

## 2. Instalacion

1. Descargar o clonar el repositorio del proyecto.
2. Copiar la carpeta del proyecto dentro de la carpeta `htdocs` de XAMPP.

Ejemplo:

```txt
D:\xampp\htdocs\VetCare_Fernando
```

3. Abrir XAMPP Control Panel.
4. Iniciar los servicios **Apache** y **MySQL**.
5. Abrir el navegador e ingresar a:

```txt
http://localhost/phpmyadmin/
```

6. Entrar a la opcion **Importar**.
7. Seleccionar el archivo:

```txt
database/vetcare_db.sql
```

8. Presionar **Continuar** para crear la base de datos `vetcare_db`.

## 3. Ejecucion

Con Apache y MySQL activos, abrir en el navegador:

```txt
http://localhost/VetCare_Fernando/
```

Si la carpeta tiene otro nombre, la URL debe ajustarse al nombre de la carpeta.

## 4. Operacion del sistema

### Registro

1. Entrar a la pagina principal.
2. Seleccionar **Registro**.
3. Capturar nombre, correo y contrasena.
4. Presionar **Registrarme**.

### Login

1. Seleccionar **Login**.
2. Ingresar correo y contrasena.
3. Presionar **Entrar**.
4. El sistema muestra el panel de mascotas.

### Crear mascota

1. Presionar **Nueva mascota** o **Agregar mascota**.
2. Capturar nombre, especie, raza, edad, propietario, telefono y estado de salud.
3. Presionar **Guardar**.

### Consultar mascotas

La pantalla `mascotas.php` muestra una tabla con las mascotas registradas y sus datos principales.

### Editar mascota

1. Presionar **Editar** en el registro deseado.
2. Modificar la informacion.
3. Presionar **Actualizar**.

### Eliminar mascota

1. Presionar **Eliminar** en el registro deseado.
2. Confirmar la eliminacion.
3. El sistema actualiza la tabla.

### Cerrar sesion

Presionar **Cerrar sesion** para finalizar el acceso al panel administrativo.

## 5. Prueba basica

Para comprobar el funcionamiento:

1. Abrir `http://localhost/VetCare_Fernando/`.
2. Registrar un usuario.
3. Iniciar sesion.
4. Crear una mascota.
5. Editar la mascota.
6. Eliminar la mascota.
7. Cerrar sesion.

## 6. Archivos principales

- `index.php`: interfaz principal.
- `registro.php`: registro de usuarios.
- `login.php`: inicio de sesion.
- `logout.php`: cierre de sesion.
- `mascotas.php`: listado de mascotas.
- `crear_mascota.php`: creacion de registros.
- `editar_mascota.php`: actualizacion de registros.
- `eliminar_mascota.php`: eliminacion de registros.
- `conexion.php`: conexion a la base de datos.
- `database/vetcare_db.sql`: base de datos del sistema.

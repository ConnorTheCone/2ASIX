# 01

## Comandos DB

Crear base de datos
```
CREATE DATABASE
```
Crear usuario y poner contraseña al usuario
```
CREATE USER 'usuario@direccion' IDENTIFIED BY 'contraseña'
```

Asignar permisos

```
GRANT ALL PRIVILEGES ON 'NombreDB' TO 'usuario@direccion'
```

Mostrar bases de datos

```
SHOW DATABASES
```

Mostrar usuarios

```
SELECT user, host FROM mysql.user
```

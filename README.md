# Práctica 2: Diseño de un Servicio Web REST: Carrito de Compra
**Asignatura:** Programación de Aplicaciones Telemáticas (PAT)
**Autor:** Andrés Guerrero Cabrera

El objetivo de la práctica es el diseño e implementación de un servicio Web REST basado en equest/responde sobre HTTP.
He construido una API mínima para realizar operaciones CRUD (Create, read, update, delete) sobre un carrito de la compra.

## Control de versiones (Git)
Comandos usados: git init, git add ., git commit -m "Initial Commit"

1. **Inicializar el repositorio:** `git init`
2. **Añadir archivos:** `git add .`
3. **Primer commit:** `git commit -m "Initial commit"`

## Spring Boot y Spring Initializr
Para el esqueleto del proyecto, se utilizó Spring Initializr

## El Recurso Carrito
Se ha implementado un modelo de datos para el Carrito, el cual representa una compra en curso

## Operaciones CRUD implementadas

POST: Crear un nuevo carrito,

GET: Consultar la información del carrito o varios carritos,

PUT: Actualizar unidades o descripción,

DELETE: Eliminar un carrito

<img width="1563" height="982" alt="image" src="https://github.com/user-attachments/assets/48c006b4-d727-472c-af13-86bb9671bf05" />

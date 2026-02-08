# Práctica 2: Diseño de un Servicio Web REST: Carrito de Compra
**Asignatura:** Programación de Aplicaciones Telemáticas (PAT)
**Autor:** Andrés Guerrero Cabrera

El objetivo de la práctica es el diseño e implementación de un servicio Web REST basado en equest/responde sobre HTTP.
He construido una API mínima para realizar operaciones CRUD (Create, read, update, delete) sobre un carrito de la compra.

## Control de versiones (Git)
Comandos usados: git init, git add ., git commit -m "Initial Commit"

1. **Inicializar el repositorio:** `git init`
2. **Añadir archivos:** `git add .`
3. **Primer commit:** `git commit -m "Primer commit"`

## Spring Boot y Spring Initializr
Para el esqueleto del proyecto, se utilizó Spring Initializer

## El Recurso Carrito
Se ha implementado un modelo de datos para el Carrito, el cual representa una compra en curso

## Operaciones CRUD implementadas

POST: Crear un nuevo carrito,

GET: Consultar la información del carrito o varios carritos,

PUT: Actualizar unidades o descripción,

DELETE: Eliminar un carrito

## Al inicio podemos ver mediante el request getCarritos que no tenemos ningún carrito creado
<img width="1563" height="982" alt="image" src="https://github.com/user-attachments/assets/48c006b4-d727-472c-af13-86bb9671bf05" />

## En esta instancia creamos dos carritos diferentes con dos productos diferentes
<img width="1574" height="984" alt="image" src="https://github.com/user-attachments/assets/dc3556fe-62bd-4dc3-957e-e08bb4a05464" />
<img width="1589" height="988" alt="image" src="https://github.com/user-attachments/assets/7b5d07f8-40af-4aee-97f7-fa3bf9df0b33" />
<img width="1580" height="988" alt="image" src="https://github.com/user-attachments/assets/c7867a06-7254-4f7c-ac1d-5a048483b9a4" />

## Podemos ver todos los carritos a la vez o solamente uno con getCarrito
<img width="1594" height="993" alt="image" src="https://github.com/user-attachments/assets/050f0312-78f0-4e30-85db-18844700bf13" />

## También lo podemos eliminar...
<img width="1570" height="985" alt="image" src="https://github.com/user-attachments/assets/41876cef-b55c-46e5-96e7-e2f370b59a74" />
<img width="1587" height="990" alt="image" src="https://github.com/user-attachments/assets/a86f1adf-95e5-4ace-a2ea-c39ec17fd6e2" />

## Por último, también podemos modificar un carrito
<img width="1583" height="993" alt="image" src="https://github.com/user-attachments/assets/ba076b59-9915-4b18-875a-f31d5332cbdd" />

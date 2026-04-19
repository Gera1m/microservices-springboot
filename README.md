# Microservicios con Spring Boot

Proyecto de microservicios desarrollado con Spring Boot.

## Servicios

- Products Service (Puerto 8081)
- Orders Service (Puerto 8082)
- Inventory Service (Puerto 8083)

## Tecnologías

- Spring Boot
- MySQL
- PostgreSQL
- Docker
- Postman

## Funcionalidad

- Crear y consultar productos
- Validar stock en inventario
- Generar órdenes solo si hay disponibilidad

## Ejecución

1. Levantar bases de datos:

docker compose up -d

2. Ejecutar los servicios:
- products-service
- inventory-service
- orders-service

## Pruebas

Se realizaron pruebas con Postman para verificar el funcionamiento.

---

Proyecto académico.

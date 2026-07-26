# Laboratorio 1. Aplicación web de catálogo

## Objetivo:

Demostrar que una misma aplicación puede almacenar y mostrar imágenes utilizando Amazon S3, MinIO o Ceph RGW mediante cambios de configuración.

## Flujo:

Usuario
   |
   v
Aplicación web
   |
   v
ObjectStorage
   |
   +------ Amazon S3
   +------ MinIO
   +------ Ceph RGW

## Concepto principal:

Portabilidad de la aplicación.

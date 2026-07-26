# SaaP


## Storage as a Platform: Diseñando aplicaciones cloud-native independientes del almacenamiento.

Diseñando aplicaciones cloud-native independientes del almacenamiento

Este material explora los principales modelos de almacenamiento utilizados en arquitecturas cloud-native y muestra cómo diseñar aplicaciones que puedan trabajar con diferentes proveedores de Object Storage sin acoplar la lógica de negocio a una implementación específica.

El recorrido inicia con los fundamentos de almacenamiento en la nube, profundiza en Object Storage y en la compatibilidad con la API de Amazon S3, y concluye mostrando a Ceph como una plataforma capaz de ofrecer almacenamiento de objetos, bloques y archivos.

El objetivo central es demostrar dos propiedades arquitectónicas:

* Portabilidad: la aplicación puede cambiar de proveedor de almacenamiento sin modificar su lógica de negocio.
* Interoperabilidad: los datos pueden trasladarse entre proveedores compatibles manteniendo su integridad y capacidad operativa.

# Contenido.

# Parte I. Fundamentos.
## 1. Por qué importa el almacenamiento.
## 2. Modelos de almacenamiento..
## 3. Cómo elegir.

# Parte II. Object Storage.
## 4. Fundamentos de Object Storage.
## 5. Amazon S3 como estándar de facto.
## 6. Alternativas compatibles.
## 7. Compatibilidad no significa igualdad.


# Parte III. Diseño de la aplicación.
## 8. Diseñar una capa portable.
## 9. Aplicación de catálogo.
## 10. Cambio de proveedor.


# Parte IV. Interoperabilidad y migración.
## 11. Portabilidad, interoperabilidad y migración.
## 12. Estrategias de migración.
## 13. Migrador JavaFX.
## 14. Riesgos de una migración.

# Parte V. Ceph como plataforma.
## 15. Ceph no es solamente Object Storage.
## 16. Caso Block Storage.
## 17. Caso File Storage.
## 18. Plataforma unificada.

# Parte VI. Conclusiones.
## 19. Lecciones.
## 20. Siguientes pasos.

## Laboratorios.
#### Laboratorio 1. Aplicación web de catálogo.
#### Laboratorio 2. Migrador JavaFX.

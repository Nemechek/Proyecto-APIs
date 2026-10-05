Proyecto de Pruebas de API | QA Manual y Automatización

¡Hola! Mi nombre es Ismael Camargo Sanches.

QA Engineer | API Testing | Quality First | Interfaces QA | Dashboards de Testing | Jira | Postman | Test Case Design & Bugs

## Objetivo

Validar el correcto funcionamiento y la robustez de los endpoints del backend mediante pruebas funcionales y de límites. Esto incluye comprobar que los campos acepten únicamente los formatos válidos (como números específicos), y rechacen entradas incorrectas como letras, combinaciones alfanuméricas, caracteres especiales, cadenas vacías o valores fuera de rango.

## Alcance

El proyecto abarca el análisis y testeo de servicios web utilizando el método POST sobre los siguientes endpoints:

/api/v1/kits/:id/products (Trabajar con los kits)

/order-and-go/v1/delivery (Trabajar con los servicios de entrega)

Las validaciones se realizaron en estricto apego a:

Documentación de la API: Swagger Docs

Requisitos del Negocio: Especificaciones de Backend (PDF)

## Herramientas

Postman: Ejecución y validación de peticiones HTTP / métodos POST.

Jira: Gestión de incidencias, redacción y seguimiento de reportes de errores (bugs).

## Casos Diseñados

1. Módulo: Trabajar con los kits (/api/v1/kits/:id/products)

Se diseñaron e implementaron casos de prueba positivos y negativos aplicando técnicas de Clases de Equivalencia y Valores Límite para:

El parámetro :id en la URL (ID del kit).

Los campos id (ID de los productos).

El campo quantity en el cuerpo de la petición.

La estructura y longitud del array productsList.

El límite total de productos únicos permitidos por kit.

2. Módulo: Trabajar con los servicios de entrega (/order-and-go/v1/delivery)

Se evaluaron escenarios de prueba considerando criterios de aceptación, límites y equivalencias para:

El parámetro deliveryTime (Nota: validado estrictamente contra la columna "Horario" de la tabla de tarifas y precios de envío).

El parámetro productsWeight.

El parámetro productsCount.

## Evidencias

Las colecciones de peticiones y respuestas validadas se encuentran estructuradas y probadas dentro de Postman.

Los reportes de defectos y su ciclo de vida se documentaron detalladamente en Jira.

## Bugs Encontrados

Durante la ejecución de las pruebas, los hallazgos y anomalías se reportaron asegurando los siguientes estándares de calidad:

Uso de títulos únicos y descriptivos en cada reporte de errores para facilitar su identificación rápida por parte del equipo de desarrollo.

Pasos para reproducir claros, resultados esperados vs. resultados obtenidos, y severidad correctamente asignada.

## Conclusiones

Este proyecto fue desarrollado como parte de mi formación en el bootcamp de Tripleten. Ha sido una experiencia enriquecedora donde consolidé competencias técnicas fundamentales en aseguramiento de la calidad de APIs, diseño sistemático de casos de prueba y gestión ágil de incidencias.

Estoy muy entusiasmado por seguir aprendiendo, asumir nuevos retos profesionales y aportar valor en futuros proyectos de tecnología.

## Contacto: Si tienes algún comentario, propuesta o mensaje, no dudes en escribirme a: ismael_camargo1@hotmail.com

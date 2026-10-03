# Proyecto-APIs
Mi nombre es Ismael Camargo Sanches
QA Engineer | API Testing | Quality First | Interfaces QA | dashboards de testing| Jira | Postman | Test case desing and bugs
Presento proyecto elaborado durante el proceso del botcamp Tripleten
este proyecto se realizo durante mi proceso en el botcamp de Tripleten, he aprendido muchisimo y confio en que estas nuevas habilidades me lleven lejos, estoy ancioso por futuros proyetos y ver como avanza mi progreso, mi correo es ismael_camargo1@hotmail.com para cualquier mensage que desen dejarme.

El objetivo de los siguientes proyectos es validar que acepte los limites de cada elemento y que solo acepte números, dejando fuera letras, letras con números, caracteres especiales, varios números juntos y strings vacios.
El metodo utilizado fue el POST y los endpoint fueron: /api/v1/kits/:id/products y /order-and-go/v1/delivery.

Además se validaron los codigos deacuerdo a la Documentacion del URL: https://cnt-a62e2b3c-8fd5-406f-87ef-d10ce34ed9ae.containerhub.tripleten-services.com/docs/ y a los requisitos https://practicum-content.s3.us-west-1.amazonaws.com/new-markets/qa-sprint-4/ESP/V9/Requisitos%20del%20backend_ES.pdf.


Primero se diseñaron las pruebas para "Trabajar con los kits" tomando en cuenta los siguientes criterios:

Cómo agregar productos a un kit.
Los casos positivos, los negativos, las clases de equivalencia y los valores límite para:
El parámetro :id en la URL (ID del kit).
Los campos id (ID de los productos).
El campo quantity en el cuerpo.
La estructura y longitud del array productsList.
El límite total de productos únicos por kit.


Las funciones revisadas y utilizadas para "Trabajar con los servicios de entrega" se tomaron en cuenta los siguientes criterios:

Los casos positivos, los negativos, las clases de equivalencia y los valores límite para el parámetro deliveryTime. > Nota: el valor de deliveryTime debe validarse con la columna “Horario” en la tabla de Requisitos para el cálculo de precios de envío. >
Los casos positivos, los negativos, las clases de equivalencia y los valores límite para el parámetro productsWeight.
Los casos positivos, los negativos, las clases de equivalencia y los valores límite para el parámetro productsCount.


Las pruebas diseñadas fueron probadas utilizando la herramienta de "Postman" y los informes de errores se redactaron utilizando "Jira"

los errores se redactaron tomando en cuenta las siguientes comprobaciónes:
¿Son únicos los títulos de los informes de errores?
¿Coinciden los títulos de los informes de errores con el resultado actual?
¿Incluyen los informes de errores pasos, resultados esperados y actuales, y se ha establecido la prioridad y especificado el entorno?
¿Están duplicados los informes de errores?
¿Se especifica el método HTTP en los encabezados de los informes de errores?

# Mejorar la retención e ingresos de una página web de ventas (S10) | 2025

Contexto: Eres analista en una gran tienda online. Junto con el departamento de marketing hemos recopilado una lista de hipótesis que pueden ayudar a aumentar los ingresos. Tienes que priorizar estas hipótesis, lanzar un test A/B y analizar los resultados.

Parte 1. Priorizar hipótesis El archivo "hypotheses_us.csv" contiene nueve hipótesis sobre cómo aumentar los ingresos de una tienda online con alcance, impacto, confianza y esfuerzo especificados para cada una. Para elegir de la mejor forma de elegir la hipótesis usaremos los métodos RICE y ICE.
Una vez elegida la implementación para hacer a la página haremos una prueba A/B para comparar si funciona mejor la versión existente o con las nuevas incorporaciones.

Parte 2. Análisis del test A/B Realizaste una prueba A/B y obtuviste los resultados descritos en los archivos pedidos_us.csv y visits_us.csv. Posteriormente analizaremos los resultados y haremos conjeturas con ayuda de métodos estadísticos.


*** Descripción de los datasets con los datos: **** Datos utilizados en la primera parte del proyecto

•	/conjuntos de datos/hipótesis_es.csv
Hipótesis: breves descripciones de las hipótesis. Alcance: alcance del usuario, en una escala del uno a diez. Impacto: impacto en los usuarios, en una escala del uno al diez. Confianza: confianza en la hipótesis, en una escala del uno al diez. Esfuerzo: los recursos necesarios para probar una hipótesis, en una escala del uno al diez. Cuanto mayor sea el valor del esfuerzo, más recursos requieren la prueba.


Datos utilizados en la segunda parte del proyecto, ya una vez con la hipótesis seleccionada previamente:
•	/conjuntos de datos/pedidos_us.csv
transactionId: identificador de pedido. visitanteId: identificador del usuario que realizó el pedido. fecha: fecha del pedido. ingresos: ingresos del pedido. grupo: el grupo del test A/B al que pertenece el usuario.
•	/conjuntos de datos/visitas_nosotros.csv
fecha: la fecha. grupo: grupo de la prueba A/B. visitas: el número de visitas en la fecha especificada en el grupo de pruebas A/B especificado.

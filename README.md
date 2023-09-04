# Proyecto_UL
Proyecto sobre aprendizaje no supervisado

# SEGMENTACIÓN DE USUARIOS PARA MEJORA DE EXPERIENCIA EN SITIOS WEB DE COMERCIO ELECTRÓNICO
## Resumen
El comercio electrónico se ha vuelto esencial para las empresas en la era de internet y la globalización, pero comprender y mejorar la retención de clientes en las páginas web es un desafío complejo. Este proyecto busca construir un modelo de clustering no supervisado para segmentar a los usuarios en grupos basados en su comportamiento en el sitio web. El objetivo no es predecir ventas, sino identificar los factores que llevan a los usuarios a abandonar el proceso de compra. Se utilizarán modelos como DBSCAN, K-medias y K-medoides para agrupar a los usuarios y analizar dónde se detienen en el embudo de conversión. Estos grupos servirán como insumo para optimizar estrategias de marketing y retención de clientes, permitiendo a los especialistas del comercio electrónico identificar características clave. Aunque se considera DBSCAN debido a sus ventajas, se realizarán comparaciones con otros métodos de clustering para tomar una decisión informada. El proyecto busca responder a la pregunta de cómo identificar los factores principales que afectan el abandono de usuarios en el proceso de compra y, así, mejorar las estrategias de mercadeo y retención.

## Descripción de los datos. 
Utilizaremos los datos “Online Shoppers Purchasing Intention Dataset”, disponibles en la carpeta Data. <\b>
Estos están compuestos por 12.330 registros y 18 variables. Las variables son las siguientes:
Administrative: Indica el número de páginas de la categoría Administrativa visitadas en la sesión. 
Administrative_Duration: Indica la duración en segundos en páginas Administrativas durante la sesión.
Informational: Indica el número de páginas de la categoría Informativa visitadas en la sesión.
Informational_Duration: Indica la duración en segundos en páginas informativas durante la sesión.
ProductRelated: Indica el número de páginas de la categoría Productos visitadas en la sesión.
ProductRelated_Duration: Indica la duración en segundos en páginas de productos durante la sesión.
BounceRates: Métrica construida por Google Analytics, indica la tasa de rebote de la página visitada (rebote se refiere a que la persona sale de la sesión visitando sólo una página).
ExitRates: Métrica construida por Google Analytics, indica la tasa de salida de la última página visitada..
PageValues: Métrica construida por Google Analytics, indica el valor promedio de la última página visitada (Para que una página tenga valor, se debió presentar una compra alguna sesión).
SpecialDay: Indica que tan cerca estaba la visita con respecto a alguna fecha festiva. 1 indica que la visita fue hecha el mismo día de la festividad, 0 si no se encuentra cerca.
Month: Mes de la visita.
OperatingSystems: Id del sistema operativo.
Browser: Id del browser usado.
Region: Id de la región del usuario realizando la visita. 
TrafficType: Tipo de tráfico.
Visitor_Type: Returning en caso de usuario recurrente, new en caso de usuario nuevo.
Weekend: Indica si la visita fue durante un fin de semana.
Revenue: Indica si se realizó alguna compra durante la visita en cuestión.

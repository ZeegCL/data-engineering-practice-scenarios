Escenarios ingesta por lotes (batch)
====================================

## Escenario #1:

El equipo de BI local le ha solicitado llevar a la nube una base de clientes para una campaña de marketing. La base se ha guardado en archivos Excel, separados por cada tienda de la empresa.Cada archivo pesa aproximadamente 30mb.

Los datos deben estar disponibles en formato CSV para que sean procesados por el software que realiza los envíos y también deben poder cruzarse posteriormente con los registros de ventas para evaluar la efectividad de la campaña. El software de envíos corre en un cluster de Kubernetes en la nube y los registros de ventas se encuentran en una base de datos relacional en la nube.


## Escenario #2:

El equipo de Logística necesita actualizar el estado de inventario de todas las tiendas, el cual se revisa usando un dashboard en Tableau y se alimenta desde una base para analítica en la nube. 

Para esto, cada encargado deja su reporte de inventario en formato CSV en una carpeta compartida en MS OneDrive. Los archivos pesan como máximo 5mb y no se tiene una fecha específica para su actualización.


## Escenario #3:

La universidad donde trabaja ha migrado recientemente a la nube todos sus servicios. Por motivos de seguridad, los sistemas de matrícula están en redes separadas con los sistemas académicos.

Se le ha solicitado actualizar el listado de estudiantes registrados en el sistema LMS (Learning Management System) en base a las nuevas matrículas, de forma diaria. Debe considerar que dicho sistema sólo recibe datos mediante llamadas autenticadas a su API Rest.

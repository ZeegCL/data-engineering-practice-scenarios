Escenarios ingesta por streaming
================================

## Escenario #1:

La sociedad agrícola para la cual trabaja ha decidido realizar un seguimiento en tiempo real del suelo en el cual se cultivan los vegetales, mediante la implementación de postes con sensores para humedad, temperatura y pH.

La instalación y configuración de los componentes se realizará con una empresa externa, la cual pondrá a disposición un servidor intermediario en el cual se almacenarán los datos por 1 semana usando Apache Kafka. Se le ha solicitado diseñar una solución que permita leer los datos, limpiarlos y posteriormente mostrarlos en un dashboard sencillo. Debe considerar que es posible que los postes pierdan conexión con el servidor central y que estos están diseñados para almacenar datos localmente por hasta 1 día.

# quiz-2-analisis-sistemass

## Texto de lectura

La tienda tiene la intención de implementar un programa de fidelización mensual mediante el cual premiará a tres clientes destacados, con la particularidad de que estos premios serán otorgados de manera recurrente, es decir, cada mes se llevará a cabo una nueva selección de ganadores. Es fundamental mantener un registro detallado de todos los premios entregados, así como de los clientes agraciados en cada ocasión. El proceso de selección de los ganadores se basa en la acumulación de puntos por parte de los clientes. Cada cliente acumula puntos mediante la realización de compras, con un sistema de bonificación especial para productos seleccionados. Los clientes también pueden obtener puntos mediante acciones adicionales, como recomendar la tienda a amigos o completar encuestas de satisfacción. Una vez que un cliente acumula una cantidad determinada de puntos, se le asigna automáticamente una entrada para el sorteo mensual. El número de entradas asignadas a cada cliente varía según la cantidad de puntos acumulados, lo que permite una distribución equitativa de oportunidades entre todos los participantes. El sorteo se lleva a cabo utilizando todas las entradas acumuladas por los clientes durante el mes, garantizando así la imparcialidad y transparencia en el proceso de selección de los ganadores. Además, se establece un registro histórico completo de todos los premios entregados y los respectivos clientes agraciados, lo que facilita un seguimiento preciso y sistemático de cada sorteo realizado por la tienda. Este registro también proporciona información valiosa para futuras promociones y estrategias de fidelización de clientes. 

## 1. Entradas de Datos:
   
   ### Información del Cliente:

- Nombre del cliente.
- ID del cliente.
- Datos de contacto (correo electrónico, teléfono, etc.).
- Registro de Compras:

   ### Fecha de la compra:
  
- Detalles del producto (nombre, ID, categoría).
- Monto gastado.
- Puntos obtenidos por la compra.
  
   ### Acciones Adicionales:

- Referencias de nuevos clientes.
- Encuestas completadas (ID de la encuesta, fecha de finalización).
- 
   ### Puntos Acumulados:

- Total de puntos acumulados por cada cliente.
- Detalle de puntos obtenidos por cada acción (compras, referencias, encuestas).

   ### Entradas al Sorteo:

- Número de entradas asignadas a cada cliente para el sorteo mensual.
- ID del sorteo.
  
## 2. Salidas de Datos:

   ### Ganadores del Sorteo:

- Lista de clientes ganadores del sorteo mensual.
- Cantidad de entradas utilizadas por cada ganador.
- Fecha del sorteo.
- Premio asignado a cada ganador.
  
   ### Registro Histórico:

- Historial de premios entregados.
- Registro de clientes ganadores por cada mes.
- Fecha y detalles de cada sorteo.
  
   ### Informe de Fidelización:

- Resumen mensual de clientes destacados.
- Estadísticas de puntos acumulados por los clientes.
- Informes de acciones de fidelización efectivas.
  
   ### Datos para Promociones Futuras:

- Análisis de clientes más activos.
- Segmentación de clientes según puntos acumulados.
- Sugerencias de productos y promociones basadas en el historial de compras y puntos.

## 1. Gestión de Clientes:

- Registro de Clientes: El sistema debe permitir el registro de nuevos clientes, capturando su nombre, ID, y datos de contacto.
- Actualización de Información del Cliente: El sistema debe permitir la actualización de los datos personales y de contacto de los clientes.
  
## 2. Acumulación de Puntos:

- Registro de Compras: El sistema debe registrar cada compra realizada por un cliente, incluyendo detalles como el producto, monto gastado, y fecha.
- Cálculo de Puntos por Compra: El sistema debe calcular y asignar puntos a los clientes basados en el monto gastado y cualquier bonificación aplicable.
- Acumulación de Puntos por Acciones Adicionales: El sistema debe asignar puntos a los clientes por completar acciones adicionales, como referir amigos o completar encuestas.
  
## 3. Gestión de Sorteos Mensuales: 

- Generación de Entradas para el Sorteo: El sistema debe generar y asignar entradas para el sorteo mensual a los clientes basándose en la cantidad de puntos acumulados.
- Realización del Sorteo: El sistema debe llevar a cabo un sorteo mensual utilizando todas las entradas acumuladas, asegurando la selección aleatoria de tres ganadores.
- Notificación a Ganadores: El sistema debe notificar a los ganadores del sorteo a través de su correo electrónico o teléfono.
  
## 4. Registro y Seguimiento de Premios:

- Registro de Premios Otorgados: El sistema debe mantener un registro de todos los premios entregados, incluyendo el nombre del cliente ganador, el premio, y la fecha de entrega.
- Histórico de Sorteos: El sistema debe almacenar un historial completo de todos los sorteos realizados, incluyendo la lista de ganadores y los premios otorgados.
  
## 5. Generación de Informes:

- Informe de Fidelización Mensual: El sistema debe generar informes mensuales que incluyan un resumen de los puntos acumulados por los clientes y las estadísticas de participación en los sorteos.
- Informe de Clientes Destacados: El sistema debe generar un informe de los clientes más activos o destacados del mes, basado en la acumulación de puntos.
- Informe para Estrategias Futuras: El sistema debe proporcionar datos y análisis para futuras promociones, basados en el comportamiento de compra y la acumulación de puntos de los clientes.

## 6. Seguridad y Accesibilidad:

- Control de Acceso: El sistema debe implementar un control de acceso basado en roles para proteger la información sensible de los clientes y del sorteo.
- Respaldo de Datos: El sistema debe contar con un mecanismo de respaldo regular de todos los datos almacenados, incluyendo información de clientes, puntos acumulados, y registros de sorteos.

# •	¿Cómo podríamos diseñar una contrapropuesta para optimizar el programa de f idelización y la selección de ganadores?

## -R// Para optimizar el programa de fidelización y la selección de ganadores, se puede implementar un sistema de niveles donde los clientes suben de categoría tales como bronce, plata y oro, según los puntos acumulados, dando beneficios en niveles superiores. Además, se podría realizar un sorteo ponderado, donde los clientes con más puntos tengan más posibilidades de ganar, pero sin excluir a los de niveles bajos. También, se puede ofrecer premios adicionales pensando en metas de participación, como sorteos especiales para clientes que refieren a otros o completan encuestas.  

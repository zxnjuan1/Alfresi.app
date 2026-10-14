## Product Backlog

El product backlog de **Alfresi.app** es la lista priorizada de las funcionalidades que necesita la plataforma, escritas como historias de usuario. Nos indica qué construir primero para que las productoras de fresas de Guasca vendan directo a sus clientes, sin intermediarios, y controlen mejor su cultivo.

Es una lista viva: se ajusta a medida que avanza el proyecto y aprendemos de las productoras y los clientes.

### Historias de usuario

- **HU-01: Registro de datos del cultivo.** Como productor de fresas hidropónicas en Guasca, quiero registrar y consultar los datos de temperatura, pH y concentración de nutrientes de la solución nutritiva, para conocer las condiciones del cultivo y facilitar el control de la dosificación de nutrientes.
  - El sistema permite registrar los datos de cada medición.
  - Cada registro incluye la fecha y hora.
  - Los datos pueden consultarse para revisar las condiciones del cultivo.

- **HU-02: Gestión de pedidos.** Como productora de fresas de Guasca, quiero recibir y organizar todos mis pedidos en un solo lugar, para vender directo sin intermediarios, evitar errores y ganar más por cada venta.
  - Los pedidos aparecen en una lista con los datos del cliente y las cantidades solicitadas.
  - Se puede actualizar el estado de cada pedido: recibido, en preparación o entregado.
  - Se pueden modificar los precios y la disponibilidad de los productos según la cosecha.

- **HU-03: Catálogo de productos para los clientes.** Como cliente interesado en fresas orgánicas, quiero ver un catálogo en línea con fotos, precios y disponibilidad, para elegir y pedir mis fresas a cualquier hora, sabiendo de dónde vienen.
  - El catálogo muestra foto, precio y disponibilidad de cada producto.
  - Se puede consultar desde el celular.
  - Muestra información sobre el origen de las fresas.
  - Permite contactar directamente a la productora para solicitar los productos.

# Cómo leer el backlog

- Cada historia tiene un **ID**, una descripción desde el punto de vista del usuario y sus **criterios de aceptación**, que indican cuándo se considera terminada.
- Las tres historias son de prioridad alta, porque son las funciones mínimas para que la plataforma sea útil.
- Cada historia tiene una **estimación de esfuerzo en puntos**: 5 para HU-01, 8 para HU-02 y 5 para HU-03. Son valores iniciales que el equipo ajusta durante la planificación.
- Cada historia tiene un **estado**: Pendiente, En desarrollo o Hecho.

El detalle completo está en `Product_Backlog_Alfresi_Sprints.xlsx`.


SPRINTS:

Sprint 1. Diseño y estructura inicial del sistema:
Se definirá la estructura de la aplicación, el diseño de las pantallas principales y la organización de la base de datos para almacenar la información del cultivo, los productos y los pedidos.

Sprint 2. Registro y consulta de datos del cultivo:
Se desarrollará la funcionalidad para registrar y consultar las mediciones de temperatura, pH y concentración de nutrientes, incluyendo la fecha y hora de cada registro.

Sprint 3. Catálogo de productos:
Se desarrollará un catálogo en línea que permita a los clientes consultar las fotografías, los precios, la disponibilidad y la procedencia de las fresas, además de contar con una opción de contacto directo con la productora.

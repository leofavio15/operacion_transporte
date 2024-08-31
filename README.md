# operacion_transporte
base de datos para gestion de operacion de transporte

# Caso Práctico: Gestión de Logística y Transporte
## Contexto: 
Una empresa de logística y transporte gestiona el envío de mercancías desde múltiples almacenes a varios destinos. La empresa desea un sistema para optimizar y rastrear el movimiento de mercancías, el uso de vehículos y el desempeño de los conductores.

# Requerimientos del Sistema:

## Almacenes:
La empresa tiene varios almacenes ubicados en diferentes ciudades. Cada almacén tiene un código único, nombre, dirección y capacidad de almacenamiento.

## Productos:
Los productos almacenados tienen un código único, nombre, descripción, peso y dimensiones. Un producto puede estar almacenado en diferentes almacenes, pero la cantidad disponible en cada almacén debe ser registrada.

## Vehículos:
La empresa utiliza diferentes tipos de vehículos (camiones, furgonetas, etc.). Cada vehículo tiene un número de registro único, tipo, capacidad máxima de carga, y se le asigna un conductor específico.

## Conductores:
Cada conductor tiene un identificador único, nombre, número de licencia, y se le asigna uno o más vehículos. También se debe llevar un registro de los viajes realizados por cada conductor.

## Rutas:
Las rutas representan el camino desde un almacén hasta un destino final. Cada ruta tiene un identificador único, punto de origen (almacén), destino (dirección), distancia, y tiempo estimado de viaje.

## Órdenes de Envío:
Los clientes realizan órdenes de envío de productos desde un almacén a un destino. Cada orden tiene un número único, fecha de emisión, fecha de entrega estimada, y puede incluir varios productos. También se registra el almacén de origen y la dirección de destino.

## Asignación de Envíos:
Cada orden de envío es asignada a un vehículo específico y un conductor. Es necesario registrar el vehículo utilizado, el conductor asignado, y la fecha y hora de salida.

## Rastreo de Envíos:
Se debe poder rastrear el estado de las órdenes de envío (en proceso, en tránsito, entregado, etc.), así como registrar cualquier incidencia durante el transporte (retrasos, accidentes, etc.).

## Desafíos:
Diseña un modelo de datos que soporte todas las operaciones mencionadas, asegurando la integridad de los datos y evitando redundancias.
Considera las relaciones entre las tablas para garantizar que el sistema pueda rastrear eficazmente la ubicación de los productos, el uso de vehículos, y el desempeño de los conductores.
Asegúrate de que el modelo permita consultas eficientes para obtener reportes sobre el estado de los envíos, disponibilidad de productos en los almacenes, y el historial de viajes de los conductores.

## Objetivo:
Crear un diagrama entidad-relación (ERD) para representar el modelo de datos relacional que soporte el sistema de gestión de logística y transporte de la empresa.

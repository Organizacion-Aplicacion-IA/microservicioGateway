# microservice-gateway

El microservicio `microservice-gateway` es un servicio basado en Spring Boot que actúa como puerta de enlace (API Gateway) para gestionar las solicitudes entrantes a los diversos microservicios de un sistema distribuido. Su principal objetivo es enrutar y dirigir el tráfico de solicitudes hacia los microservicios correspondientes, facilitando la seguridad, el balanceo de carga, la monitorización y el manejo de errores de manera centralizada.

## Tabla de contenido
1. [Descripción General](#descripción-general)
2. [Requisitos de Tecnologías](#requisitos-de-tecnologías)
3. [Configuración](#configuración)

## Descripción General

El microservicio `microservice-gateway` está diseñado para funcionar como un punto de entrada único a un sistema compuesto por múltiples microservicios. Los principales beneficios de usar un API Gateway incluyen:

- **Ruteo de solicitudes**: Dirige las solicitudes de los clientes a los microservicios adecuados.
- **Seguridad**: Gestiona la autenticación y autorización de las solicitudes.
- **Balanceo de carga**: Distribuye las solicitudes entrantes entre los diferentes instancias de microservicios.

El microservicio está construido con Spring Boot y se integra con otras tecnologías como Spring Cloud para implementar características como el descubrimiento de servicios y la gestión del enrutamiento dinámico de solicitudes.

## Requisitos de Tecnologías

Para ejecutar este microservicio, necesitas tener configurado lo siguiente:

### Dependencias:
- **Java 21**: Asegúrate de tener instalada una versión compatible de Java.
- **Spring Boot 3.4**: Framework principal para construir la aplicación.
- **Spring Cloud Gateway**: Para gestionar el enrutamiento y las funcionalidades de API Gateway.
- **Eureka (opcional)**: Si se desea implementar descubrimiento de servicios.
- **Maven**: Para la gestión de dependencias y construcción del proyecto.

### Herramientas y Servicios:
- **Base de datos**: MySQL(Un volcado de la base de datos previo)
- **Servicios de infraestructura**: asegúrate de tenerlos los microsevicios que enruta en ejecución.

## Configuración

A continuación se detallan los pasos para configurar el entorno de desarrollo:

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/Organizacion-Aplicacion-IA/microservicioGateway.git

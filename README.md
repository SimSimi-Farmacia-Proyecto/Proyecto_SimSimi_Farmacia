Plataforma de Gestión Farmacéutica - SimSimi
📋 Descripción del Proyecto
SimSimi es una solución integral para la gestión de ventas, inventario y validación de recetas médicas. Diseñada bajo una arquitectura de microservicios, permite escalar de forma independiente cada módulo del negocio, garantizando la trazabilidad de medicamentos controlados y la eficiencia en el proceso de venta.

🏗️ Arquitectura del Sistema
El sistema se basa en un ecosistema de 10 microservicios desacoplados que se comunican mediante WebClient y se gestionan a través de un API Gateway.

Componentes de Infraestructura:
Service Discovery: Eureka Server para el registro dinámico.
API Gateway: Spring Cloud Gateway como punto de entrada único.
Persistencia: Database per Service (MySQL para cada módulo).

Listado de Microservicios:
ms-usuarios: Gestión de acceso y seguridad (RBAC).
ms-clientes: Registro y perfiles de pacientes.
ms-medicamentos: Catálogo técnico de fármacos.
ms-inventario: Control de stock y movimientos de bodega.
ms-recetas: Validación de prescripciones médicas.
ms-ventas: Orquestador de transacciones.
ms-detalle-venta: Desglose de productos por transacción.
ms-pagos: Integración y validación de cobros.
ms-notificaciones: Alertas vía email/push al cliente.
ms-reportes: Consolidado de métricas operativas.

👥 Equipo de Desarrollo
Integrante 1 - Dylan Arenas
Integrante 2 - Alexandra Menares

# Resumen: Identificación de Sistemas ERP-CRM

## 1. Introducción a la gestión empresarial

La administración es la ciencia social que estudia las organizaciones y se encarga de la planificación, organización, dirección y control de recursos (humanos, financieros, materiales, tecnológicos) para obtener máximo beneficio.

### Características principales de la administración:
- **Universalidad**: Se aplica en cualquier organismo social
- **Especificidad**: Tiene características propias que la diferencian de otras disciplinas
- **Unidad temporal**: Todos los elementos administrativos se dan simultáneamente
- **Unidad jerárquica**: Todos los niveles directivos participan en la administración
- **Valor instrumental**: Es un medio para conseguir objetivos
- **Amplitud de ejercicio**: Se aplica en todos los niveles organizacionales
- **Interdisciplinariedad**: Se relaciona con múltiples disciplinas
- **Flexibilidad**: Se adapta a diferentes necesidades empresariales

## 2. Evolución de la Informática de gestión empresarial

Los Sistemas de Información (SI) varían según el campo de aplicación:
- En **informática**: sistemas interconectados para obtener, almacenar y manipular datos
- En **teoría de sistemas**: sistemas automatizados o manuales que procesan información

### Tipos de Sistemas de Información:
- **TPS** (Transaction Processing Systems): Gestión de transacciones
- **MIS** (Management Information Systems): Solución de problemas empresariales
- **DSS** (Decision Support Systems): Apoyo a la toma de decisiones
- **EIS** (Executive Information Systems): Información para nivel gerencial
- **OAS** (Office Automation Systems): Automatización de oficinas
- **SE** (Expert Systems): Emulan comportamiento experto
- **ERP** (Enterprise Resource Planning): Integran información y procesos

### Evolución histórica:
- **Años 60**: Primeros SI, aplicaciones contables, gestión de stock (ICS)
- **Años 70**: Aparición del MRP (Material Requirements Planning)
- **Años 80**: PC y MRP II con gestión de producción y distribución
- **Años 90**: ERP completos con modelo cliente-servidor
- **2000**: ERP II con CRM integrado
- **Actualidad**: Mayor funcionalidad y adaptación específica por sectores

## 3. Organización de una empresa y sus relaciones

### Macroentorno (factores globales):
- Factores tecnológicos, jurídicos, demográficos, socioculturales y económicos

### Microentorno (factores específicos):
- Proveedores, clientes, intermediarios y competidores

## 4. Concepto de ERP (Sistemas de planificación de recursos empresariales)

Sistema integral que soporta los procesos de negocio de una empresa, permitiendo operaciones como órdenes de compra, facturación, administración de inventario, etc.

### Características distintivas:
- **Integrales**: Controlan procesos interrelacionados de todos los departamentos
- **Modulares**: Funcionalidad dividida en módulos instalables según necesidades
- **Adaptables**: Se configuran según la idiosincrasia de cada empresa

### Beneficios:
- Unificación de procesos
- Información fiable y oportuna
- Eliminación de datos innecesarios
- Reducción de costes y tiempos
- Compartición de información organizacional

### Gestión actual de ERP:
- Comercio electrónico, CRM, SCM, SRM
- Business Intelligence (BI), Knowledge Management (KM)
- Partner Relationship Management (PRM)
- Product Lifecycle Management (PLM)

### Principales proveedores:

#### SAP Business Suite:
- Plataforma NetWeaver
- Áreas: Finanzas, fabricación, aprovisionamiento, desarrollo de productos, marketing, ventas, RRHH

#### Oracle:
- JD Edwards Enterprise One
- Aplicaciones ERP independientes de plataforma

#### Microsoft Dynamics:
- Dynamics AX, GP, NAV, SL
- Orientado a medianas empresas

#### OpenBravo:
- ERP web basado en código abierto
- Licencia Mozilla Public License
- Arquitectura Java con modelos MVC

#### Odoo (anteriormente OpenERP):
- Sistema ERP integrado de código abierto
- Alternativa a SAP y Microsoft Dynamics
- Licencia AGPL, sin coste de licencias

## 5. Concepto de CRM (Gestión de relaciones con clientes)

Sistema que apoya la gestión de relaciones con clientes, ventas y marketing. Incorpora mecanismos para establecer relaciones satisfactorias y duraderas.

### Componentes:
- **Lógica operacional**: Realización de tareas
- **Lógica analítica**: Análisis de información existente

### Funcionalidades:
- Gestión de contactos y redes comerciales
- Asignación de tareas
- Envío de boletines promocionales
- Gestión de eventos

## 6. Arquitectura de un sistema ERP-CRM

### Ejemplo: Arquitectura Odoo
**Tecnologías**: Python, SQL/PL-SQL, XML
**Arquitectura**: MVC con PostgreSQL

#### Componentes principales:
- **Capa ORM**: Mapeo entre objetos Python y base de datos PostgreSQL
- **Arquitectura MVC**: Modelo (datos Python), Vista (formularios XML), Controlador (lógica de negocio)
- **Tenencia Múltiple**: Base de datos común para todos los clientes
- **Sistema de workflows**
- **Diseñadores de informes**
- **Facilidades de traducción**

#### Comunicación:
- Servidor-Cliente: XML-RPC
- Cliente web: JSON-RPC
- Acceso mediante servicios WSGI

## 7. Tipos de licencias

### Software libre vs. Software privativo:
- **Software libre**: Respeta la libertad total del usuario
- **Software privativo**: Software que no es libre

### Ventajas del software libre en ERP:
- Software y actualizaciones gratuitas
- Gran cantidad de información accesible
- Múltiples opciones: Openbravo, Odoo

### Modelos de mantenimiento:
- **Privativo**: Licencias, implantación, actualizaciones contractuales
- **Libre**: Mantenimiento por horas o usuario, sin garantías formales

## 8. Tipos de instalación

### ERP estándar vs. ERP a medida:
- **Estándar**: Soluciones predeterminadas para implementación rápida
- **A medida**: Desarrollo específico para necesidades particulares

### ERP local vs. ERP en la nube:
- **Local**: Control total, inversión en infraestructura
- **Nube**: Menor inversión inicial, mayor escalabilidad

### Modalidades de instalación Odoo:
- Máquina virtual (evaluación)
- Paquetes en entorno gráfico
- Instalación personalizada desde código fuente
- Acceso en línea (SaaS)

### Modelos de trabajo:
- **Monopuesto**: Todo en un equipo (localhost)
- **Cliente/Servidor**: Separación de funciones y datos

## 9. Módulos de un sistema ERP

### Clasificación:
- **Módulos base**: Se cargan automáticamente en la instalación
- **Módulos adicionales**: Se instalan posteriormente según necesidades

### Características de los módulos:
- Instalación/desinstalación mediante asistentes
- Configuración y parametrización
- Generación de informes específicos
- Niveles de seguridad diferenciados
- Interconexión entre módulos
- Adaptación de menús por usuario

### Módulos principales:

#### Módulo Base:
- Configuración de aplicación
- Gestión de datos maestros
- Establecimiento de idioma
- Seguridad y gestión de usuarios
- Administración de módulos

#### Gestión contable y financiera:
- Contabilidad general y analítica
- Gestión de impuestos
- Presupuestos
- Facturas de clientes y proveedores
- Extractos bancarios
- Informes contables

#### Compras, ventas y almacén:
**Compras**: Solicitudes de presupuestos, pedidos, seguimiento de tarifas
**Ventas**: Pedidos, confirmación de envío, formas de pago, albaranes
**Almacén**: Múltiples almacenes, gestión de stock, traspasos, codificación de productos

#### Facturación:
- Configuración de formas de pago/cobro
- Facturas automáticas
- Generación de efectos
- Gestión de recibos y transferencias
- Importación de extractos bancarios

#### Gestión de personal:
- Planificación y nóminas
- Gestión de empleados y vacaciones
- Contratos y beneficios
- Control de ausencias
- Gestión de rendimiento
- Perfiles y responsabilidades

#### Gestión de relaciones con clientes (CRM):
- Datos identificativos de contactos
- Segmentación de clientes
- Gestión de llamadas y reuniones
- Campañas de marketing
- Seguimiento comercial
- Herramientas de productividad
- Estadísticas diversas
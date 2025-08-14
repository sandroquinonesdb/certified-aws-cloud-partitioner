# Guía de Servicios AWS - Certificación Cloud Practitioner

Esta guía contiene los servicios AWS esenciales para la certificación AWS Cloud Practitioner, organizados por categorías.

## 🤖 Servicios de Inteligencia Artificial y Machine Learning

### Amazon Macie  
**¿Para qué sirve?** Servicio de seguridad que utiliza machine learning para descubrir, clasificar y proteger datos confidenciales almacenados en Amazon S3. Detecta automáticamente información sensible como PII, credenciales, números de tarjeta y más, generando alertas y reportes accionables.  
- **Casos de uso:** Detección de datos sensibles en S3, cumplimiento normativo (GDPR, HIPAA), auditoría de buckets públicos, protección de datos durante migraciones.  
 Solo analiza datos almacenados en Amazon S3.  

### Amazon Rekognition

**¿Para qué sirve?** Servicio de análisis de imágenes y videos que utiliza machine learning para identificar objetos, personas, texto, escenas y actividades. También puede detectar contenido inapropiado.

- **Casos de uso:** Moderación de contenido, análisis facial, reconocimiento de celebridades, análisis de sentimientos en imágenes.

### Amazon Transcribe

**¿Para qué sirve?** Convierte automáticamente el habla en texto utilizando tecnología de reconocimiento de voz automático (ASR).

- **Casos de uso:** Transcripción de llamadas, subtítulos para videos, análisis de conversaciones de call centers.

### Amazon Polly

**¿Para qué sirve?** Convierte texto en habla realista utilizando tecnología de síntesis de voz avanzada.

- **Casos de uso:** Aplicaciones de lectura, asistentes de voz, contenido de audio para e-learning.

### Amazon Translate

**¿Para qué sirve?** Servicio de traducción automática neuronal que proporciona traducciones rápidas, de alta calidad y asequibles.

- **Casos de uso:** Localización de sitios web, traducción de documentos, comunicación multiidioma.

### Amazon Lex

**¿Para qué sirve?** Servicio para construir interfaces de conversación (chatbots) utilizando voz y texto.

- **Casos de uso:** Chatbots de atención al cliente, asistentes virtuales, interfaces de voz para aplicaciones.

### Amazon Comprehend

**¿Para qué sirve?** Servicio de procesamiento de lenguaje natural (NLP) que utiliza machine learning para encontrar insights y relaciones en texto.

- **Casos de uso:** Análisis de sentimientos, extracción de entidades, clasificación de documentos.

### Amazon SageMaker

**¿Para qué sirve?** Plataforma completamente administrada para construir, entrenar y desplegar modelos de machine learning a escala.

- **Casos de uso:** Desarrollo de modelos ML personalizados, experimentación, despliegue de modelos en producción.

### Amazon Forecast

**¿Para qué sirve?** Servicio de pronósticos basado en machine learning que utiliza los mismos algoritmos que Amazon.

- **Casos de uso:** Pronósticos de demanda, planificación financiera, predicción de inventario.

### Amazon Kendra

**¿Para qué sirve?** Servicio de búsqueda empresarial inteligente impulsado por machine learning.

- **Casos de uso:** Búsqueda en documentos corporativos, bases de conocimiento, portales de autoservicio.

### Amazon Personalize

**¿Para qué sirve?** Servicio de recomendaciones en tiempo real basado en machine learning.

- **Casos de uso:** Recomendaciones de productos, personalización de contenido, marketing dirigido.

### Amazon Textract

**¿Para qué sirve?** Extrae automáticamente texto, escritura a mano y datos de documentos escaneados.

- **Casos de uso:** Procesamiento de formularios, digitalización de documentos, extracción de datos de facturas.

## 🏢 Servicios de Gestión y Gobernanza

### AWS Organizations

**¿Para qué sirve?** Servicio de gestión de cuentas que permite administrar múltiples cuentas de AWS de forma centralizada.

- **Casos de uso:** Gestión de múltiples cuentas, aplicación de políticas, facturación consolidada.

### AWS Control Tower

**¿Para qué sirve?** Proporciona la forma más fácil de configurar y gobernar un entorno multi-cuenta de AWS seguro.

- **Casos de uso:** Configuración inicial de multi-cuenta, aplicación de mejores prácticas, monitoreo de compliance.

### AWS Resource Access Manager (RAM)

**¿Para qué sirve?** Permite compartir recursos de AWS de forma segura entre cuentas o dentro de una organización.

- **Casos de uso:** Compartir subnets, imágenes AMI, licencias entre cuentas.

### AWS Service Catalog

**¿Para qué sirve?** Permite a las organizaciones crear y gestionar catálogos de productos de TI aprobados para uso en AWS.

- **Casos de uso:** Estandarización de despliegues, autoservicio para desarrolladores, control de costos.

## 💰 Modelos de Precios y Gestión de Costos

### Modelos de Precios en AWS

**¿Para qué sirve?** AWS ofrece varios modelos de precios para optimizar costos:

- **Pay-as-you-go:** Paga solo por lo que usas
- **Save when you commit:** Descuentos por comprometerse a usar recursos
- **Pay less by using more:** Descuentos por volumen
- **Casos de uso:** Optimización de costos según patrones de uso.

### AWS Savings Plans

**¿Para qué sirve?** Modelo de precios flexible que ofrece precios bajos a cambio de un compromiso de uso consistente.

- **Casos de uso:** Reducir costos de EC2, Lambda y Fargate hasta un 72%.

### AWS Compute Optimizer

**¿Para qué sirve?** Recomienda recursos óptimos de AWS para reducir costos y mejorar el rendimiento.

- **Casos de uso:** Optimización de instancias EC2, volúmenes EBS, funciones Lambda.

### Facturación y Costos en AWS

**¿Para qué sirve?** Herramientas para gestionar y entender los costos de AWS:

- **AWS Billing Dashboard:** Vista general de costos
- **AWS Cost Explorer:** Análisis detallado de costos
- **Casos de uso:** Monitoreo de gastos, análisis de tendencias.

### Estimación de Costos

**¿Para qué sirve?** Herramientas para estimar costos antes del despliegue:

- **AWS Pricing Calculator:** Estimaciones detalladas
- **AWS Simple Monthly Calculator:** Cálculos básicos
- **Casos de uso:** Planificación presupuestaria, comparación de arquitecturas.

### Seguimiento y Monitoreo de Costos

**¿Para qué sirve?** Herramientas para monitorear gastos en tiempo real:

- **AWS Budgets:** Alertas de presupuesto
- **AWS Cost and Usage Reports:** Reportes detallados
- **Casos de uso:** Control presupuestario, alertas de sobrecostos.

### AWS Cost Anomaly Detection

**¿Para qué sirve?** Detecta automáticamente gastos inusuales utilizando machine learning.

- **Casos de uso:** Identificación temprana de sobrecostos, alertas automáticas.

## 🛠️ Servicios de Soporte y Monitoreo

### AWS Service Quotas

**¿Para qué sirve?** Gestiona y monitorea los límites de servicio (cuotas) en tu cuenta de AWS.

- **Casos de uso:** Solicitar aumentos de límites, monitorear uso de cuotas.

### AWS Trusted Advisor

**¿Para qué sirve?** Proporciona recomendaciones en tiempo real para optimizar recursos de AWS.

- **Categorías:** Optimización de costos, rendimiento, seguridad, tolerancia a fallos, límites de servicio.
- **Casos de uso:** Auditorías de seguridad, optimización de costos, mejores prácticas.

### Tipos de Soporte en AWS

**¿Para qué sirve?** AWS ofrece diferentes niveles de soporte:

- **Basic:** Gratuito, acceso a documentación
- **Developer:** Soporte técnico durante horario laboral
- **Business:** Soporte 24/7, acceso a Trusted Advisor, AWS Support Api
- **Enterprise:** Soporte 24/7, Soporte dedicado, Technical Account Manager, AWS Support Api, concierne support team, funciones de gestion de eventos de infraestructura

## 💻 Servicios de Escritorio Virtual y Streaming

### Amazon WorkSpaces

**¿Para qué sirve?** Servicio de escritorio virtual completamente administrado que se ejecuta en la nube de AWS.

- **Casos de uso:** Trabajo remoto, escritorios virtuales para empleados, acceso seguro a aplicaciones corporativas.

### Amazon AppStream 2.0

**¿Para qué sirve?** Servicio de streaming de aplicaciones completamente administrado que permite transmitir aplicaciones de escritorio.

- **Casos de uso:** Streaming de aplicaciones especializadas, acceso remoto a software, distribución de aplicaciones.

## 🌐 Internet of Things (IoT)

### AWS IoT Core

**¿Para qué sirve?** Plataforma en la nube administrada que permite a dispositivos conectados interactuar de forma fácil y segura con aplicaciones en la nube.

- **Casos de uso:** Conectividad de dispositivos IoT, procesamiento de datos de sensores, automatización industrial.

## 🎥 Servicios de Media y Contenido

### Amazon Elastic Transcoder

**¿Para qué sirve?** Servicio de transcodificación de medios en la nube para convertir archivos multimedia a formatos optimizados.

- **Casos de uso:** Conversión de videos para diferentes dispositivos, optimización de contenido multimedia.

## 🔗 Servicios de Desarrollo de Aplicaciones

### AWS AppSync

**¿Para qué sirve?** Servicio administrado que facilita el desarrollo de APIs GraphQL para aplicaciones.

- **Casos de uso:** APIs en tiempo real, sincronización de datos offline, aplicaciones móviles y web.

### AWS Amplify

**¿Para qué sirve?** Plataforma de desarrollo que permite construir y desplegar aplicaciones web y móviles full-stack.

- **Casos de uso:** Desarrollo rápido de aplicaciones, hosting de sitios web estáticos, autenticación de usuarios.

### AWS Application Composer

**¿Para qué sirve?** Herramienta visual para diseñar y construir aplicaciones serverless utilizando un editor de arrastrar y soltar.

- **Casos de uso:** Prototipado rápido, diseño de arquitecturas serverless, visualización de aplicaciones.

### AWS Device Farm

**¿Para qué sirve?** Servicio de pruebas de aplicaciones que permite probar aplicaciones móviles en dispositivos reales.

- **Casos de uso:** Pruebas automatizadas de apps móviles, testing en múltiples dispositivos, QA de aplicaciones.

## 💾 Servicios de Backup y Recuperación

### AWS Backup

**¿Para qué sirve?** Servicio completamente administrado que centraliza y automatiza la protección de datos en servicios de AWS.

- **Casos de uso:** Backup automatizado, políticas de retención, recuperación de datos.

### Disaster Recovery

**¿Para qué sirve?** Estrategias y servicios para recuperación ante desastres:

- **Pilot Light:** Infraestructura mínima siempre activa
- **Warm Standby:** Versión escalada de pilot light
- **Multi-Site:** Infraestructura completa en múltiples sitios
- **Casos de uso:** Continuidad del negocio, recuperación rápida ante fallos.

### AWS DataSync

**¿Para qué sirve?** Servicio de transferencia de datos que facilita mover grandes cantidades de datos hacia y desde AWS.

- **Casos de uso:** Migración de datos, sincronización de archivos, backup híbrido.

## 🚚 Servicios de Migración

### Servicios de Migración

**¿Para qué sirve?** AWS ofrece múltiples servicios para migrar aplicaciones y datos:

- **AWS Migration Hub:** Centro de control para migraciones
- **AWS Application Migration Service:** Migración de aplicaciones
- **AWS Database Migration Service:** Migración de bases de datos
- **AWS Snow Family:** Migración de datos offline
- **Casos de uso:** Migración a la nube, modernización de aplicaciones.

## ⚙️ Servicios de Orquestación y Automatización

### AWS Step Functions

**¿Para qué sirve?** Servicio de orquestación que permite coordinar múltiples servicios de AWS en flujos de trabajo serverless.

- **Casos de uso:** Automatización de procesos, orquestación de microservicios, flujos de trabajo complejos.

## 📱 Servicios de Comunicación

### Amazon Pinpoint

**¿Para qué sirve?** Servicio de comunicación multicanal que permite enviar mensajes dirigidos a través de email, SMS, push y voz.

- **Casos de uso:** Campañas de marketing, notificaciones push, comunicación con clientes.

## 🛰️ Servicios Especializados

### AWS Ground Station

**¿Para qué sirve?** Servicio completamente administrado que permite controlar comunicaciones satelitales, procesar datos y escalar operaciones.

- **Casos de uso:** Comunicación con satélites, descarga de datos satelitales, operaciones espaciales.

### Amazon EMR
**¿Para qué sirve?** Servicio administrado para procesamiento de big data que permite ejecutar frameworks como Apache Spark, Hadoop y Hive en clústeres escalables.

- **Casos de uso:** ETL distribuido, análisis de logs, procesamiento de datos para machine learning, análisis de comportamiento web.


### AWS Marketplace 

permite a los socios cualificados comercializar y vender su software a los clientes de AWS. AWS Marketplace es una tienda de software en línea que ayuda a los clientes a encontrar, comprar y empezar a usar de inmediato el software y los servicios que se ejecutan en AWS.

AWS Marketplace está diseñado para proveedores independientes de software (ISV), revendedores de valor añadido (VAR) e integradores de sistemas (SI) que desean ofrecer productos de software a sus clientes en la nube. Los socios utilizan AWS Marketplace para estar operativos en cuestión de días y ofrecer sus productos de software a clientes de todo el mundo.

## Otros servicios


### 🔐 Amazon GuardDuty

**Definición oficial (AWS):**  
Amazon GuardDuty es un servicio de detección de amenazas que supervisa continuamente cuentas, cargas de trabajo y datos en AWS para identificar actividades maliciosas mediante IA, ML e inteligencia sobre amenazas.

**¿Para qué sirve?**  
Detecta accesos no autorizados, malware, minería de criptomonedas y comportamientos anómalos en tu entorno AWS.

**Tecnología:**  
- Machine learning (ML) y modelado de comportamiento  
- Inteligencia sobre amenazas (IP maliciosas, dominios, hashes)  
- Integración con MITRE ATT&CK y AWS Security Hub

**Casos de uso:**  
- Detección de credenciales comprometidas  
- Supervisión de buckets S3, EC2, Lambda, EKS  
- Alertas por actividad sospechosa en CloudTrail y DNS  
- Protección contra ransomware y malware en EBS y S3  

---

### 🛡️ AWS Inspector

**Definición oficial (AWS):**  
Amazon Inspector es un servicio automatizado de administración de vulnerabilidades que analiza continuamente cargas de trabajo en AWS para detectar vulnerabilidades de software y exposiciones de red no deseadas.

**¿Para qué sirve?**  
Evalúa la seguridad de instancias EC2, contenedores ECR y funciones Lambda, identificando CVEs y dependencias inseguras.

**Tecnología:**  
- Escaneo continuo basado en CVE y SBOM (Software Bill of Materials)  
- Evaluación de paquetes del sistema operativo y dependencias de software  
- Puntuación de riesgo contextual (CVSS ajustado al entorno)

**Casos de uso:**  
- Detección de vulnerabilidades en tiempo real  
- Priorización de parches según exposición a red  
- Cumplimiento normativo (PCI DSS, NIST CSF)  
- Integración con CI/CD y exportación de hallazgos a EventBridge  

---

### 🕵️‍♂️ AWS Detective

**Definición oficial (AWS):**  
Amazon Detective recopila automáticamente datos de registro y utiliza machine learning, análisis estadístico y teoría de grafos para facilitar investigaciones de seguridad eficientes y visuales.

**¿Para qué sirve?**  
Permite analizar la causa raíz de incidentes de seguridad mediante visualizaciones interactivas y correlación de eventos.

**Tecnología:**  
- Machine learning (ML) + teoría de grafos  
- Visualización de relaciones entre usuarios, IPs, roles IAM y recursos  
- Integración con GuardDuty, CloudTrail y Security Hub

**Casos de uso:**  
- Investigación de IAM comprometido  
- Trazabilidad de actividad sospechosa en EC2, S3, RDS  
- Análisis de grupos de búsqueda relacionados con incidentes  
- Auditoría de eventos históricos hasta por 12 meses  

## Servicios de Análisis y Consulta de Datos

- **Amazon Athena:** Consulta interactiva sin servidor sobre datos en S3 usando SQL.
- **Amazon Redshift:** Almacén de datos escalable para análisis complejos.
- **AWS Glue:** Catálogo de datos y ETL serverless.
- **Amazon QuickSight:** Visualización de datos y BI.

### Amazon Athena  
**¿Para qué sirve?** Servicio de consultas sin servidor que permite analizar datos directamente en Amazon S3 usando SQL estándar, sin necesidad de cargar ni transformar previamente los datos【6†】.

- **Casos de uso:**  
  - Análisis ad hoc de datos almacenados en S3  
  - Generación de reportes sin ETL  
  - Exploración de logs, archivos JSON, CSV y Parquet  
  - Preparación de datos para machine learning  
  - Integración con AWS Glue, QuickSight y Apache Spark

### 🧪 AWS Glue

**Definición oficial (AWS):**  
AWS Glue es un servicio de integración de datos sin servidor que facilita a los usuarios descubrir, preparar, migrar e integrar datos desde múltiples orígenes. Permite crear, ejecutar y supervisar canalizaciones ETL (extracción, transformación y carga) para análisis, machine learning y desarrollo de aplicaciones.

**¿Para qué sirve?**  
Automatiza el procesamiento de datos a gran escala, eliminando la necesidad de administrar servidores o infraestructura. Es ideal para preparar datos antes de analizarlos o entrenar modelos de IA.

**Tecnología:**  
- Basado en **Apache Spark sin servidor**  
- Usa **machine learning (ML)** para detección de esquemas y generación de código ETL  
- Compatible con más de **70 orígenes de datos**  
- Incluye **Glue Studio** para diseño visual de flujos de datos  
- Soporta **SBOM** y validación de esquemas para calidad de datos

**Casos de uso:**  
- Integración de datos desde S3, RDS, Redshift, JDBC, entre otros  
- Transformación de datos para lagos de datos y almacenes analíticos  
- Limpieza y normalización de datos para modelos de machine learning  
- Validación de dependencias y estructuras de paquetes en pipelines de datos  
- Automatización de flujos ETL en entornos multi-origen

**Explicación complementaria:**  
AWS Glue permite que desarrolladores y analistas trabajen con datos sin preocuparse por la infraestructura. Su motor Spark sin servidor escala automáticamente y su catálogo centralizado facilita la reutilización de esquemas. Además, con herramientas como Glue Studio y la integración con SageMaker, se convierte en una solución potente para arquitecturas de datos modernas.


### Amazon CloudTrail  
**¿Para qué sirve?** Servicio de auditoría que registra todas las acciones realizadas en tu cuenta AWS, incluyendo llamadas a la API, acceso a recursos y cambios en la configuración.  
- **Casos de uso:** Cumplimiento normativo (SOC, PCI, HIPAA), análisis forense, detección de accesos no autorizados, trazabilidad de eventos operativos【6†】.
- se puede configurar un trail para registrar eventos de api, tamibne se puede elegir si se aplica todas las regiones o una region

### Amazon CloudWatch  
**¿Para qué sirve?** Plataforma de monitoreo y observabilidad que recopila métricas, logs y eventos de servicios AWS y aplicaciones personalizadas, permitiendo visualizar el estado operativo y configurar alarmas automatizadas.  
- **Casos de uso:** Supervisión de rendimiento de aplicaciones, detección de anomalías, activación de respuestas automáticas, optimización de recursos, análisis de causa raíz【13†】.

### Amazon SNS  
**¿Para qué sirve?** Servicio de mensajería que permite enviar notificaciones a múltiples destinatarios mediante el modelo de publicación-suscripción (pub/sub).

- **Casos de uso:**  
  - Alertas automáticas desde CloudWatch Alarms  
  - Notificaciones push a dispositivos móviles  
  - Integración con SQS, Lambda y HTTP endpoints  
  - Difusión de eventos a múltiples sistemas

🔗 Requiere otro servicio (como CloudWatch Alarms) para generar las alertas que luego SNS distribuye a sus suscriptores.

### Amazon SQS  
**¿Para qué sirve?** Servicio de colas de mensajes totalmente gestionado que permite desacoplar componentes de aplicaciones distribuidas.

- **Casos de uso:**  
  - Comunicación entre microservicios  
  - Procesamiento asíncrono de tareas  
  - Almacenamiento temporal de eventos  
  - Uso de colas FIFO para orden estricto y entrega única

🔗 Compatible con SNS para fan-out, y con Lambda para procesamiento sin servidor.

### AWS Config  
**¿Para qué sirve?** Servicio de auditoría y cumplimiento que registra configuraciones de recursos AWS y evalúa su conformidad con reglas definidas.
es un servicio que le permite registrar el historial de configuración de sus recursos de AWS y evaluar su cumplimiento con sus políticas internas y prácticas recomendadas. Estos datos se pueden utilizar para el diagnóstico de problemas operativos, auditorías y fines relacionados con el cumplimiento normativo.
- **Casos de uso:**  
  - Validación de políticas de seguridad y gobernanza  
  - Auditoría de cambios en recursos (EC2, IAM, S3, etc.)  
  - Generación de reportes de cumplimiento  
  - Integración con AWS Organizations para control centralizado
  - Facilita el cumplimiento de los requisitos reglamentarios y las mejores prácticas.

🔗 No monitorea métricas en tiempo real; se enfoca en configuración y cumplimiento.

### AWS Systems Manager  
**¿Para qué sirve?** Permite administrar servidores que se ejecutan en AWS y en centros de datos locales desde una única interfaz. Ofrece herramientas como Run Command, Session Manager y Parameter Store para automatizar tareas, ejecutar scripts y centralizar configuraciones.  
- **Casos de uso:** Administración remota, ejecución de comandos en múltiples servidores, gestión de parches, almacenamiento seguro de parámetros.  
- **¿Funciona en on-premise?** ✅ Sí. Mediante activación híbrida, se pueden registrar servidores locales como instancias administradas.  
- **Tipo de implementación:** 🌐 **Híbrida** (AWS + on-premise)

### AWS CodeDeploy  
**¿Para qué sirve?** Automatiza la implementación de código en instancias EC2, servidores locales y contenedores. Permite despliegues sin tiempo de inactividad, control de versiones y rollback automático.  
- **Casos de uso:** Actualización continua de aplicaciones, despliegue en múltiples entornos, integración con pipelines CI/CD.  
- **¿Funciona en on-premise?** ✅ Sí. Se pueden registrar instancias físicas locales para recibir despliegues mediante el agente de CodeDeploy.  
- **Tipo de implementación:** 🌐 **Híbrida** (AWS + on-premise)

### 🌐 Componentes de Red en AWS

## 🌐 Servicios de red en AWS: Definiciones y usos

| Servicio                   | Definición oficial AWS                                                                 | ¿Para qué sirve?                                                                 |
|----------------------------|-----------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| **Internet Gateway**       | Componente escalable que permite comunicación entre VPC e Internet.                    | Acceso bidireccional desde subredes públicas a Internet.                        |
| **NAT Gateway**            | Servicio gestionado para acceso saliente desde subredes privadas.                      | Permite salida a Internet sin exponer IP privadas; no acepta tráfico entrante. |
| **Transit Gateway**        | Enrutador centralizado para conectar múltiples VPCs y redes on-premises.               | Simplifica la arquitectura de red a gran escala; reemplaza emparejamientos.    |
| **VPC Peering**            | Conexión privada entre dos VPCs para enrutar tráfico entre ellas.                      | Comunicación directa entre VPCs sin usar VPN ni gateway.                        |
| **VPC Endpoint**           | Conexión privada entre VPC y servicios AWS sin pasar por Internet.                     | Mejora seguridad y rendimiento; evita uso de NAT o IGW para servicios internos.|
| **Direct Connect**         | Conexión física dedicada entre tu red local y AWS.                                     | Latencia predecible, mayor ancho de banda y seguridad reforzada.               |
| **Elastic IP**             | Dirección IPv4 pública estática asociada a tu cuenta AWS.                              | Permite mantener IP fija para instancias EC2, incluso tras reinicios.          |
| **Route Table**            | Conjunto de reglas que determinan el destino del tráfico de red.                       | Controla el enrutamiento entre subredes, gateways y conexiones externas.       |
| **Security Group**         | Firewall virtual a nivel de instancia EC2.                                             | Controla tráfico entrante/saliente; solo permite reglas "allow".               |
| **Network ACL (NACL)**     | Lista de control de acceso a nivel de subred.                                          | Permite y deniega tráfico; es stateless y evalúa reglas en orden.              |
| **Virtual Private Gateway**| Componente para conectar tu red on-premises a tu VPC mediante VPN.                    | Comunicación segura entre red local y AWS; no monitorea ni escala instancias.  |
| **Amazon LightSail**       | Solución VPS simplificada con recursos preconfigurados.                               | Ideal para sitios web pequeños; no ofrece escalado automático ni monitoreo avanzado. |
| **AWS PrivateLink**        | Tecnología escalable y de alta disponibilidad para conectar VPC a servicios de forma privada. | Permite acceso privado a servicios sin pasar por Internet; mejora seguridad y control. |
| **AWS Site-to-Site VPN**   | Servicio gestionado que crea una conexión segura entre tu red local y AWS mediante túneles IPsec. | Conecta tu centro de datos o sucursal a AWS; ideal para migraciones y comunicación segura. |

### ❄️ Comparativa: AWS Snowcone vs AWS Snowball Edge

| Característica                  | 🧊 AWS Snowcone                                      | 🧊 AWS Snowball Edge                                  |
|--------------------------------|------------------------------------------------------|--------------------------------------------------------|
| **Propósito principal**         | Transferencia ligera y edge computing portátil       | Migración masiva y procesamiento local intensivo       |
| **Capacidad de almacenamiento**| 8 TB (HDD) o 14 TB (SSD)                             | Hasta 210 TB (Storage) / 42 TB + GPU (Compute)         |
| **Capacidad de cómputo**        | 2 vCPU, 4 GB RAM                                     | Hasta 52 vCPU, soporte EC2, EKS Anywhere               |
| **Tamaño y portabilidad**       | Ultra portátil (2.1 kg, tamaño de libro)             | Maleta robusta, requiere transporte especializado      |
| **Transferencia de datos**      | Offline (envío físico) / Online (DataSync)           | Offline / Online / NFS / S3 API compatible             |
| **Velocidad de transferencia**  | Hasta 100 MB/s                                       | Hasta 250 MB/s (con redes de hasta 100 Gbps)【8†】      |
| **Acelera TB a PB**             | ❌ No diseñado para volúmenes petabyte               | ✅ Sí, optimizado para migraciones a escala PB【6†】【8†】|
| **Casos de uso**                | IoT, drones, vehículos, sitios sin conectividad      | Migraciones masivas, ML local, fábricas, entornos industriales |
| **Costo y logística**           | Bajo costo, fácil envío                             | Mayor costo, requiere planificación logística          |

### Amazon RDS  
**¿Para qué sirve?** Servicio administrado para bases de datos relacionales como MySQL, PostgreSQL, MariaDB, Oracle y SQL Server. Automatiza tareas como backups, escalado y actualizaciones.  
- **Casos de uso:** Aplicaciones empresariales, backend de apps móviles, sistemas institucionales.  


### Amazon DynamoDB  
**¿Para qué sirve?** Base de datos NoSQL completamente administrada, diseñada para alta disponibilidad, baja latencia y escalabilidad automática.  
- **Casos de uso:** Juegos, IoT, sesiones de usuario, catálogos de productos.  

### Amazon DocumentDB  
**¿Para qué sirve?** Base de datos de documentos JSON compatible con MongoDB, completamente administrada y escalable.  
- **Casos de uso:** Perfiles de usuario, CMS, apps móviles, recomendaciones con IA.  

### Amazon Aurora  
**¿Para qué sirve?** Motor de base de datos relacional compatible con MySQL y PostgreSQL, optimizado para rendimiento y disponibilidad.  
- **Casos de uso:** Aplicaciones críticas, plataformas SaaS, sistemas financieros.  

### Amazon ElastiCache  
**¿Para qué sirve?** Servicio de caché en memoria compatible con Redis y Memcached, diseñado para acelerar aplicaciones con latencia de microsegundos.  
- **Casos de uso:** Almacenamiento de sesiones, rankings en tiempo real, limitación de tasa, mejora de rendimiento de bases de datos.  
-
### Amazon Redshift  
**¿Para qué sirve?** Data warehouse en la nube para análisis de grandes volúmenes de datos con SQL, integración con S3 y herramientas de BI.  
- **Casos de uso:** Inteligencia empresarial, análisis de logs, dashboards, machine learning con SageMaker.  


### Amazon Timestream  
**¿Para qué sirve?** Base de datos de series temporales optimizada para IoT, DevOps y análisis en tiempo real, con consultas SQL y escalado automático.  
- **Casos de uso:** Métricas operativas, monitoreo de infraestructura, análisis de tráfico web, series temporales con ML.  

### ☁️ Clasificación de servicios AWS por modelo de entrega

| Modelo     | Servicios AWS representativos                                                                 |
|------------|-----------------------------------------------------------------------------------------------|
| **IaaS**   | Amazon EC2, Amazon EBS, Amazon VPC, Elastic Load Balancing, AWS IAM, AWS Direct Connect       |
| **PaaS**   | AWS Lambda, AWS Elastic Beanstalk, Amazon RDS, Amazon S3, Amazon DynamoDB, Amazon EMR, Amazon OpenSearch Service, Amazon Timestream, Amazon Aurora, Amazon ElastiCache, Amazon Neptune |
| **SaaS**   | Amazon Chime, Amazon WorkSpaces, Amazon QuickSight, AWS Marketplace (apps SaaS), AWS Honeycode |


## Servicios de Almacenamiento en AWS

### Amazon S3  
**¿Para qué sirve?** Almacenamiento de objetos escalable, duradero y accesible desde cualquier parte.  
- **Casos de uso:**  
  - Backup y archivado  
  - Hosting de sitios estáticos  
  - Almacenamiento de datos para análisis (Athena, Redshift Spectrum)  
  - Integración con Lambda, CloudFront y Glacier

---

### Amazon EFS  
**¿Para qué sirve?** Sistema de archivos elástico y compartido para instancias EC2 y otros servicios.  
- **Casos de uso:**  
  - Compartir archivos entre múltiples instancias  
  - Persistencia en contenedores (ECS, EKS, Fargate)  
  - Ciencia de datos y machine learning  
  - DevOps y CMS distribuidos

---

### Amazon EBS  
**¿Para qué sirve?** Almacenamiento en bloque para instancias EC2, ideal para bases de datos y sistemas operativos.  
- **Casos de uso:**  
  - Volúmenes raíz de EC2  
  - Bases de datos relacionales y NoSQL  
  - Aplicaciones con alto IOPS  
  - Snapshots para recuperación ante desastres

---

### Amazon FSx  
**¿Para qué sirve?** Sistemas de archivos administrados con soporte para protocolos estándar (SMB, NFS, Lustre, ZFS).  
- **Casos de uso:**  
  - FSx for Windows: Integración con Active Directory  
  - FSx for Lustre: HPC y machine learning  
  - FSx for NetApp ONTAP: NFS, SMB, iSCSI  
  - FSx for OpenZFS: NFS para cargas Linux


## Comparativa de Clases de Almacenamiento en Amazon S3

| Clase de Almacenamiento         | Disponibilidad | Zonas de Disponibilidad | Frecuencia de Acceso     | Tiempo de Recuperación       |
|---------------------------------|----------------|--------------------------|---------------------------|------------------------------|
| S3 Standard                     | 99.99%         | Múltiples (≥3 AZ)        | Frecuente                 | Inmediato (milisegundos)     |
| S3 Intelligent-Tiering          | 99.9%          | Múltiples (≥3 AZ)        | Variable / impredecible   | Inmediato o automático       |
| S3 Standard-IA                  | 99.9%          | Múltiples (≥3 AZ)        | Poco frecuente            | Inmediato (milisegundos)     |
| S3 One Zone-IA                  | 99.5%          | Una sola AZ              | Poco frecuente            | Inmediato (milisegundos)     |
| S3 Glacier Instant Retrieval    | 99.9%          | Múltiples (≥3 AZ)        | Raro pero urgente         | Milisegundos a segundos      |
| S3 Glacier Flexible Retrieval   | 99.9%          | Múltiples (≥3 AZ)        | Muy raro                  | Minutos a horas              |
| S3 Glacier Deep Archive         | 99.99%         | Múltiples (≥3 AZ)        | Casi nunca                | Horas (hasta 12 horas)       |
| S3 Express One Zone             | 99.99%         | Una sola AZ              | Frecuente y sensible a latencia | Milisegundos (ultra rápido) |


## Comparativa: SSD vs HDD en AWS

| Característica                        | SSD (Solid State Drive)                                                                 | HDD (Hard Disk Drive)                                                                 |
|--------------------------------------|------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|
| **Mejor para cargas de trabajo con:**| *Operaciones de I/O pequeñas y aleatorias*                                               | *Operaciones de I/O grandes y secuenciales*                                            |
| **¿Puede usarse como volumen de arranque?** | Sí                                                                                       | No                                                                                     |
| **Casos de uso recomendados**        | - Aplicaciones transaccionales críticas<br>- Workloads que requieren IOPS sostenido<br>- Bases de datos como MongoDB, Oracle, SQL Server | - Procesamiento de logs<br>- Big data y data warehouses<br>- Almacenamiento de datos de acceso poco frecuente |
| **Costo**                            | Moderado / Alto                                                                          | Bajo                                                                                   |
| **Atributo dominante de rendimiento**| IOPS                                                                                     | Throughput (MiB/s)                                                                     |

## Tipos de Volúmenes Amazon EBS

| Tipo de Volumen                   | Tipo de Disco | ¿Volumen de Arranque? | Casos de Uso Recomendados                                                                 | Características Clave                          |
|----------------------------------|---------------|------------------------|-------------------------------------------------------------------------------------------|------------------------------------------------|
| gp3 (SSD de propósito general)   | SSD           | ✅ Sí                  | - Entornos de desarrollo y prueba<br>- Aplicaciones generales                             | Balance entre costo y rendimiento              |
| io2/io1 (SSD con IOPS aprovisionadas) | SSD      | ✅ Sí                  | - Bases de datos empresariales<br>- Aplicaciones críticas con alto IOPS sostenido         | Alto rendimiento, alta durabilidad             |
| st1 (HDD optimizado para rendimiento) | HDD       | ❌ No                 | - Big data<br>- Almacenes de datos<br>- Procesamiento de registros                        | Alto throughput a bajo costo                   |
| sc1 (Disco duro frío)            | HDD           | ❌ No                 | - Datos de acceso poco frecuente<br>- Archivos grandes<br>- Costos mínimos de almacenamiento | Muy bajo costo, rendimiento limitado           |

## administraciones

### Amazon Cognito  
**¿Para qué sirve?** Servicio de gestión de identidades que permite añadir registro, inicio de sesión y control de acceso a aplicaciones web y móviles de forma rápida y escalable【6†】.  
- **Casos de uso:**  
  - Registro y autenticación de usuarios con UI personalizable  
  - Inicio de sesión con proveedores sociales (Google, Facebook, Amazon)  
  - Integración con directorios empresariales vía SAML 2.0 y OIDC  
  - Emisión de tokens JWT para acceso seguro a APIs y recursos AWS  
  - Control de acceso granular con roles IAM y atributos personalizados  
  - Autenticación sin contraseña con WebAuthn, OTP por SMS o correo  
  - Escalabilidad a millones de usuarios con CIAM (Customer Identity and Access Management)


###  Amazon Cognito Identity Pool

proporciona credenciales temporales de AWS para usuarios invitados (no autenticados) y para usuarios autenticados que recibieron un token. Un grupo de identidades almacena datos de identidad de usuario específicos de su cuenta.

Los grupos de identidades de Amazon Cognito permiten crear identidades únicas y asignar permisos a los usuarios. Su grupo de identidades puede incluir:

– Usuarios en un grupo de usuarios de Amazon Cognito

– Usuarios que se autentican con proveedores de identidad externos como Facebook, Google o un proveedor de identidad basado en SAML

– Los usuarios se autentican a través de su propio proceso de autenticación existente

### AWS Artifact  
**¿Para qué sirve?** Portal de autoservicio que proporciona acceso bajo demanda a informes de cumplimiento, certificaciones (SOC 1, SOC 2, ISO, PCI DSS) y acuerdos legales como NDA y BAA【17†】.  
- **Casos de uso:**  
  - Descarga de informes de cumplimiento para auditores  
  - Validación de controles de seguridad de AWS  
  - Gestión de acuerdos legales con AWS  
  - Evaluación de proveedores en AWS Marketplace

---

### AWS GovCloud (US)  
**¿Para qué sirve?** Región aislada de AWS diseñada para agencias gubernamentales de EE. UU. y clientes con requisitos regulatorios estrictos (ITAR, FedRAMP High, DoD IL5)【25†】.  
- **Casos de uso:**  
  - Migración de cargas sensibles del gobierno  
  - Cumplimiento de normativas federales y militares  
  - Procesamiento de datos clasificados  
  - Aislamiento físico y lógico para seguridad reforzada

---

### AWS Audit Manager  
**¿Para qué sirve?** Servicio que automatiza la recopilación de evidencia para auditorías, basado en marcos como SOC 2, ISO 27001, PCI DSS y NIST【15†】.  
- **Casos de uso:**  
  - Preparación para auditorías internas y externas  
  - Evaluación continua de controles de seguridad  
  - Generación de reportes de evaluación personalizados  
  - Integración con AWS Config y Security Hub

---

### AWS Certificate Manager (ACM)  
**¿Para qué sirve?** Servicio que permite aprovisionar, administrar y renovar certificados SSL/TLS públicos y privados para proteger aplicaciones y recursos en AWS【6†】.  
- **Casos de uso:**  
  - Protección de endpoints con HTTPS (CloudFront, ELB, API Gateway)  
  - Gestión centralizada de certificados  
  - Emisión de certificados privados con AWS Private CA  
  - Renovación automática de certificados públicos

### AWS IAM Policy Simulator  
 **¿Para qué sirve?** Herramienta que permite simular y probar el efecto de políticas IAM (identity-based, resource-based y boundaries) antes de aplicarlas en producción【6†】.  
- **Casos de uso:**  
  - Validación de políticas antes de implementarlas  
  - Simulación de permisos para usuarios, grupos y roles  
  - Evaluación de condiciones, contextos y restricciones  
  - Identificación de conflictos entre políticas adjuntas  
  - Pruebas de políticas personalizadas sin necesidad de adjuntarlas

## Modelo de responsabilidad compartida

AWS adopta un modelo de responsabilidad compartida en el que tanto el proveedor como el cliente tienen roles definidos en la gestión de la seguridad y el cumplimiento.

### Controles heredados  
Son aquellos controles de seguridad que AWS gestiona por completo y que el cliente hereda sin necesidad de ninguna acción adicional.  
- **Ejemplos de controles heredados:**  
  - Controles físicos y ambientales  
  - Administración de parches de la infraestructura base  
  - Configuración del hardware de AWS  
  - Seguridad de las capas de virtualización  
  - Seguridad de las redes subyacentes

  - Controles físicos y ambientales  
Estos controles se refieren a la seguridad física de los centros de datos de AWS, la infraestructura de red (cables, servidores, etc.) y otros aspectos relacionados con el entorno físico donde se ejecutan los servicios de AWS.

### Responsabilidad compartida  
AWS se responsabiliza de la seguridad **de la nube**, es decir, de la infraestructura física y virtual que proporciona.  
El cliente es responsable de la seguridad **en la nube**, es decir, de la configuración, gestión y protección de sus propias cargas de trabajo y datos en AWS.

- **Responsabilidad de AWS:**  
  - Infraestructura física  
  - Virtualización  
  - Red subyacente  
  - Seguridad de centros de datos

- **Responsabilidad del cliente:**  
  - Configuración de servicios (IAM, VPC, S3, etc.)  
  - Gestión de datos y cifrado  
  - Control de acceso y autenticación  
  - Actualización de sistemas operativos y aplicaciones

## Cifrado del lado del servidor en AWS

### ¿Quién se encarga?
AWS gestiona el cifrado de los datos en reposo cuando se utiliza SSE, pero el cliente puede decidir cómo se administran las claves:

- **SSE-S3 (Server-Side Encryption con claves gestionadas por Amazon S3):**  
  - **Responsable:** AWS  
  - **Descripción:** Cifrado automático con claves gestionadas por S3. No requiere configuración adicional.  
  - **Uso típico:** Buckets estándar con cifrado predeterminado activado.

- **SSE-KMS (Server-Side Encryption con AWS Key Management Service):**  
  - **Responsable:** AWS gestiona el cifrado, pero el cliente controla las claves mediante AWS KMS.  
  - **Descripción:** Permite auditoría, control de acceso granular y rotación de claves.  
  - **Uso típico:** Datos sensibles que requieren trazabilidad y control de claves.

- **SSE-C (Server-Side Encryption con claves proporcionadas por el cliente):**  
  - **Responsable:** El cliente  
  - **Descripción:** El cliente proporciona la clave en cada solicitud. AWS no almacena la clave.  
  - **Uso típico:** Casos donde el cliente quiere control total sobre las claves sin usar KMS.

### AWS WAF (Web Application Firewall)  
**¿Para qué sirve?** Firewall de aplicaciones web que permite crear reglas para filtrar el tráfico HTTP/HTTPS hacia recursos como CloudFront, API Gateway y ALB【1†】.  
- **Casos de uso:**  
  - Protección contra inyecciones SQL y scripting entre sitios (XSS)  
  - Filtrado por IP, encabezados, URI y cuerpo de la solicitud  
  - Implementación de CAPTCHA y desafíos silenciosos  
  - Prevención de fraude en páginas de inicio de sesión  
  - Integración con AWS Firewall Manager para administración centralizada

---

### AWS Shield  
**¿Para qué sirve?** Servicio gestionado que protege aplicaciones en AWS contra ataques de denegación de servicio distribuido (DDoS) en capas de red, transporte y aplicación【7†】.  
- **Casos de uso:**  
  - Protección automática contra ataques DDoS (Shield Standard)  
  - Mitigación avanzada con soporte 24/7 y visibilidad de eventos (Shield Advanced)  
  - Integración con CloudFront, ALB, Route 53 y Global Accelerator  
  - Reducción de superficie de ataque y respuesta automatizada  
  - Activación de planes de respuesta ante incidentes

### Amazon EC2 Reserved Instances  
**¿Para qué sirve?** Permite reservar capacidad de instancias EC2 por uno o tres años con un **descuento significativo** frente al precio On-Demand. Si se asignan a una zona de disponibilidad específica, también ofrecen **reserva de capacidad**, lo que garantiza disponibilidad para lanzar instancias cuando se necesiten.

- **Opciones de pago disponibles:**  
  - **All Upfront (Pago total por adelantado):**  
    Pagas el costo completo del período de la instancia reservada en un solo pago inicial.  
    🔹 Proporciona el mayor descuento frente a On-Demand.

  - **Partial Upfront (Pago parcial por adelantado):**  
    Realizas un pago inicial bajo y luego se te cobra una tarifa horaria con descuento durante el período.  
    🔹 Equilibrio entre ahorro y flujo de caja.

  - **No Upfront (Sin pago por adelantado):**  
    No requiere pago inicial. Se aplica una tarifa horaria con descuento durante todo el período.  
    🔹 Ideal para presupuestos ajustados, requiere historial de facturación exitoso.

- **Casos de uso:**  
  - Workloads estables y predecibles  
  - Aplicaciones empresariales con alta disponibilidad  
  - Optimización de costos en entornos de producción  
  - Garantía de capacidad en zonas específicas

### 🧩 Amazon EC2 Reserved Instances: Estándar vs. Convertibles

Las **Instancias Reservadas (RI)** permiten ahorrar significativamente frente al precio On-Demand, al comprometerse por 1 o 3 años. Existen dos clases principales:

| Tipo de RI | Descuento promedio | Flexibilidad | Intercambio permitido | Se puede vender en Marketplace | Casos de uso |
|------------|--------------------|--------------|------------------------|-------------------------------|--------------|
| **Standard Reserved Instance**<br>Instancia Reservada Estándar | Hasta 75% | ✅ Modificar zona, tamaño, tipo de red (dentro de misma familia) | ❌ No | ✅ Sí | Workloads estables, proyectos de largo plazo, entornos sensibles al costo |
| **Convertible Reserved Instance**<br>Instancia Reservada Convertible | Hasta 55% | ✅ Cambiar familia, tipo, SO, tenencia | ✅ Sí, si el nuevo valor es igual o mayor | ❌ No | Workloads estables con evolución arquitectónica, flexibilidad operativa |

> Ambas opciones son adecuadas para **uso en estado estable**, pero las **Convertibles** permiten intercambios múltiples siempre que el valor de la nueva RI sea igual o superior.

---

### 💳 Opciones de pago / Payment Options

| Opción | Español | Descripción |
|--------|---------|-------------|
| **All Upfront** | Pago total por adelantado | Pago único al inicio. Máximo descuento. |
| **Partial Upfront** | Pago parcial por adelantado | Pago inicial bajo + tarifa horaria con descuento. |
| **No Upfront** | Sin pago por adelantado | Solo tarifa horaria con descuento. Requiere historial de facturación confiable. |

---

### 📌 Recomendaciones

- Usa **Standard RI** si tu carga es predecible y buscas el mayor ahorro.
- Elige **Convertible RI** si anticipas cambios en tipo de instancia, SO o tenencia.
- Ambas permiten elegir zona de disponibilidad para **reserva de capacidad**.
### 🧠 Tipos de instancias EC2 según modelo de compra

Amazon EC2 ofrece múltiples modelos de compra para adaptarse a distintos escenarios de negocio, presupuesto y tolerancia al riesgo:

| Tipo de instancia | Descripción | Ventajas | Limitaciones | Casos de uso |
|-------------------|-------------|----------|--------------|--------------|
| **On-Demand Instance**<br>Instancia Bajo Demanda | Pago por segundo sin compromiso. | 🔹 Máxima flexibilidad<br>🔹 Sin contrato | 🔸 Costo más alto<br>🔸 No garantiza capacidad | Pruebas, cargas impredecibles, picos temporales |
| **Reserved Instance – Standard**<br>Instancia Reservada Estándar | Compromiso de 1 o 3 años. Descuento hasta 75%. | 🔹 Ahorro significativo<br>🔹 Reserva de capacidad | 🔸 Menor flexibilidad<br>🔸 No se puede cambiar familia | Workloads estables, producción crítica |
| **Reserved Instance – Convertible**<br>Instancia Reservada Convertible | Compromiso de 1 o 3 años. Descuento hasta 55%. | 🔹 Permite cambiar familia, SO, tenencia<br>🔹 Uso estable | 🔸 No se puede vender en Marketplace | Workloads estables con evolución arquitectónica |
| **Spot Instance**<br>Instancia Puntual | Capacidad sobrante con hasta 90% de descuento. | 🔹 Ahorro extremo<br>🔹 Ideal para cargas tolerantes a fallos | 🔸 Puede ser interrumpida con 2 minutos de aviso | ML, Big Data, CI/CD, apps sin estado |
| **Savings Plans** | Compromiso de uso (USD/hora) por 1 o 3 años. | 🔹 Ahorro flexible<br>🔹 Aplica a múltiples servicios | 🔸 No garantiza capacidad<br>🔸 No reserva zona | Migraciones, consolidación de costos |
| **Dedicated Host** | Servidor físico dedicado para cumplir requisitos de licencia. | 🔹 Control total<br>🔹 Licenciamiento BYOL | 🔸 Costo elevado<br>🔸 Complejidad operativa | Software con licencias específicas, cumplimiento normativo |

---

### 💡 Aclaración sobre Spot Pricing

> AWS simplificó el modelo de precios Spot para hacerlo **predecible y gradual**, ajustándose a tendencias de oferta y demanda.  
> El precio Spot vigente se aplica al inicio de cada hora de ejecución. Las instancias pueden ser **interrumpidas con 2 minutos de aviso**.

---

### 📌 Recomendaciones rápidas

- Usa **On-Demand** si necesitas rapidez sin planificación previa.
- Elige **Spot** si tu aplicación tolera interrupciones y buscas optimizar costos.
- Considera **Reserved Instances** si tu carga es estable y continua.
- Evalúa **Savings Plans** si prefieres flexibilidad sin reservar capacidad.
- Opta por **Dedicated Hosts** si tienes requisitos de licenciamiento o cumplimiento.

🔗 [Tipos de instancias EC2 – AWS](https://aws.amazon.com/ec2/instance-types/)  
🔗 [Comparación interactiva de instancias EC2 – Vantage](https://instances.vantage.sh/)

### 📊 AWS Cost and Usage Report (CUR)

El **Informe de Costos y Uso de AWS (CUR)** es la fuente más completa y granular para analizar el gasto y consumo de servicios en AWS. Permite visualizar el uso por servicio, usuario IAM, etiquetas activadas y tipo de instancia (incluyendo RI, Spot, On-Demand).

---

### 🧩 Funcionalidades principales

| Funcionalidad | Descripción |
|---------------|-------------|
| **Granularidad horaria y diaria** | Permite visualizar el uso por hora, día o mes. Ideal para análisis detallado y optimización. |
| **Seguimiento de Instancias Reservadas (RI)** | Cada línea de uso con descuento RI incluye información sobre la asignación del beneficio. |
| **Etiquetas activadas para asignación de costos** | Permite segmentar el gasto por proyecto, equipo o aplicación mediante etiquetas personalizadas. |
| **Integración con herramientas analíticas** | Compatible con Amazon Athena, Amazon Redshift y Amazon QuickSight para consultas SQL, dashboards y visualizaciones. |
| **Exportación automática a S3** | Los datos se almacenan en formato CSV o Parquet en un bucket S3 definido por el usuario. |
| **Actualización diaria** | El informe se actualiza al menos una vez al día, con opción de hasta tres actualizaciones diarias. |

## 💰 Glosario bilingüe de gestión de costos en AWS

| Término técnico en inglés               | Definición en español                                                                 |
|----------------------------------------|----------------------------------------------------------------------------------------|
| **Consolidated Billing**               | Facturación consolidada que permite agrupar múltiples cuentas AWS bajo una cuenta principal (management account), generando una sola factura y aplicando descuentos por volumen. [Fuente oficial](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/consolidated-billing.html) |
| **AWS Cost Explorer**                  | Herramienta visual para analizar el uso y los costos de AWS. Permite identificar tendencias, filtrar por servicio, cuenta o etiqueta, y proyectar gastos futuros, tambien ofrece recomendacoines de compra instancias reservadas. [Documentación oficial](https://docs.aws.amazon.com/cost-management/latest/userguide/ce-what-is.html) |
| **AWS Cost and Usage Reports (CUR)**   | Informes detallados en formato CSV que desglosan el uso y los costos por hora, servicio, recurso o etiqueta. Se almacenan en Amazon S3 y pueden integrarse con Athena, Redshift o QuickSight. [Guía oficial](https://docs.aws.amazon.com/cur/latest/userguide/what-is-cur.html) |
| **AWS Budgets**                        | Servicio para definir presupuestos personalizados y recibir alertas cuando se superan límites de gasto, uso o cobertura. Permite acciones automatizadas y generación de informes. [Más información](https://aws.amazon.com/es/aws-cost-management/aws-budgets/) |


## ⏱️ Tiempos de respuesta por nivel de soporte AWS

| Nivel de soporte        | Orientación general           | Sistema afectado           | Sistema de producción afectado | Sistema de producción caído     | Sistema crítico caído           |
|-------------------------|-------------------------------|-----------------------------|-------------------------------|----------------------------------|----------------------------------|
| **Desarrollador developer**       | < 24 horas                    | < 12 horas                  | —                             | —                                | —                                |
| **Negocios bisiness**            | < 24 horas                    | < 12 horas                  | < 4 horas                     | < 1 hora                         | —                                |
| **Empresa Inicial enterprise on-ramp**     | < 24 horas                    | < 12 horas                  | < 4 horas                     | < 1 hora                         | < 30 minutos                     |
| **Empresa enterprise**             | < 24 horas                    | < 12 horas                  | < 4 horas                     | < 1 hora                         | < 15 minutos                     |

## 🛠️ Comparativa de Planes de Soporte AWS

| Plan de soporte     | Costo        | Horario de atención       | Casos recomendados                          | Trusted Advisor                     | API de soporte | Concierge Support | TAM dedicado | Soporte técnico | Programas proactivos                      |
|---------------------|--------------|----------------------------|---------------------------------------------|-------------------------------------|----------------|-------------------|--------------|------------------|-------------------------------------------|
| **Basic**           | Gratuito     | —                          | Acceso a documentación                      | No aplica                           | No             | No                | No           | No               | No aplica                                  |
| **Developer**       | Pago         | Horario laboral            | Pruebas y experimentación                   | Chequeos básicos (cuotas, seguridad)| No             | No                | No           | Email en horario laboral | Workflows AWSSupport                      |
| **Business**        | Pago         | 24/7                       | Cargas de trabajo en producción             | Chequeos completos                  | Sí             | Sí                | No           | Teléfono, email y chat 24/7 | 1 evento IEM/año, Workflows Premium       |
| **Enterprise**      | Pago         | 24/7                       | Cargas críticas o de misión empresarial     | Chequeos completos                  | Sí             | Sí                | Sí           | Soporte dedicado + TAM     | IEM, revisiones, workshops, deep dives    |

## 📘 Glosario bilingüe de soporte AWS

| Término técnico en inglés           | Definición en español                                                                 |
|------------------------------------|----------------------------------------------------------------------------------------|
| **Trusted Advisor**                | Herramienta que analiza tu entorno AWS y recomienda mejoras en seguridad, costos, rendimiento, tolerancia a fallos y límites de servicio. Apoya buenas prácticas del marco Well-Architected. |
| **AWS Support API**                | Interfaz programática que permite gestionar casos de soporte y acceder a resultados de Trusted Advisor desde tus propias herramientas. Requiere plan Business o Enterprise. |
| **Concierge Support**              | Equipo especializado que brinda asistencia personalizada en gestión de cuentas, facturación y orientación estratégica para clientes Enterprise. |
| **Technical Account Manager (TAM)**| Gerente técnico asignado que actúa como punto de contacto dedicado. Ofrece asesoría estratégica, revisiones arquitectónicas y coordinación de soporte proactivo. |
| **Proactive Programs / Servicios proactivos** | Revisiones operativas, workshops y diagnósticos especializados que anticipan problemas, optimizan cargas y mejoran la postura de seguridad. Incluidos en el plan Enterprise. |

## 🧭 Servicios Profesionales de AWS y el Marco de Adopción de la Nube (AWS CAF)

Los **Servicios Profesionales de AWS** ofrecen una serie de servicios diseñados para ayudarle a lograr resultados específicos relacionados con la **adopción empresarial de la nube**. Cada servicio incluye:

- Un conjunto de **actividades estructuradas**
- **Prácticas recomendadas** basadas en experiencia real
- **Documentación especializada** que refleja el apoyo brindado a cientos de clientes en su transición hacia AWS

Los Servicios Profesionales utilizan una **metodología única**, basada en las prácticas internas de Amazon, para ayudarle a completar proyectos de forma **más rápida y fiable**, adaptándose a:

- Expectativas cambiantes
- Estructuras de equipo dinámicas
- Ciclos iterativos de transformación

---

### 📐 Marco de Adopción de la Nube de AWS (AWS CAF)

Los Servicios Profesionales de AWS desarrollaron el **AWS Cloud Adoption Framework (CAF)** para ayudar a las organizaciones a **diseñar y acelerar** una adopción exitosa de la nube.

El marco proporciona:

- **Guía estructurada** y **prácticas recomendadas**
- Un enfoque integral para la **computación en la nube**
- Aplicación transversal en toda la organización y durante el ciclo de vida de TI

---

### 🎯 Beneficios del uso de AWS CAF

- **Aceleración** de la adopción de la nube
- **Reducción de riesgos**
- Obtención de **beneficios empresariales medibles**

---

> El uso del AWS CAF permite transformar su organización con mayor rapidez, alineando tecnología, procesos y personas hacia una adopción efectiva y sostenible de la nube.

| 🔍 Perspectiva CAF         | 🔑 Palabras clave clave                                                                 |
|---------------------------|------------------------------------------------------------------------------------------|
| Negocio (Business)        | Valor comercial, resultados, casos de negocio, retorno de inversión (ROI), alineación estratégica |
| Personas (People)         | Roles, habilidades, capacitación, gestión del cambio, cultura organizacional, liderazgo |
| Gobernanza (Governance)   | Políticas, cumplimiento, gestión de riesgos, métricas, control financiero, auditoría     |
| Plataforma (Platform)     | Arquitectura, automatización, infraestructura, escalabilidad, servicios cloud, migración |
| Operaciones (Operations)  | Monitoreo, gestión de incidentes, continuidad, procesos operativos, soporte, mejora continua |
| Seguridad (Security)      | Protección de datos, identidad, acceso, cumplimiento, cifrado, gestión de amenazas       |

## 📊 Cuadro de palabras clave por fase del AWS CAF

| 🧭 Fase CAF     | 🔑 Palabras clave clave                                                                 |
|----------------|------------------------------------------------------------------------------------------|
| **Visión** *(Envision)*     | Objetivos estratégicos, oportunidades de transformación, valor comercial, patrocinio ejecutivo |
| **Alineación** *(Align)*    | Brechas de capacidades, dependencias, gestión del cambio, preparación organizacional |
| **Lanzamiento** *(Launch)*  | Pilotos, producción inicial, validación de valor, aprendizaje iterativo, impacto medible |
| **Escalado** *(Scale)*      | Ampliación, beneficios sostenibles, evolución continua, madurez organizacional, adopción total |

## 🔐 AWS Security Hub: Definición y Casos de Uso

### 📘 Definición

**AWS Security Hub** es un servicio que centraliza y automatiza la recopilación, análisis y priorización de datos de seguridad provenientes de cuentas, servicios de AWS y herramientas de terceros. Proporciona una **visión integral del estado de seguridad**, facilita el cumplimiento normativo y permite responder de forma eficiente ante amenazas en entornos **cloud, híbridos y locales**.

---

### ✅ Casos de uso principales

| 🧩 Caso de uso                                | 📌 Descripción                                                                                   |
|----------------------------------------------|--------------------------------------------------------------------------------------------------|
| **Evaluación de cumplimiento normativo**     | Ejecuta comprobaciones automáticas basadas en estándares como CIS, PCI DSS, ISO 27001, etc.     |
| **Agregación de hallazgos de seguridad**     | Centraliza resultados de servicios como GuardDuty, Inspector, Config y herramientas externas.   |
| **Priorización de amenazas**                 | Clasifica hallazgos por severidad y permite enfocar esfuerzos en los riesgos más críticos.      |
| **Automatización de respuestas**             | Integra con Lambda, EventBridge y Systems Manager para ejecutar acciones ante hallazgos.        |
| **Visibilidad centralizada multi-account**   | Ofrece una vista unificada del estado de seguridad en múltiples cuentas y regiones.             |
| **Integración con entornos híbridos**        | Compatible con AWS Outposts y soluciones locales para una cobertura de seguridad extendida.     |

---

## 🤝 APN Consulting Partners: Definición

Los **APN Consulting Partners** son empresas que forman parte de la **Amazon Partner Network (APN)** y que ofrecen servicios especializados para ayudar a los clientes a **diseñar, desarrollar, migrar y gestionar** sus cargas de trabajo en AWS.

### 🧩 ¿Qué tipo de servicios ofrecen?
- Consultoría estratégica
- Integración de sistemas
- Servicios gestionados (MSP)
- Resellers con valor agregado

### 🎯 Objetivo
Acelerar la adopción de la nube de AWS mediante **asesoría técnica y de negocio**, aprovechando las mejores prácticas y herramientas del ecosistema AWS.

### 🌐 Ejemplos de actividades
- Migración de aplicaciones y datos
- Diseño de arquitecturas escalables y seguras
- Optimización de costos y rendimiento
- Cumplimiento normativo y seguridad

> Más del 90% de las empresas Fortune 100 utilizan soluciones y servicios de APN Partners.


## 🧱 Principios generales de diseño del AWS Well-Architected Framework

El Marco de Well-Architected identifica un conjunto de principios que facilitan el diseño de arquitecturas robustas, escalables y eficientes en la nube. Estos principios permiten aprovechar al máximo las capacidades de AWS y minimizar riesgos operativos y financieros.

---

### ⚙️ 1. Eliminar conjeturas sobre capacidad

> “No más conjeturas sobre la capacidad que necesita.”

- En lugar de aprovisionar capacidad fija, se utiliza escalado automático.
- Se evita el sobreaprovisionamiento costoso y el subaprovisionamiento que afecta el rendimiento.
- Los servicios en la nube permiten ajustar la capacidad en tiempo real según la demanda.

---

### 🧪 2. Pruebas a escala de producción

> “Prueba de sistemas a escala de producción.”

- Se pueden crear entornos de prueba bajo demanda que simulan la producción.
- Solo se paga por los recursos mientras se ejecutan las pruebas.
- Permite validar comportamientos reales sin incurrir en costos fijos elevados.

---

### 🤖 3. Automatización basada en experimentación arquitectónica

> “Automatización según la experimentación arquitectónica.”

- La automatización reduce costos y errores humanos.
- Facilita la replicación de cargas de trabajo y el rastreo de cambios.
- Se pueden auditar impactos y revertir configuraciones cuando sea necesario.

---

### 🔄 4. Arquitecturas evolutivas

> “Consideración de la posibilidad de usar arquitecturas evolutivas.”

- Las decisiones arquitectónicas ya no son eventos estáticos.
- La nube permite iterar, probar y evolucionar sistemas con bajo riesgo.
- Se facilita la adaptación a requisitos cambiantes del negocio.

---

### 📊 5. Uso de datos para impulsar decisiones arquitectónicas

> “Impulso de arquitecturas mediante el uso de datos.”

- Se recopilan métricas sobre el comportamiento de las cargas de trabajo.
- Las decisiones se basan en evidencia, no en suposiciones.
- La infraestructura como código permite aplicar mejoras de forma continua.

---

### 🎮 6. Mejora continua mediante “días de juego”

> “Mejora mediante ‘días de juego’.”

- Se simulan eventos reales para probar la resiliencia de la arquitectura.
- Se identifican oportunidades de mejora en procesos y sistemas.
- Se fortalece la experiencia organizacional en gestión de incidentes.

---

## ☁️ Ventajas del Cloud Computing según AWS

Amazon Web Services (AWS) define la computación en la nube como la distribución de recursos de TI bajo demanda a través de Internet, mediante un modelo de **pago por uso**. Estas son sus principales ventajas:

---

### 🚀 Agilidad
- Acceso inmediato a servicios como **Amazon EC2**, **Amazon S3**, **Amazon RDS**, entre otros.
- Permite experimentar, innovar y lanzar productos más rápido.

### 📈 Elasticidad
- Escalado automático de recursos con **Auto Scaling** y **Elastic Load Balancing**.
- Se adapta a picos de demanda sin aprovisionamiento excesivo.

### 💰 Ahorro de costos
- Sustitución de gastos fijos por variables: se paga solo por lo que se usa.
- Economías de escala gracias a la infraestructura global de AWS.

### 🌍 Implementación global
- Despliegue en múltiples **Regiones** y **Zonas de disponibilidad** con baja latencia.
- Servicios como **Amazon CloudFront** permiten distribución de contenido a escala mundial.

### 🔐 Seguridad
- Infraestructura diseñada según el modelo de **Responsabilidad compartida**.
- Servicios como **AWS IAM**, **AWS Shield**, **AWS KMS** y **Amazon GuardDuty** protegen datos y aplicaciones.

### 🔄 Alta disponibilidad y recuperación
- Arquitecturas resilientes con **Multi-AZ**, **Snapshots** y **Backup automatizado**.
- Servicios como **AWS Elastic Disaster Recovery** facilitan la continuidad del negocio.

### 🧠 Innovación continua
- Acceso a tecnologías avanzadas como **Amazon SageMaker** (ML), **AWS IoT Core**, **Amazon Redshift** (análisis) y más.
- Integración con más de 200 servicios gestionados.

## 🔍 Funciones del Analizador de acceso de AWS IAM (IAM Access Analyzer)

El **IAM Access Analyzer** es una herramienta de AWS que permite aplicar el principio de privilegio mínimo mediante análisis automatizados y validación de políticas. Sus funciones principales incluyen:

---

### 🛡️ 1. Identificación de acceso externo
- Detecta recursos compartidos con **entidades externas** (otras cuentas de AWS, usuarios federados, roles públicos, etc.).
- Analiza políticas basadas en recursos (como buckets de S3, roles de IAM, secretos de Secrets Manager).
- Genera resultados detallados para evaluar si el acceso es **intencionado y seguro**.

### 📘 2. Validación de políticas de IAM
- Verifica que las políticas cumplan con la **gramática de políticas JSON** y las **mejores prácticas de seguridad**.
- Incluye comprobaciones personalizadas para alinearse con estándares corporativos.
- Ayuda a evitar errores comunes como permisos excesivos o condiciones mal definidas.

### 📊 3. Generación de políticas basada en actividad
- Analiza los registros de acceso en **AWS CloudTrail**.
- Sugiere políticas refinadas basadas en el uso real de los permisos.
- Ideal para reducir el acceso no utilizado y aplicar privilegio mínimo.

---

### 🧠 Funciones adicionales
- **Análisis interno**: identifica accesos entre cuentas dentro de una organización

## 🧠 Prácticas recomendadas para crear aplicaciones en la nube en AWS

Estas prácticas están alineadas con el **AWS Well-Architected Framework** y ayudan a construir aplicaciones resilientes, escalables y eficientes en la nube.

---

### ⚠️ 1. Diseñar para el fracaso *(Design for failure)*

> Asume que los componentes pueden fallar y diseña para recuperarte automáticamente.

**Casos de uso:**
- Uso de **Auto Scaling Groups** con múltiples instancias en distintas **Zonas de disponibilidad**.
- Implementación de **Elastic Load Balancing** para distribuir tráfico y evitar puntos únicos de falla.
- Configuración de **Amazon S3 Versioning** y **Lifecycle Policies** para recuperación de datos.

---

### 🔗 2. Desacoplar componentes *(Decouple your components)*

> Separar funcionalidades permite escalar, actualizar y recuperar partes del sistema sin afectar el resto.

**Casos de uso:**
- Comunicación entre microservicios con **Amazon SQS** o **Amazon EventBridge**.
- Uso de **Amazon SNS** para notificaciones asincrónicas.
- Arquitecturas basadas en eventos con **AWS Lambda**.

---

### 📈 3. Implementar elasticidad *(Implement elasticity)*

> Ajusta automáticamente los recursos según la demanda para optimizar costos y rendimiento.

**Casos de uso:**
- Escalado automático de instancias EC2 con **Auto Scaling**.
- Uso de **AWS Lambda** para ejecución bajo demanda sin aprovisionamiento.
- Almacenamiento escalable con **Amazon S3** y **Amazon DynamoDB**.

---

### 🧮 4. Pensar en paralelo *(Think parallel)*

> Diseña procesos que puedan ejecutarse simultáneamente para mejorar eficiencia y rendimiento.

**Casos de uso:**
- Procesamiento distribuido con **AWS Step Functions** y **Lambda**.
- Análisis de datos en paralelo con **Amazon EMR** o **AWS Glue**.
- Carga masiva de objetos en **Amazon S3** usando multipart upload.
### 

## 🏢 Negocios
- Gestión de Estrategia  
- Gestión de Portafolio  
- Gestión de Innovación  
- Gestión de Producto  
- Asociación Estratégica  
- Monetización de Datos  
- Perspectivas de Negocios  
- Ciencia de Datos  

## 👥 Personas
- Evolución Cultural  
- Liderazgo Transformacional  
- Fluidez en la Nube  
- Transformación de la Fuerza Laboral  
- Aceleración del Cambio  
- Diseño Organizacional  
- Alineación Organizacional  

## 🛡️ Gobernanza
- Gestión de Programas y Proyectos  
- Gestión de Beneficios  
- Gestión de Riesgos  
- Gestión Financiera en la Nube  
- Gestión del Portafolio de Aplicaciones  
- Gobernanza de Datos  
- Curación de Datos  

## 🧱 Plataforma
- Arquitectura de Plataforma  
- Arquitectura de Datos  
- Ingeniería de Plataforma  
- Ingeniería de Datos  
- Aprovisionamiento y Orquestación  
- Desarrollo de Aplicaciones Modernas  
- CI/CD  

## 🔐 Seguridad
- Gobernanza de Seguridad  
- Aseguramiento de Seguridad  
- Gestión de Identidad y Acceso  
- Detección de Amenazas  
- Gestión de Vulnerabilidades  
- Protección de Infraestructura  
- Protección de Datos  
- Seguridad de Aplicaciones  
- Respuesta a Incidentes  

## ⚙️ Operaciones
- Observabilidad  
- Gestión de Eventos (AIOps)  
- Gestión de Incidentes y Problemas  
- Gestión de Cambios y Lanzamientos  
- Gestión del Rendimiento y Capacidad  
- Gestión de Configuración  
- Gestión de Parches  
- Gestión de Disponibilidad y Continuidad  
- Gestión de Aplicaciones  

### S3 Multipart upload API

se recomienda cuando los archivos superan los 100 MB utilizar esta opcion de s3

### IAM DENEGACION EXPLICITA
UNICA CUENTA QUE ENTRA EN AWS Y PUEDE HACER DE TODO ES la root, hay denegacion explicita para lo usuarios debajo de esa cuenta 

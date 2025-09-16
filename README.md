# AF-MICROSERVICIOS-EN-LA-NUBE
# Microservicios en la Nube (AWS, Azure, GCP) (30h)

## Objetivo
Este curso enseña a los participantes cómo desplegar, gestionar y escalar microservicios en plataformas de nube como **AWS, Azure y Google Cloud**.  
Se profundiza en herramientas como **EKS, AKS y GKE** para orquestar contenedores, así como en las prácticas de **seguridad, monitorización, alta disponibilidad y optimización de costos** para entornos distribuidos en la nube.

---

## 1. Introducción a los Microservicios en la Nube
- Introducción al concepto de microservicios y la nube.  
- Beneficios de la nube para arquitecturas de microservicios: elasticidad, escalabilidad y pago por uso.  
- Diferencias entre los servicios gestionados de AWS, Azure y Google Cloud.  
- Introducción a los contenedores en la nube y su orquestación.  

---

## 2. Despliegue de Microservicios en AWS
- **Amazon ECS (Elastic Container Service):** Configuración y gestión.  
- **Amazon EKS (Elastic Kubernetes Service):**
  - Creación de un clúster EKS.  
  - Integración de microservicios con **AWS Fargate**.  
  - Configuración de **EC2 Auto Scaling** para escalar automáticamente los nodos del clúster.  
- **AWS Lambda para microservicios serverless:**
  - Arquitecturas sin servidor con Lambda y API Gateway.  
  - Integración con **S3, DynamoDB, SNS/SQS**.  
- **Seguridad en AWS:**
  - Gestión de identidades y permisos con **AWS IAM** (Roles y políticas).  
  - Encriptación y protección de datos en tránsito y en reposo (**KMS, SSL/TLS**).  

---

## 3. Despliegue de Microservicios en Microsoft Azure
- **Azure Kubernetes Service (AKS):**
  - Creación de un clúster de AKS con escalado automático.  
  - Despliegue de microservicios en contenedores.  
  - Integración con **Azure DevOps** para automatizar el CI/CD.  
- **Azure Functions para microservicios serverless:**
  - Uso de **Triggers y Bindings** para conectar microservicios con bases de datos y colas.  
  - Comparación entre funciones sin servidor y contenedores en AKS.  
- **Configuración de Azure Networking:**
  - Creación de **redes virtuales** y seguridad con **NSG (Network Security Groups)**.  
  - Configuración de **Application Gateway** para balanceo de carga y enrutamiento.  
- **Gestión de seguridad:**
  - Uso de **Azure Active Directory (AAD)** para autenticación y autorización.  
  - Configuración de **Azure Key Vault** para gestionar secretos y claves de cifrado.  

---

## 4. Despliegue de Microservicios en Google Cloud Platform (GCP)
- **Google Kubernetes Engine (GKE):**
  - Configuración de clústeres en GKE con autoescalado.  
  - Despliegue de microservicios con contenedores.  
  - Uso de **Anthos** para entornos híbridos y multicloud.  
- **Google Cloud Run (serverless):**
  - Despliegue de contenedores directamente en Cloud Run.  
  - Optimización de recursos y reducción de costos con **autoscalado**.  
- **Bases de datos distribuidas en GCP:**
  - Uso de **Cloud Firestore** y **Cloud SQL**.  
  - Arquitectura de microservicios basada en eventos con **Google Pub/Sub**.  
- **Seguridad en GCP:**  
  - Uso de **Google Cloud IAM** para gestionar políticas y permisos.  
  - Configuración de políticas de seguridad a nivel de red y capa de aplicación.  

---

## 5. Integración y Despliegue Continuo en la Nube
- Introducción a **CI/CD en entornos multinube**.  
- **Automatización de despliegues:**
  - Uso de **AWS CodePipeline, Azure Pipelines y Google Cloud Build**.  
  - Pipeline de integración continua con testing automatizado.  
  - Estrategias de despliegue: **Blue-Green, Canary Releases, Rolling Updates**.  
- **Infraestructura como código (IaC):**
  - Uso de **Terraform** para crear y gestionar infraestructura en AWS, Azure y GCP.  
  - Automatización de despliegue y configuración de clústeres con **Ansible**.  

---

## 6. Seguridad y Monitorización de Microservicios en la Nube
- **Autenticación y autorización:**
  - Uso de **AWS IAM, Azure Active Directory y Google Cloud IAM**.  
  - Integración con sistemas de identidad y gestión de acceso (**IDP, SAML, OAuth**).  
- **Monitorización y logging:**
  - Uso de **CloudWatch (AWS), Azure Monitor y Google Cloud Operations**.  
  - Implementación de **Prometheus, Grafana y Elasticsearch** para logs, métricas y alertas.  
- **Trazabilidad y análisis de rendimiento:**
  - Uso de **Jaeger** y **OpenTelemetry** para tracing distribuido.  
  - Monitoreo de costos y optimización de recursos.  

---

## 7. Alta Disponibilidad y Recuperación ante Fallos en la Nube
- **Alta disponibilidad:**
  - Replicación de clústeres y despliegue en múltiples zonas y regiones.  
  - Estrategias de **balanceo de carga global** y resistencia ante fallos.  
- **Recuperación ante desastres (DR):**
  - Uso de **snapshots, backups automáticos y restauración de clústeres**.  
  - Simulación de fallos y pruebas de recuperación.  

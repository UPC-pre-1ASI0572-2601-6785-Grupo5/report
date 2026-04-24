# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. Design-Level EventStorming
Se llevó a cabo un proceso de Event Storming para identificar los Bounded Contexts de nuestro sistema. Durante este proceso, se siguieron los pasos que se describen a continuación:

## Collect Domain Events

Se plantean eventos importantes de todos los grupos funcionales en tiempo pasado y nomenclatura en inglés.

<img width="585" height="622" alt="image" src="https://github.com/user-attachments/assets/d63f6d4c-b6b0-4428-b2c9-c9249941d636" />

## Timeline
<img width="899" height="302" alt="image" src="https://github.com/user-attachments/assets/b106fc48-1643-4278-9595-4173b6fd6bb4" />

<img width="856" height="285" alt="image" src="https://github.com/user-attachments/assets/76c6dcde-c783-4cf1-a26c-0a017d0130d6" />

## Pain and Pivotal Points
En este paso se resaltan con un diamante los eventos por aclarar o que requieren de más conocimientos de especialistas. Por otro lado, los pivotal points son puntos de cambios que se marcan con una barra vertical. Por otro lado, los pivotal points son puntos de cambios que se marcan con una barra vertical.

<img width="881" height="358" alt="image" src="https://github.com/user-attachments/assets/bb6336e9-1fe4-406d-ba5d-171455ae246b" />

<img width="577" height="357" alt="image" src="https://github.com/user-attachments/assets/36dfe51b-8b70-47ab-b7ce-1c40e95320f1" />

#### 4.1.1.1 Candidate Context Discovery

<img width="768" height="769" alt="image" src="https://github.com/user-attachments/assets/471b6c99-3999-4d43-8442-dfc5301b5a15" />

<img width="811" height="464" alt="image" src="https://github.com/user-attachments/assets/3bbde438-aed5-40e4-bb24-b453903588cf" />

#### 4.1.1.2 Domain Message Flows Modeling
#### 4.1.1.2 Domain Message Flows Modeling
#### 4.1.1.3 Bounded Context Canvases
### 4.1.2. Context Mapping
### 4.1.3. Software Architecture
#### 4.1.3.1. Software Architecture System Landscape Diagram

![System Landscape Diagram](/assets/SystemLandscapeDiagram.png)

#### 4.1.3.2. Software Architecture Context Level Diagrams
En esta sección se presenta el diagrama de contexto de la arquitectura de software, el cual ilustra a FuelTrack en el centro de las operaciones, interactuando de manera directa con sus usuarios objetivo y los sistemas físicos (hardware) de los que depende para su funcionamiento. Este primer nivel del modelo C4 nos permite tener una visión de alto nivel del alcance del ecosistema.

![Context Level Diagram](/assets/ContextLevelDiagram.png)

#### 4.1.3.3. Software Architecture Container Level Diagrams
En esta sección se presenta el diagrama de contenedores de la solución propuesta. Este diagrama detalla los contenedores de software y sus interrelaciones, proporcionando una visión general de la estructura interna del sistema.

![Container Level Diagram](/assets/ContainerLevelDiagram.png)

#### 4.1.3.4. Software Architecture Deployment Diagrams

El diagrama de despliegue muestra cómo se distribuyen los distintos componentes de software en su entorno de ejecución. El sistema está compuesto por una aplicación web (Vue.js) y una aplicación móvil (Flutter), las cuales se ejecutan en los navegadores y dispositivos de los usuarios. Estas aplicaciones se comunican mediante JSON/HTTPS con un API Gateway en la nube, el cual enruta las peticiones hacia un clúster de microservicios (IAM, Órdenes, Vouchers e IoT Monitoring) desarrollados en Python/FastAPI. Paralelamente, en el entorno físico de las cisternas, opera una Edge Application (C++) embebida que captura los datos de los sensores y los transmite vía MQTT hacia el backend. Todos los servicios internos realizan operaciones de lectura y escritura sobre un servidor de base de datos PostgreSQL centralizado. Además, la arquitectura se integra con sistemas en la nube externos como Google Maps para validación de rutas y geocercas, y Mercado Pago para procesar las transacciones B2B.

![Deployment Diagram](/assets/DeploymentDiagram.png)

## 4.2. Tactical-Level Domain-Driven Design

### 4.2.X. Bounded Context: [Nombre del Bounded Context]
#### 4.2.X.1. Domain Layer
#### 4.2.X.2. Interface Layer
#### 4.2.X.3. Application Layer
#### 4.2.X.4. Infrastructure Layer
#### 4.2.X.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.X.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.X.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.X.6.2. Bounded Context Database Design Diagram

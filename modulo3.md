# 📘 Modulo 3

### **Introduccion a la computacion sin servidor**
Con la computacion sin servidor se puede ejecutar aplicaciones sin administrar la infraestructura subyacente.

### **Servicios administrados y sin administrar**
Con los servicios sin administrar, como Amazon EC2. AWS se encarga de la infraestructura fisica subyacente, pero el cliente es responsable de configurar, proteger y mantener el SO. Por otro lado, los servicios administrados, reducen la cantidad de procesos que deberia hacer el cliente.

### **Servicios totalmente administrados**
AWS administra completamente la infraestructura subyacente, por lo que se puede centrar solamente en escribir y desplegar codigo. Un ejemplo sera Lambda, este es un servicio de computacion sin servidor, el cual se encarga de la infraestructura, escalabilidad y disponibilidad, mientras que tu solo eres responsable de proteger y administrar el codigo de la aplicacion.

### 🚀**AWS Lambda**
Lambda es un servicio de computacion sin servidor, el cual gestiona toda la infraestructura, el escalado y la administracion de los servidores. El precio depende la cantidad de memoria que asignes a su funcion. Es ideal para procesar datos en base a eventos.

**Escala aumaticamente en funcion a las cargas**

### 🚀**Contenedores y orquestacion en AWS**

**Contenedores**
Los contenedores, es una forma eficaz de empaquetar y ejecutar aplicaciones de forma coherente en mutiples entornos, con la flexibilidad necesaria para poder escalar y desplegarlos de manera eficiente en AWS.

**Caracterisiticas:**
- Empaquetan todo lo que la aplicacion necesita para ejecutarse
- Crea un entorno uniforme
- Permite desplegar y escalar la aplicacion en cualquier lugar

**Orquestacion:**
Administran el ciclo de los contenedores, esto se basa en, inciarlos, detenerlos y ejecutarlos en un cluster. En AWS hay dos opciones para orquestar contenedores:

**Amazon Elastic Container Service (ECS)**
Es un servicio escalable de orquestacion de contenedores para ejecutar y administrar contenedores en AWS, como los contenedores Docker. Docker es un software para crear, probar y desplegar aplicaciones rapidamente.

-  Amazon ECS con Amazon EC2: Ideal para pequeñas empresas que quieren un control total de la infraestructura.
-  Amazon ECS con Fargate EC2: Ideal para empresas emergentes, es una opcion sin servidor, por lo que ECS se ocupa del escalado y orquestacion.

**Amazon Elastic Kubernets (EKS)**
Servicio ecompletamente administrado para ejecutar Kubernetes en AWS, reduce el despliegue, la administracion y el escalado de aplicaciones en contenedores mediante Kubernetes de codigo abierto.

### 🚀**Servicios de computación adicionales**



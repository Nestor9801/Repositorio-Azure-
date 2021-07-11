# Repositorio de repaso para certificación AZ-900

![Cloud](https://user-images.githubusercontent.com/54288868/125151642-439b2e80-e10d-11eb-8725-c198bb1df06d.jpg)

Este es un repositorio que nos ayudará a estudiar los conceptos de Azure para su estudio. Así mismo, cuenta con imágenes para su propia comprensión.

## Índice

* [Módulo 1: Descripción de los conceptos básicos de Azure](#módulo-1-descripción-de-los-conceptos-básicos-de-azure)
* [Módulo 2: Conceptos fundamentales de Azure](#módulo-2-conceptos-fundamentales-de-azure)
* [Módulo 3: Descripción de los componentes principales de la arquitectura de Azure](#módulo-3-descripción-de-los-componentes-principales-de-la-arquitectura-de-Azure)



## Módulo 1: Descripción de los conceptos básicos de Azure 

**Informática en la nube:** Es la prestación de servicios informáticos a través de internet. Normalmente solo se paga por los servicios 
en la nube que se usan, lo que permite:

- Reducir los costos operativos.
- Ejecutar la infraestructura de forma más eficaz.
- Escalar a medida que cambien las necesidades empresariales.



**Azure:** Es un conjunto de servicios en la nube en expansión. Ofrece la libertad de compilar, administrar e implementar aplicaciones en una red
global de masiva mediante sus herramientas y plataformas favoritas.

<p align="center">
<img src="https://user-images.githubusercontent.com/54288868/125181255-bc12f580-e1c8-11eb-8e59-6e735255a21b.png" width="500" class="center">
</p>


**Azure Portal:** Interfaz gráfica de usuario basada en web que proporciona una alternativa a la línea de comandos en la cual puede administrar una 
suscripción Azure.
 
 <p align = "center">
 <img src = "https://user-images.githubusercontent.com/54288868/125181473-a30b4400-e1ca-11eb-9e6d-c93d41956c3d.png" width="300" class="center">
  </p>

**Azure Marketplace:** Es una tienda online que contiene miles de aplicaciones de software y servicios de TI.

<p align = "center">
<img src = "https://user-images.githubusercontent.com/54288868/125204496-4435e100-e243-11eb-8bb5-e4b2015bc6f1.png" width ="300" class = "center">
 </p>
 
 ## Módulo 2: Conceptos fundamentales de Azure
 
 ### Modelos de implementacioón de informática en la nube
 
 **Nube pública:** Servicios informáticos que se ofrecen  través de la red Internet pública y están disponibles para cualquiera que quiera comprarlos. Servicios como 
 servidores y almacenamiento son propiedad de un proveedor de servicios en la nube de terceros, que los explota y los distribuye a través de Internet.
 
 **Nube privada:** Consta de recursos informáticos propios de una empresa que solo un usuario o la misma empresa usa en exclusiva, está puede estar localizada
 físicamente en un centro de datos local o estar hospedada por un porveedor de servicios de terceros.
 
 **Nube híbrida:** Una nube híbrida es un entorno informático que combina una nube pública y una nube privada, lo que permite compartir datos y aplicaciones entre 
 ellas.

### Comparación de modelos de la nube


| Nube pública | Nube privada | Nube híbrida |
| ------------- | ------------- | ------------- |
| Sin gastos de capital para escalar vericalmente| Se requiere de hardware para el inicio y mantenimiento  |  Proporciona maxima flexibilidad |
| Aplicaciones pueden aprovisionarse y desaprovisionarme rápidamente | Control total de recursos y la seguridad | Se puede determinar donde se ejecutarán las aplicaciones |
| Solo se paga por lo que se usa | Las organizaciones son responsables por del mantenimineto y actualizaciones del hardware | Se controla la seguridad, el cumplimiento o requisitos legales |

### Conceptos de ventajas de informártica en la nube

**Alta disponibilidad:** Esta en función de un nivel de acuerdo de servicio (SLA) por sus siglas en inglés. Este es un protocolo de diseño de sistemas que asegura
absoluta continuidad operacional y proporciona al usuario una experiencia continua sin tiempo de inactividad perceptible, aunque se produzcan errores.

**Escalabilidad vertical:** Aumento de la capacidad de proceso mediante la incorporación de RAM o CPU adicionales a una máquina virtual.

<p align = "center">
<img src = "https://user-images.githubusercontent.com/54288868/125206973-7fd6a800-e24f-11eb-9378-f01295f7317e.png" width ="300" class = "center">
 </p>
 
**Escalabilidad horizontal:** Aumento de la capacidad de proceso mediante la adición de instancias de recursos, como la incorporación de máquinas virtuales a la configuración.

<p align = "center">
<img src = "https://user-images.githubusercontent.com/54288868/125207085-f2478800-e24f-11eb-841f-c686e5e892f4.png" width ="300" class = "center">
 </p>
 
 <p><a href="https://www.oscarblancarteblog.com/2017/03/07/escalabilidad-horizontal-y-vertical/" target="_blank"> [Enlace]</a> Retroalimentación de escalabilidad</p>

**Elasticidad:** Capacidad que se tiene en la nube de crecer la infraestructura y los recursos de los que se dispone según las necesidades de tu empresa y así también reducirlas cuando ya no se requieran.

**Agilidad:** Alta velocidad de implemntación y configuración de los recursos basados en la nube de acuerco con los requerimientos de la aplicación.

### Gastos de capital y gastos operativos

**Gastos de capital (Capital Expenditure o CapEx):**  Inversión previa de dinero en infraestructura física, que se podrá deducir a lo largo del tiempo. El costo previo de CapEx tiene un valor que disminuye con el tiempo.

**Gastos de Operación (Operational Expenditure u OpEx):**  Es un modelo basado en el consumo. El dinero se invierte en servicios o productos y se factura al instánte.
Se paga por lo que se usa.

### Modelos de servicio en la nube

**IaaS (Infraestructre as a Service o infraestructura como servicio):** Es un modelo de servicio en la nube que es más similar a la administración de servidores físicos, un proveedor de servicios en la nube mantendrá actualizado el hardware, pero el mantenimiento del sistema operativo y la configuración de red serán su responsabilidad como inquilino de nube. 

**PaaS (Platform as a Service o Plataforma como servicio):** Este modelo de servicio en la nube es un entorno de hospedaje administrado. El proveedor de servicios en la nube administra las máquinas virtuales y los recursos de red, y el inquilino de nube implementa sus aplicaciones en el entorno de hospedaje administrado. 

**SaaS (Software as a Service o Software como servicio):** En este modelo de servicio en la nube, el proveedor de servicios en la nube administra todos los aspectos del entorno de la aplicación, como las máquinas virtuales, los recursos de red, el almacenamiento de datos y las aplicaciones. El inquilino de nube solo necesita proporcionar sus datos a la aplicación administrada por el proveedor de servicios en la nube.

<p align = "center">
<img src = "https://user-images.githubusercontent.com/54288868/125208660-77836a80-e259-11eb-8753-a66da7c3f2ec.png" width ="400" class = "center">
 </p>

### Ventajas de  modelos de servicio 

| IaaS | PaaS| SaaS|
| ------------- | ------------- | ------------- |
|Sin gastos de capital (CapEx) | Sin gastos de capital (CapEx) | Sin gastos de capital (CapEx)|
| Configuración de aplicaciones con rapidez para que sean accesibles y desaprovisionarlas cuando sea necesario | PaaS es más ágil que IaaS, y no es necesario que los usuarios configuren servidores para ejecutar aplicaciones| Los usuarios pueden proporcionar al personal acceso al software más reciente de forma fácil y rápida.|
| Modelo basaso en el consumo (OpEx)  | Modelo basaso en el consumo (OpEx) | Modelo de precio de pago por uso |
|**Flexibilidad:** IaaS es el servicio en la nube más flexible, ya que se dispone de control para configurar y administrar el hardware que ejecuta una aplicación.  | **Productividad:** Los usuarios se pueden centrar únicamente en el desarrollo de aplicaciones, ya que el proveedor de nube lleva a cabo toda la administración de plataformas. | **Flexibilidad:** Los usuarios pueden acceder  los mismos datos de la aplicación desde cualquier lugar |


### Inormática sin servidor

**Informática sin servidor:** Es un modelo de desarrollo nativo de la nube que permite que los desarrolladores diseñen y ejecuten aplicaciones sin tener que gestionar servidores. El proveedor de servicios en la nube aprovisiona, escala y administra automáticamente la infraestructura necesaria para ejecutar el código.


 ## Módulo 3: Descripción de los componentes principales de la arquitectura de Azure
 
 ### Suscripciones, grupos de administración y recursos de Azure
 
 **Recursos:** Son son instancias de servicios que puede crear, como máquinas virtuales, almacenamiento o bases de datos SQL. 
 
 **Grupos de recursos:** Contenedor lógico en el que se implementan y administran recursos de Azure como aplicaciones web, bases de datos y cuentas de almacenamiento. Es un contenedor lógico para recursos implementados en Azure
 
 **Suscripción:** Agrupa las cuentas de usuario y los recursos que han creaod las cuentas de usuario. Las organizaciones pueden usar las suscripciones para administrar los costos y los recursos creados por los usuarios, equipos o proyectos.
 
 **Grupos de administración:** Ayudan a la administración de acceso, directivas y el cumplimiento de varias suscripciones.
 
 ### Regiones de Azure y Zonas de disponibilidad
 
 **Región:** Es un área geográfica del planeta que contiene al menos un centro de datos, aunque podrían ser varios centros de datos cercanos y conectados mediante una red de baja latencia
 
 **Zonas de disponibilidad:** Son centros de datos separados físicamente dentro de una región de Azure. Una zona de disponibilidad se configura para constituir un límite de aislamiento. Si una zona deja de funcionar, la otra continúa trabajando.
 
 <p align = "center">
<img src = "https://user-images.githubusercontent.com/54288868/125212731-094ca100-e275-11eb-9c29-fdfe3c1147ba.png" width ="300" class = "center">
 </p>
 
 **Par de regiones:** Es el emparejamiento de una región Azure con otra de la misma zona geográfica, estas permite la replicación de recursos, como el almacenamiento en la máquina virtual, en una zona geográfica, lo que ayuda a reducir la probabilidad de que se produzcan interrupciones provocadas por eventos como desastres naturales, disturbios civiles, cortes del suministro eléctrico o interrupciones de la red física que afecten de forma simultánea a ambas regiones. 
 
 
 ## Recursos de Azure y Azure Resource Manager
 
 ### Grupos de recursos de Azure 
 
 **Agrupación lógica:** Proporciona orden y organización a los recursos que cree en Azure. La agrupación lógica es el aspecto que más le interesa, ya que, entre los recursos, el desorden es elevado.
 
 **Ciclo de vida:** Se refiere al tiempo determinado que un grupo de recursos está en ejecución y son útiles generalmente en desarrollo de pruebas.
 
 **RBAC (Control de acceso basado en roles):** Facilita la administración y limita el acceso para permitir solo lo que sea necesario.
 
 ## Azure Resource Manager 
 
 **Azure Resource Manager:** Es el servicio de implementación y administración para Azure. Proporciona una capa de administración que le permite crear, actualizar y eliminar recursos de la cuenta de Azure.
 
 
<p><a href="https://docs.microsoft.com/es-mx/learn/modules/azure-architecture-fundamentals/management-groups-subscriptions" target="_blank"> Suscripciones y grupos de administración de Azure</a> </p>








# ASO_TrabajoMonitorizacion

# 1  Las herramientas de monitorización de servidores.
       
## 1.1  Introducción general.
## 1.2  Las herramientas  a estudiar
           

 # 2  La herramienta XXX
 ## 2.1  Historia
 ## 2.2  Funciones/utilidades y características. Ventajas y desventajas
	
Inciga: Una plataforma para la gestión electrónica de la administración pública
Inciga es una plataforma que permite a las administraciones públicas gestionar de forma electrónica los expedientes administrativos, la tramitación de procedimientos, la comunicación con los ciudadanos, la firma electrónica y el pago electrónico.

- Funciones:

  - Gestión de expedientes: Creación, seguimiento y gestión de expedientes administrativos de forma electrónica.
  - Tramitación electrónica: Presentación de solicitudes, consulta de expedientes y recepción de notificaciones.
  - Comunicación electrónica: Envío de mensajes, solicitud de información y realización de trámites.
  - Firma electrónica: Firma electrónica de documentos.
  - Pago electrónico: Pago de tasas y otros tributos.

- Utilidades:

  - Mejora la eficiencia de la administración pública: Agiliza los trámites, reduce el tiempo de espera y los costes.
  - Mejora la transparencia: Permite a los ciudadanos acceder a la información pública de forma más fácil.
  - Mejora la participación ciudadana: Facilita la participación de los ciudadanos en la toma de decisiones.
  - Mejora la accesibilidad: Permite a los ciudadanos acceder a los servicios públicos de forma más fácil.

- Características:

  - Plataforma segura y fiable: Cumple con los más altos estándares de seguridad.
  - Fácil de usar: Tanto para la administración como para los ciudadanos.
  - Personalizable: Se puede adaptar a las necesidades de cada administración.
  - Escalable: Se puede adaptar a las necesidades de cualquier administración.

- Ventajas:

  - Mejora la eficiencia, la transparencia, la participación y la accesibilidad.
  - Plataforma segura, fácil de usar, personalizable y escalable.

- Desventajas:

  - Coste de implementación: Puede ser costosa para las administraciones.
  - Necesidad de formación: Los usuarios necesitan formación para usarla.
  - Riesgo de brecha digital: Puede aumentar la brecha entre los ciudadanos con y sin acceso a internet.
En general, Inciga es una plataforma que ofrece muchas ventajas para la administración pública y los ciudadanos. Sin embargo, es importante tener en cuenta las desventajas antes de su implementación.
 ## 2.3  Plataformas posibles donde instalar  requisitos (agentes y máquinas desde las que se monitoriza).
 ### Software:
  Para instalar Inciga y cumplir con los requisitos necesarios para la monitorización de agentes y máquinas, hay varias plataformas y sistemas operativos a considerar:

Linux (Ubuntu, CentOS, Red Hat, Debian, etc.): Inciga es compatible con varias distribuciones de Linux. Puedes instalar los agentes de Inciga en máquinas que ejecuten cualquiera de estas distribuciones Linux para monitorizar su rendimiento y estado.

Windows Server: Inciga también es compatible con entornos Windows Server. Puedes instalar agentes de Inciga en servidores que utilicen sistemas operativos Windows para monitorizar su rendimiento y salud.

Cloud Platforms (AWS, Azure, Google Cloud Platform): Puedes instalar agentes de Inciga en instancias virtuales en la nube en plataformas como AWS (Amazon Web Services), Azure o Google Cloud Platform para monitorizar el rendimiento de tus recursos en la nube.

Contenedores (Docker): Inciga puede ejecutarse dentro de contenedores Docker, lo que permite una implementación fácil y portabilidad en diferentes entornos.

Entornos virtualizados (VMware, VirtualBox, Hyper-V): Si estás utilizando entornos virtualizados, puedes instalar agentes de Inciga en las máquinas virtuales para monitorizar su rendimiento y salud.

Dispositivos de red: Además de servidores y máquinas virtuales, Inciga también puede utilizarse para monitorizar dispositivos de red como enrutadores, switches y firewalls, siempre y cuando se puedan instalar agentes o se pueda acceder a ellos a través de SNMP (Simple Network Management Protocol).
 
 ## 2.4  Requisitos tanto de agentes como de máquinas de monitoreo.
 Los requisitos mínimos de hardware y software para Inciga pueden variar dependiendo de la cantidad de recursos que desees monitorear y la escala de tu implementación. Sin embargo, aquí hay una lista general de requisitos mínimos típicos para instalar y ejecutar Inciga:

- Requisitos de hardware:

  - CPU: Procesador de doble núcleo o superior.
  - RAM: 2 GB de RAM como mínimo. Se recomienda 4 GB o más para entornos de monitoreo más grandes.
  - Almacenamiento: Espacio suficiente en disco para instalar el software y almacenar los datos de monitoreo. Generalmente, se recomienda al menos 20 GB de espacio en disco.
  - Red: Conexión de red estable y suficiente ancho de banda para enviar y recibir datos de monitoreo.
- Requisitos de software:

  - Sistema Operativo: Inciga es compatible con una variedad de sistemas operativos, incluyendo diferentes distribuciones de Linux (como Ubuntu, CentOS, Red Hat) y Windows Server. Asegúrate de que estás utilizando una versión compatible del sistema operativo.
  - Java: Inciga requiere Java Runtime Environment (JRE) para ejecutarse. Asegúrate de tener instalada una versión compatible de Java en tu sistema.
  - Base de datos: Inciga utiliza una base de datos para almacenar datos de monitoreo. Puedes usar MySQL, PostgreSQL o Microsoft SQL Server como base de datos backend. Asegúrate de tener instalada y configurada una base de datos compatible.
 ## 2.5  Esquema de Red (entorno). Máquinas, dirección de la red, IP’s, S.O. de las máquinas, servicios instalados. 
- Escenario/esquema de red:  especificar todo (IP, SO, sw instalado, etc)
Nota: Indicar posibles escenarios, p.ej en  Zabbix hay 3 escenarios posibles: Agent, Agent-less y Agent con proxy
## 2.6  Instalación y configuración en máquinas a monitorizar.
- Instalación : indiquen las versiones de toda la paquetería que instalan. (captura de pantalla de systemctl -status de cada servicio)
o  mediante script en las máquinas de la red a monitorizar.

# 3. Instalación y configuración en máquinas a monitorizar (agentes) y remotas.
 ## 3.1  Instalación y configuración en agentes 
 ## 3.2  Diseño de pruebas.  Decisión de servicios a monitorizar
 ## 3.3  Puesta en marcha (pruebas) y ejemplo de uso.

 # 4  [Otros puntos a investigar según la herramienta]

    • Instalación mediante script en las máquinas de la red a monitorizar.
    • Monitorización remota por SSH  o en consola. 
    • Monitorización usando el navegador web.Alerta a usuario 
    • Tarea programada (si procede) en cron.
    • Otros usos: proxy, etc 

 # 5  Conclusiones y problemas encontrados 
 Conclusiones tras conocer la herramienta. Indicar también problemas (y cómo se han solventado).


 # 6  OPCIONAL --- Comparativa con otras herramientas (trabajo de otro equipo)
 ## 6.1   Funciones/utilidades y características. Ventajas y desventajas
 ## 6.2   Plataformas y  requisitos.
 ## 6.3  Conclusión tras la comparativa (si lo consideras necesario)

 # 7  Bibliografía


# ANEXO. Desarrollo del proyecto con SCRUM
## I. Equipo y roles
## II. Reuniones realizadas (events)
## III. Documentos: 
- link al backlog del equipo  -- no olvidar compartir con mctripiana@iesgrancapitan.org --
- Añadir (compartir en drive, link) cualquier otro documento que sea necesario
           
           

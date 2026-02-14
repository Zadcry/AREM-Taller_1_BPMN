#  Informe Técnico del Taller

##  Nombre del Taller
Taller 1 - Modelado del proceso del cliente con BPMN

## Integrantes del equipo
- Julián Mauricio Zafra (julianzamo@unisabana.edu.co)
- Camilo Arciniegas Guerrero (camiloarcgu@unisabana.edu.co)
- Santiago Andrés Araque (santiagoaral@unisabana.edu.co)
- Juan Diego Campo (juancamco@unisabana.edu.co)
- Juan Sebastián Ayala (juanaysi@unisabana.edu.co)
- Juan José Forero (juanfope@unisabana.edu.co)

##  Descripción general del trabajo

Para este proyecto trabajamos con el análisis de un proceso real perteneciente a un
gimnasio especializado en la práctica de parkour. Este proceso describe la forma en que se
gestionan las clases mensuales, desde la selección y pago por parte de los clientes hasta el
control de asistencia y cierre del período.


## 🔧 Proceso de desarrollo
Explique cómo realizaron el trabajo: qué decisiones tomaron, qué herramientas utilizaron, qué aspectos modelaron primero y cómo lo fueron ajustando.

##  Análisis del modelo propuesto

El proceso actual de gestión de clases del gimnasio involucra tres actores principales:
• Clientes
• Gimnasio (personal administrativo y entrenadores)
• Sistema de registro (archivo Excel)
Flujo del proceso:
1. Selección y pago del plan

* Durante los primeros 5 días del mes, los clientes deciden cuántas clases
tomarán.
 
* Realizan el pago correspondiente al número de clases.

2. Registro manual del pago
* El gimnasio recibe el pago.
* El personal ingresa manualmente en un archivo Excel:
* nombre del cliente
* número de clases adquiridas
3. Asistencia a clases
* El cliente asiste a una clase.
* El entrenador imparte la clase.
4. Registro de asistencia
* Al finalizar la clase, el personal registra en el Excel:
* qué clientes asistieron
* se descuenta automáticamente una clase del saldo disponible
* se adjunta una fotografía como evidencia de asistencia
5. Cierre mensual
Al finalizar el mes:
* las clases no utilizadas se eliminan
* El Excel se reinicia para el siguiente período
El proceso actual maneja de manera simple el control de asistencia y permite llevar un
seguimiento básico del uso de las clases adquiridas por los clientes. Además, incluye un
descuento automático de las clases disponibles, lo que facilita conocer el saldo restante
de cada usuario.
Sin embargo presenta falencias importantes, destacando la gestión manual en varios
momentos del proceso, esto incrementa el riesgo de inconsistencias, omisiones y errores
humanos generando posibles problemas futuros relacionados con la seguridad y la
perdida de información.

### Diferencias con el caso visto en clase (Clínica Salud Viva):

Inicialmente vemos una gran diferencia en cuanto a la automatización, donde la clínica
tiene un nivel bastante alto comparado con el del gimnasio. La Clínica Salud Viva cuenta
con una plataforma digital que permite a los pacientes agendar citas médicas, recibir
notificaciones y consultar su historial de atención. En cambio, el gimnasio gestiona todo el
proceso mediante un archivo Excel y registros manuales, sin validaciones automáticas ni
comunicación digital con los usuarios.
También se evidencia una diferencia en la gestión de la información y la trazabilidad. En la
clínica, cada paso del proceso queda registrado digitalmente, permitiendo consultar
historiales y mantener un seguimiento estructurado del paciente. En el gimnasio, aunque se
lleva un control de asistencia y evidencia fotográfica, la información está limitada a un
registro mensual que se reinicia al finalizar el período, lo que impide un historial
acumulativo de largo plazo.
A continuación, se ve una tabla comparativa entre ambos procesos:

<img width="752" height="425" alt="image" src="https://github.com/user-attachments/assets/a7e287d1-0473-4500-8a4a-f32c14c0118a" />

El proceso del gimnasio puede mejorar mediante la implementación de un sistema digital
que automatice el registro de pagos, el control de asistencia y la generación de reportes.
Además, el envío de notificaciones y la posibilidad de reservar clases ayudarían a mejorar
la organización y la experiencia del cliente. Mantener un historial acumulativo y centralizar
la información también reduciría errores y aumentaría la eficiencia administrativa.

##  Diagrama final entregado

![Diagrama final](https://github.com/user-attachments/assets/4da4d37a-0a68-4a7e-8d13-afe303c8ce4b)



##  Tabla de actores, entidades o componentes (si aplica)

| Nombre del elemento | Tipo | Descripción | Responsable |
|---------------------|------|-------------|-------------|
| Ej: Paciente        | Actor | Usuario que agenda una cita médica | Cliente |

##  Investigación complementaria

### Tema investigado:

### Buenas prácticas en BPMN

Según el artículo _BPMN Best Practices_[1], los modelos BPMN deberían seguir las siguientes reglas y prácticas:

**1. Empieza con un objetivo claro**: Tener el objetivo claro desde el principio permite asegurarse que el modelo está alineado con los objetivos de la organización o proyecto.

**2. Mantenlo simple**: Usa solo los elementos necesarios y evita complejidad innecesaria para que sean claros y fáciles de mantener. 

**3. Usa notación consistente**: Utiliza siempre los mismos símbolos y reglas de notación para mantener claridad y coherencia.

**4. Prueba tus modelos**: Realiza tests y simula el proceso para detectar errores y mejorar su funcionamiento antes de implementarlo.

**5. Mejora tu modelo continuamente**: Revisa y optimiza constantemente tus procesos BPMN usando datos para mantener eficiencia y mejora continua.

### TOGAF Versus C4

### TOGAF

Es un marco de la arquitectura empresarial que tiene el objetivo de apoyar a las empresas en la planeación, diseño e implementación de su arquitectura de manera organizada. Para llevar a cabo este marco de arquitectura, se utiliza la ADM (Architecture Development Method), una metodología formal para guiar la construcción y el mantenimiento de la arquitectura de la empresa u orgaanización. [2]

### C4

El modelo C4 es una técnica de notación gráfica utilizada para modelar la estructuración de la arquitectura de sistemas de software. Se basa en la representación visual de la estructura del sistema con diferentes niveles de abstracción, desde el contexto más general hasta el código, pasando por contenedores, componentes y código. Se centra principalmente en hacer que las arquitecturas de sistemas de software sean claramente visibles y comprensibles.[3]

### Diferencias entre ambos modelos

* TOGAF se enfoca en como gestionar la arquitectura empresarial, mientras que C4 se especializa en dar una representación visual de la arquitectura de software.
* Los usuarios de TOGAF son generalmente arquitectos empresariales, mientras que los usuarios de C4 son arquitectos de software.
* TOGAF cubre el apartado de negocio, datos y aplicaciones. C4 cubre sistemas, componentes y código.

### ¿Qué es el modelo STRIDE?

Es una herramienta estructurada que tiene el objetivo de identificar amenazas de seguridad en sistemas de software. Las amenazas se clasifican principalmente en seis categorías[4]:

**1. Spoofing:** Un atacante se hace pasar por otro usuario  para obtener acceso no autorizado. 

**2. Tampering:** Alteración no autorizada de datos, código o recursos del sistema.

**3. Repudiation:** Situación en la cual un usuario puede negar haber realizado una acción y no existen pruebas suficientes para demostrarlo.

**4. Information Disclosure:** Exposición de datos sensibles a usuarios no autorizados.

**5. Denial Of Service:** Ataques que impiden a los usuarios legítimos acceder a recursos o servicios.

**6. Elevation of Privilege:** Un atacante obtiene permisos más elevados de lo que debería, permitiéndole ejecutar acciones restringidas.

Gracias a esta clasificación, el equipo de seguridad de software puede anticiparse a riesgos y aplicar mitigaciones apropiadas durante el ciclo de vida del desarrollo.

En resumen, el modelo STRIDE permite analizar la seguridad de un sistema de forma preventiva, ayudando así a identificar vulnerabilidades en el desarrollo para que no lleguen al resultado o producto final. La clasificación de las amenazas en seis categorías claras permite la implementación de controles de seguridad desde las primeras fases de diseño del sistema, de esta forma, se reducen los riesgos y se fortalece la seguridad del sistema.


### Resumen:

En la investigación complementaria se abordaron buenas prácticas del modelo BPMN, así como enfoques de arquitectura TOGAF, el modelo C4 y el modelo STRIDE para identificar amenazas. Las buenas prácticas en BPMN resaltan la importancia de tener un objetivo claro desde el principio, mantener la simplicidad y validar los modelos antes de pasarlos a una etapa más avanzada. Finalmente, STRIDE identifica vulnerabilidades y amenazas de seguridad clasificándolas en seis categorías, permitiendo implementar controles preventivos desde la fase de diseño.

Estos marcos de arquitectura evidencian puntos clave con lo realizado en el presente taller. Ver el gym por medio de BPMN fue más que dibujar pasos y roles, abrió espacio para pensar cambios reales. La claridad llegó cuando se usaron reglas simples al diseñar el esquema. Saber qué separa TOGAF de C4 muestra mejor hasta dónde podría crecer ese sistema. El uso del marco STRIDE reveló peligros poco vistos: datos extraviados, archivos modificados sin control, ausencia de seguimiento claro. Todo junto da una mirada completa. No se trata solo de movimientos encadenados. Se convierte en pieza dentro de una estructura mayor, lista para avanzar hacia formatos digitales estables, ordenados, protegidos.

##  Referencias
- [1] BPMN Best Practices. (s. f.). BPMN.page. Recuperado de https://bpmn.page/article/BPMN_Best_Practices.html
- [2] The Open Group, TOGAF® Standard, 10th Edition, 2022. [En línea]. Disponible en: https://www.opengroup.org/togaf
- [3] Visual Paradigm, Desvelando el poder del modelo C4: Simplificando los diagramas de arquitectura de software – Visual Paradigm Blog Español. [En línea]. Disponible en: https://blog.visual-paradigm.com/es/unveiling-the-power-of-c4-model-simplifying-software-architecture-diagrams/
- [4] Microsoft, “Threat modeling tool – STRIDE per element,” Microsoft Learn. [En línea]. Disponible en: https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool-threats

---

_Este documento hace parte de la entrega del taller X del curso AREM (Arquitectura Empresarial) - Universidad de La Sabana._

# 📄 Informe Técnico del Taller

## 🔖 Nombre del Taller
_Taller X - [Nombre completo del taller]_

## Integrantes del equipo
- Julián Mauricio Zafra (pongan su correo)
- Camilo Arciniegas (pongan su correo)
- Santiago Araque (pongan su correo)
- Juan Diego Campo (juancamco@unisabana.edu.co)
- Juan Sebastián Ayala (juanaysi@unisabana.edu.co)
- Juan José Forero (ponganle el correo)

## 🧠 Descripción general del trabajo
Describa brevemente el objetivo del taller y cómo se desarrolló la actividad.

## 🔧 Proceso de desarrollo
Explique cómo realizaron el trabajo: qué decisiones tomaron, qué herramientas utilizaron, qué aspectos modelaron primero y cómo lo fueron ajustando.

## 🧩 Análisis del modelo propuesto
Incluya un análisis sobre:
- Cómo se estructura el modelo entregado
- Cómo representa las necesidades del cliente
- Qué supuestos se tomaron

## 📈 Diagrama final entregado
> (Inserte aquí una imagen o enlace al modelo-final.drawio / .asta / PDF)

## 📋 Tabla de actores, entidades o componentes (si aplica)

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
Describa en 2–3 párrafos lo investigado, citando fuentes cuando sea necesario. Incluya cómo se relaciona con el taller.

## 📚 Referencias
- [1] BPMN Best Practices. (s. f.). BPMN.page. Recuperado de https://bpmn.page/article/BPMN_Best_Practices.html
- [2] The Open Group, TOGAF® Standard, 10th Edition, 2022. [En línea]. Disponible en: https://www.opengroup.org/togaf
- [3] Visual Paradigm, Desvelando el poder del modelo C4: Simplificando los diagramas de arquitectura de software – Visual Paradigm Blog Español. [En línea]. Disponible en: https://blog.visual-paradigm.com/es/unveiling-the-power-of-c4-model-simplifying-software-architecture-diagrams/
- [4] Microsoft, “Threat modeling tool – STRIDE per element,” Microsoft Learn. [En línea]. Disponible en: https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool-threats

---

_Este documento hace parte de la entrega del taller X del curso AREM (Arquitectura Empresarial) - Universidad de La Sabana._

[necesidades_usuario (1).md](https://github.com/user-attachments/files/24929070/necesidades_usuario.1.md)
# Práctica 1.
> Integrantes:
- **Amaya Pineda, Marlon Javier**
- **Escobar Hernandez, Roberto Carlos**
- **Hidalgo Barahona, Sergio Hidalgo**
- **Alvaro Sebastian Jordan Lopez**

# Introducción al caso.
Una pequeña empresa que consta de 25 empleados necesita mejoras urgentes a su sistema actual, el cual presenta inconvenientes significativos a la operación de la misma:

- **Lentitud en el sistema**: Los usuarios reportan que toma mucho tiempo realizar cualquier tarea y retrasa sus operaciones.
- **Pérdida de archivos**: La permanencia de información se ve seriamente comprometida, con archivos desapareciendo del almacenamiento regularmente.
- **Caídas frecuentes del sistema**: El sistema se vuelve inaccesible y pausa las operaciones de la empresa por longitudes de tiempo considerables.

# Situaciones problemáticas y necesidades.

De acuerdo a los problemas expresados por los usuarios de la empresa, sus necesidades se resumen en las siguientes:

|Necesidad|Tipo|Clasificación|Justificación|
|--|--|--|--|
| Los usuarios reportan dificultades para trabajar con el sistema debido a constantes interrupciones por largos tiempos de espera. | Explícita | Operativa | Los tiempos de respuesta afectan directamente el desempeño de los usuarios y todo trabajo realizado dentro de la empresa. |
| El acceso a los archivos es poco confiable y los usuarios reportan que algunos archivos no son accesibles y se pierden después de un tiempo. | Explícita | Operativa| Se deben preservar los archivos e información críticos de la empresa. |
| Con frecuencia los usuarios pierden conexión al sistema, pausando su trabajo por lapsos de tiempo inaceptables. | Explícita | Operativa | Las consecuencias impactan directamente al cumplimiento de tareas y continuidad del negocio. |
| Se debe analizar el sistema desde su implementación de software, su configuración y el entorno informático que le rodea para determinar la fuente de la lentitud percibida por los usuarios y optimizar. | Implícita | Técnica | Se ve reflejado en la optimización de diversos componentes del sistema. |
| Se debe asegurar la integridad y evitar pérdida de la información, ya que la pérdida de archivos puede ser un gran riesgo. | Implícita | Técnica | Se relaciona a los procesos de manejo, protección e integridad de la información. |
| Se debe asegurar que la conexión al sistema permanezca estable y accesible, ya que los usuarios reportaron desconectarse constantemente. | Implícita | Técnica | Puede llegar a requerir varios cambios, grandes y pequeños, en la infraestructura informática. |
| Es necesario crear documentación del funcionamiento del sistema y todos los cambios o arreglos que se realicen, ya que la empresa necesita claridad sobre estos asuntos para dar mantenimiento a largo plazo a su sistema. | Implícita | Operativa | Facilita la comunicación entre los responsables del mantenimiento y posibles expansiones futuras del sistema. |

# Requerimientos iniciales.

| Requerimiento | Necesidad | Clasificación | Justificación |
|--|--|--|--|
| El sistema debe mantenerse disponible durante 99% de la jornada laboral  | Asegurar conexión estable al sistema | No funcional | Las interrupciones por cantidades considerables de tiempo afectan severamente la productividad de la empresa. |
| El sistema debe asegurar redundancia en el almacenamiento de archivos con una implementación que se adapte a las necesidades de la empresa | Pérdida de archivos | No funcional | La continua persistencia de información almacenada es integral para el funcionamiento de una empresa. |
| El sistema debe permitir el trabajo fluido y constante | Lentitud del sistema | Funcional | La fluidez y respuesta rápida del sistema beneficia el rendimiento de la empresa. |
| La información almacenada debe mantenerse íntegra y disponible | Protección de la información | Funcional | La coherencia y confiabilidad de la información disponible es sumamente importante. |
| Los responsables del sistema deben contar con información sobre el funcionamiento del sistema | Falta de documentación | Funcional | Para el funcionamiento y mantenimiento del sistema a largo plazo, detalles de su funcionamiento y uso deben ser documentados para la posteridad. |


# Resumen


Capitulo 3

Subrutinas y paso de parámetros
En el contexto de Raspberry Pi, las subrutinas y el paso de parámetros se utilizan para controlar hardware, interactuar con sensores, manejar eventos y realizar una variedad de tareas programáticas.
La forma en que se definen y utilizan las subrutinas y se pasan los parámetros puede variar según el lenguaje de programación específico que estés utilizando en tu proyecto Raspberry Pi.

E/S a Bajo Nivel
La E/S (Entrada/Salida) a bajo nivel se refiere a la interacción con dispositivos de hardware, como puertos, periféricos y archivos, directamente a nivel de código en lenguajes de programación. Esto implica un mayor control y eficiencia, pero también una mayor complejidad en la programación.





Capitulo 4

Ventajas de la E/S a Bajo Nivel
Control total: Permite un control preciso sobre el hardware, lo que es útil en aplicaciones de tiempo real y sistemas embebidos.

Rendimiento: Las operaciones de E/S a bajo nivel suelen ser más rápidas, ya que no involucran capas de abstracción.

Acceso directo al hardware: Permite interactuar con puertos, controladores y registros de hardware.

Desventajas de la E/S a Bajo Nivel
Complejidad: Requiere un conocimiento profundo del hardware y una programación más detallada.

Portabilidad limitada: Los programas escritos para E/S a bajo nivel pueden no ser portables a través de diferentes sistemas o arquitecturas.

Operaciones Comunes de E/S a Bajo Nivel
Lectura y escritura de registros de hardware: Acceso directo a registros de control de dispositivos.

Programación de puertos de E/S: Configuración y manipulación de puertos para la comunicación con periféricos.

Mapeo de memoria de dispositivos: Asignación de direcciones de memoria para interactuar con dispositivos.

Acceso a registros de interrupciones: Control de eventos y manejo de interrupciones.

Lenguajes y Plataformas
C y ensamblador: Lenguajes comunes para la programación de E/S a bajo nivel debido a su capacidad de acceso directo a la memoria y al hardware.

Sistemas embebidos y microcontroladores: Donde la E/S a bajo nivel es fundamental para el funcionamiento del hardware.

Sistemas operativos: Los sistemas operativos interactúan con hardware a bajo nivel para administrar recursos y proporcionar servicios a aplicaciones.

Consideraciones de Seguridad
La programación de E/S a bajo nivel puede ser riesgosa si no se maneja con cuidado, ya que los errores pueden tener consecuencias graves. Es importante tomar medidas para garantizar la seguridad y estabilidad de los sistemas.

En resumen, la E/S a bajo nivel implica interactuar directamente con el hardware de un sistema, lo que proporciona un mayor control y rendimiento, pero también requiere un conocimiento profundo del hardware y conlleva riesgos de seguridad.





Capitulo 5

Interrupciones hardware

Interrupciones de Hardware
Las interrupciones de hardware son eventos generados por dispositivos de hardware que requieren la atención inmediata del procesador de una computadora. Estas interrupciones permiten que el sistema operativo y las aplicaciones respondan de manera eficiente a eventos externos sin necesidad de realizar sondeos continuos. Aquí se resumen los conceptos clave relacionados con las interrupciones de hardware:

Función de las Interrupciones
Las interrupciones de hardware desempeñan un papel crucial en los sistemas informáticos:

Notificación de eventos: Los dispositivos hardware, como periféricos o controladores, generan interrupciones para notificar al procesador acerca de eventos importantes, como la finalización de una operación de E/S o la detección de un error.

Manejo de eventos asíncronos: Las interrupciones permiten manejar eventos asíncronos, lo que significa que no es necesario que el procesador esté constantemente monitoreando el estado de los dispositivos.

Eficiencia y multitarea: Las interrupciones mejoran la eficiencia y la multitarea al permitir que el procesador atienda eventos en un orden de prioridad sin bloquear la ejecución de otras tareas.

Componentes Clave
Controlador de Interrupciones: Hardware dedicado o circuitos dentro del procesador que gestiona las interrupciones. Puede priorizar, enmascarar (desactivar) o habilitar interrupciones.

Vector de Interrupción: Una tabla que mapea cada número de interrupción a una rutina de manejo específica. Cuando ocurre una interrupción, el procesador busca la dirección de la rutina correspondiente en el vector.

Rutinas de Manejo: Pequeños programas o funciones que se ejecutan en respuesta a una interrupción específica. Realizan tareas de manejo, como guardar y restaurar registros, y atender el evento.

En resumen, las interrupciones de hardware son eventos generados por dispositivos que permiten una respuesta eficiente a eventos importantes en un sistema informático. Se gestionan mediante controladores de interrupciones, tablas de vectores y rutinas de manejo, y son esenciales para la multitarea y la eficiencia de los sistemas.

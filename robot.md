## Especificaciones de los robots

Cada equipo participante recibirá **dos robots tipo rover**, construidos a partir de una versión modificada de la plataforma educativa Sumobot. Ambos robots deberán trabajar de manera coordinada para localizar, recolectar y transportar objetos cúbicos dentro del espacio de competencia.

### Plataforma base

Los robots utilizarán la plataforma oficial Sumobot proporcionada por la organización. La tarjeta electrónica principal y el microcontrolador incluidos en el robot deberán mantenerse como el núcleo del sistema de control.

No se permite:

* Sustituir la tarjeta electrónica principal.
* Cambiar el microcontrolador original.
* Utilizar otra tarjeta de desarrollo como controlador principal.
* Reemplazar completamente la plataforma por otro robot comercial o construido desde cero.

Sí se permite modificar el código, agregar sensores, incorporar módulos auxiliares y construir mecanismos físicos conectados a la plataforma original.

### Capacidades de movimiento

Cada robot contará con un sistema de locomoción diferencial compuesto por dos motores independientes. Esto permitirá ejecutar movimientos como:

* Avance y retroceso.
* Giro sobre su propio eje.
* Correcciones de trayectoria.
* Aproximación a objetos.
* Transporte o empuje de cubos.
* Navegación coordinada con el segundo robot.

Los equipos deberán desarrollar el software de control necesario para convertir las instrucciones generadas por el sistema de navegación en movimientos precisos del rover.

### Comunicación inalámbrica

Los robots podrán comunicarse entre sí mediante **ESP-NOW** u otro mecanismo inalámbrico compatible con la plataforma oficial.

La comunicación podrá utilizarse para:

* Distribuir tareas entre los robots.
* Compartir estados y posiciones.
* Evitar colisiones.
* Informar sobre objetos localizados.
* Confirmar la recolección o entrega de un objeto.
* Coordinar movimientos simultáneos.

Los robots también podrán recibir instrucciones desde una computadora central, siempre que estas sean generadas y transmitidas automáticamente.

### Identificación mediante visión global

Cada rover deberá incorporar un marcador visual que permita al sistema de visión global determinar:

* La identidad del robot.
* Su posición dentro de la superficie.
* Su orientación.
* Su trayectoria.
* Su cercanía a obstáculos, cubos y otros robots.

Los marcadores podrán utilizar colores, patrones geométricos, códigos ArUco u otro sistema de identificación visual autorizado por la organización.

### Sistema de recolección

Los equipos podrán diseñar o modificar mecanismos simples para manipular los objetos cúbicos.

Entre los mecanismos permitidos se encuentran:

* Palas.
* Empujadores.
* Pinzas.
* Brazos simples.
* Guías laterales.
* Compartimentos de transporte.
* Mecanismos accionados mediante microservos.

El mecanismo deberá ser de bajo costo, seguro y compatible con las dimensiones y capacidades del robot base.

### Sensores y componentes adicionales

Se permitirá agregar componentes que complementen la información proporcionada por la cámara global, incluyendo:

* Sensores ultrasónicos.
* Sensores infrarrojos.
* Sensores de distancia.
* Sensores de color.
* Encoders.
* Microservos.
* Reguladores de voltaje.
* Indicadores luminosos.
* Soportes y piezas impresas en 3D.
* Cableado, conectores y módulos auxiliares.

Los componentes adicionales no podrán sustituir el sistema principal de control del robot.

### Procesamiento externo

La percepción global y la planificación podrán ejecutarse en una computadora externa conectada a la cámara superior.

Esta computadora podrá:

* Procesar las imágenes de la superficie.
* Detectar los robots y objetos.
* Estimar posiciones y orientaciones.
* Construir un mapa del entorno.
* Calcular rutas.
* Asignar tareas a cada robot.
* Transmitir comandos de movimiento.
* Verificar y corregir las trayectorias durante la ejecución.

La computadora externa funcionará como centro de coordinación, pero los movimientos deberán ejecutarse sin intervención humana directa.

### Autonomía

Una vez iniciada la prueba, los robots deberán operar de manera completamente autónoma.

No se permitirá:

* Controlar los robots con teclado, teléfono o control remoto.
* Mover manualmente los robots.
* Reubicar objetos durante la ejecución.
* Enviar instrucciones humanas.
* Modificar o reprogramar el sistema después de iniciar la prueba.

Antes de la competencia se permitirá realizar procesos de calibración, verificación de comunicación y ajuste del sistema de visión.

### Restricción de modificaciones

Las modificaciones físicas y electrónicas realizadas sobre cada robot no podrán superar un costo total de **US$50 por robot**.

Esta restricción busca mantener condiciones equivalentes entre los equipos y favorecer soluciones basadas en diseño mecánico, programación, visión por computadora y coordinación algorítmica, en lugar de depender de componentes especializados de alto costo.

## Entrega de robots y materiales

La organización entregará a cada equipo participante, **sin costo**, los robots y los materiales base necesarios para desarrollar el reto.

El kit podrá incluir:

* Dos robots tipo rover basados en la plataforma Sumobot.
* Tarjetas electrónicas y microcontroladores.
* Motores y sistema de locomoción.
* Baterías o sistemas de alimentación compatibles.
* Marcadores para identificación visual.
* Objetos cúbicos utilizados en las pruebas.
* Componentes mecánicos y electrónicos básicos.
* Materiales para la construcción de mecanismos de recolección.
* Acceso al espacio de prueba y al sistema de visión global.
* Documentación técnica y ejemplos iniciales de programación.

Los equipos no deberán pagar por la inscripción, los robots ni los materiales oficiales entregados para participar.

Cualquier componente adicional que un equipo desee incorporar deberá cumplir las reglas técnicas, el límite de costo y los criterios de seguridad establecidos por la organización.

## Responsabilidad de los equipos

Cada equipo será responsable de:

* Programar los dos robots.
* Desarrollar el sistema de visión y navegación.
* Diseñar la estrategia de coordinación.
* Construir o adaptar el mecanismo de recolección.
* Documentar las modificaciones realizadas.
* Mantener un registro del costo de los componentes adicionales.
* Entregar el código fuente y la documentación técnica.
* Presentar una demostración autónoma y funcional.

Los robots y materiales proporcionados deberán utilizarse exclusivamente para el desarrollo y ejecución del reto, siguiendo las normas de seguridad y uso definidas por la organización.

# Análisis y Diseño

Construir software sin planificar es como levantar una casa sin planos ni instrucciones: un error que solo genera caos, retrasos y resultados inservibles. La improvisación nunca sustituye a un buen diseño previo.

## ¿Qué es un análisis?

Un análisis es entender problemas antes de que sucedan, es saber quiénes usarán el sistema, qué se necesita, qué información maneja y qué restricciones existen.

## ¿Qué es el diseño?

Diseñar es planificar la solución antes de construirla, definiendo cómo se organizará el sistema, qué tecnologías se usarán y cómo interactuará el usuario con el producto final. Es el plano previo que asegura que todas las piezas encajen correctamente.

## Ciclo de vida del software

El ciclo de vida del software es el conjunto de etapas que atraviesa un sistema desde su idea inicial hasta que queda obsoleto y se deja de usar. Es un proceso similar al de un ser vivo, ya que el programa nace, crece, madura con nuevas versiones y finalmente muere.

1. **Análisis de Requerimientos:** Es la fase más crítica; se habla con el cliente para entender y documentar con precisión todo lo que el sistema debe hacer.
2. **Diseño:** Se define la arquitectura del software, creando los planos, diagramas y prototipos de las interfaces y bases de datos.
3. **Implementación:** Los programadores traducen los diseños anteriores en código real utilizando lenguajes de programación.
4. **Pruebas:** Se verifica a fondo el correcto funcionamiento del sistema para detectar y corregir cualquier tipo de error.
5. **Despliegue:** Se entrega el software terminado al cliente y se pone en funcionamiento en un entorno real para los usuarios.
6. **Mantenimiento:** Se corrigen los fallos que surjan con el uso cotidiano y se añaden nuevas funciones según las necesidades futuras.

## Metodología tradicional

Las metodologías estructuradas se basan en planificar todo meticulosamente antes de actuar, siguiendo un plan rígido de principio a fin. Funcionan como la construcción de un puente: requieren conocer cada detalle y requisito de antemano para evitar cambios durante la ejecución.

## Revolución ágil

En 2001, diecisiete desarrolladores frustrados por la rigidez tradicional desarrollaron el método ágil, que transformó el método para desarrollar por su flexibilidad y la adaptación que brinda.

### SCRUM

* **Sprints:** Ciclos de trabajo de 1 a 4 semanas con objetivos muy concretos.
* **Daily standups:** Reuniones diarias de 15 minutos para repasar lo hecho ayer, las tareas de hoy y los posibles bloqueos.
* **Roles esenciales:** El Product Owner (define qué se construye), el Scrum Master (elimina obstáculos y protege al equipo) y el Equipo de desarrollo (programa el producto).
* **Demo:** Presentación final al cliente con los avances reales construidos durante el sprint.
* **Retrospectiva:** Espacio de discusión del equipo enfocado en la mejora continua del proceso de trabajo.

### XP

* **Programación en pares:** Dos personas en una computadora; una escribe y la otra revisa al mismo tiempo.
* **TDD:** Crear primero la prueba y después programar el código que la supere.
* **Refactorización:** Limpiar y mejorar el código por dentro sin cambiar cómo funciona por fuera.
* **Entregas frecuentes:** Lanzar actualizaciones pequeñas y seguidas para reducir errores.

## Comparación de los dos métodos

Aquí tienes la comparación directa en el formato que pides:

### Planificación
* **Estructuradas:** Se hace toda al inicio del proyecto.
* **Ágiles:** Es continua y se adapta en cada sprint.

### Cambios
* **Estructuradas:** Son muy difíciles y costosos de aplicar.
* **Ágiles:** Son bienvenidos en cualquier momento.

### Documentación
* **Estructuradas:** Es extensa, detallada y formal.
* **Ágiles:** Se genera solo la mínima necesaria.

### Cliente
* **Estructuradas:** Solo ve el producto terminado al final.
* **Ágiles:** Participa y opina constantemente.

### Equipo ideal
* **Estructuradas:** Grande y con roles muy especializados.
* **Ágiles:** Pequeño y con miembros multifuncionales.

### Predicción
* **Estructuradas:** Alta, ya que todo se define al principio.
* **Ágiles:** Baja al inicio, pero sube al avanzar.

### Riesgo
* **Estructuradas:** Alto si los errores se descubren tarde.
* **Ágiles:** Bajo, los fallos se detectan rápido.

### Ejemplos
* **Estructuradas:** Modelos en Cascada, en V o Espiral.
* **Ágiles:** Marcos como Scrum, Kanban o XP.

## Requerimientos

Un requerimiento es la descripción precisa de lo que un sistema debe hacer o las restricciones que debe cumplir, traduciendo las peticiones del cliente al lenguaje de los desarrolladores. Al igual que al pedir una pizza defines el tamaño, los ingredientes y el tiempo de entrega, en el software se detallan estas condiciones para que los programadores sepan exactamente qué construir.

### Requerimientos que debe de cumplir

* **Specific (Específico):** Debe ser claro y detallado, sin dejar espacio a ambigüedades.
* **Measurable (Medible):** Debe poder verificarse y probarse con facilidad.
* **Achievable (Alcanzable):** Debe ser realista y posible de construir con los recursos disponibles.
* **Relevant (Relevante):** Debe aportar un valor real e importante para el negocio o el usuario.
* **Time-bound (Con plazo):** Debe tener definido un límite de tiempo o fecha para estar listo.

### ¿Cómo son los pasos para un requerimiento?

* **Entrevistas:** Conversar de forma directa con los usuarios y clientes para entender sus necesidades.
* **Encuestas:** Recoger opiniones y datos de un gran volumen de personas de manera rápida.
* **Observación:** Ver detalladamente cómo trabaja la gente en su día a día para identificar problemas reales.
* **Talleres:** Reuniones grupales con los interesados para debatir y co-crear las soluciones.
* **Análisis de documentos:** Revisar manuales, leyes, contratos y sistemas actuales para entender las reglas del negocio.
* **Prototipos:** Crear maquetas visuales para que el cliente valide si el diseño es el correcto antes de programarlo.
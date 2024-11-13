# Prompt que mediante parámetros solicite a la IA un ejercicio a resolver

## Presentación del problema a abordar

En el desarrollo de software es frecuente que sean escasos los ejercicios para aplicar conceptos o que la creatividad se acabe rápido, ya sea que estemos buscando ejercicios para resolver nosotros o para que los resuelva un alumno. Pero también podría ampliarse el rango objetivo hacia más áreas que tengan el mismo problema, o que se puedan resolver desde texto a texto o texto a imagen. 
Esto supone un problema porque ralentiza y demora el avance de la práctica y el aprendizaje. 
Es necesario brindar una solución para que deje de ser una preocupación la búsqueda de ejercicios y concentrar los esfuerzos y creatividad en la resolución de los mismos.

## Desarrollo de la propuesta de solución

Desde un formulario web se le solicitará al usuario una serie de parámetros como asignatura, nivel, dificultad, orientación, etc. los cuales se usarán para generar un prompt y que la inteligencia artificial desarrolle un ejercicio sujeto a los parámetros indicados. 
El resultado podría ser tanto una consigna redactada como una imagen.

## Justificación de la viabilidad del proyecto

El proyecto es viable porque es factible solicitarle a cualquier inteligencia artificial que desarrolle un texto o imagen, dado que es la forma en la que trabajan según sea.

<hr />

## Prompts

### Ejemplo 1:
Estructura: Necesito un ejercicio para resolver. La materia es [espacio curricular], el tema es [tema]. La dificultad es [dificultad].

Prompt de ejemplo: Necesito un ejercicio para resolver. La materia es analisis funcional. El tema es relevamiento de requerimientos funcionales y no funcionales. La dificultad es basica

Resultado esperado:
Ejercicio: Identificación de Requerimientos
Imagina que estás realizando el análisis funcional para una aplicación de gestión de tareas para estudiantes llamada "Mi Estudio". La aplicación permitirá a los estudiantes organizar sus asignaciones, establecer fechas de entrega, y recibir recordatorios.

Identifica y clasifica los siguientes requerimientos en funcionales o no funcionales:

- La aplicación debe permitir a los usuarios crear, editar y eliminar tareas.
- La aplicación debe enviar recordatorios a los usuarios un día antes de la fecha de entrega de cada tarea.
- La interfaz debe ser intuitiva y fácil de usar.
- La aplicación debe funcionar sin errores en dispositivos Android e iOS.
- Los datos de los usuarios deben estar encriptados.
- La aplicación debe ser capaz de manejar hasta 10,000 usuarios simultáneamente.
Redacta tres nuevos requerimientos funcionales y tres no funcionales para mejorar la aplicación.

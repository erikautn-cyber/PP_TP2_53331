# PP_TP2_53331
Trabajo Practico 2 de Erika Coronel, Legajo: 53331
Alumna: Erika Denise Coronel
DNI: 47370133
Legajo: 53331

Descripción
Este proyecto corresponde al Trabajo Práctico N°2 de la asignatura Paradigma de Programación.

El sistema permite gestionar eventos universitarios, estudiantes, salas, actividades e inscripciones.

Durante el trabajo se aplican conceptos de Programación Orientada a Objetos, excepciones, interfaces, genéricos, persistencia y concurrencia.

Ejercicios realizados
Ejercicio 1
Gestión de eventos universitarios.
Gestión de estudiantes.
Gestión de salas.
Actividades.
Inscripciones.
Excepción personalizada CupoExcedidoException.
Uso de try-catch-finally.
Persistencia mediante serialización.
Recuperación de eventos.
Ejercicio 2
Interfaz Certificable.
Actividades certificables.
Clase Curso.
Generación de certificados para talleres y cursos.
Ejercicio 3
Uso de genéricos.
Uso de límites de tipo.
Uso de wildcards.
Filtrado de actividades por tipo.
Cálculo de costos de materiales.
Ejercicio 4
Clase anidada TicketDeAcceso.
Generación de tickets.
Clase EnvioTicketsThread.
Uso de hilos.
Ejecución concurrente entre el hilo principal y el hilo de envío.
Tecnologías utilizadas
Java
IntelliJ IDEA
Git
GitHub
Ejecución
Para ejecutar el proyecto:

Abrir el proyecto en IntelliJ IDEA.
Abrir App.java.
Ejecutar el método main.
Observar los resultados en la consola.

Estructura del proyecto
src
├── actividades
│   ├── Actividad.java
│   ├── Charla.java
│   ├── Taller.java
│   └── Curso.java
│
├── certificacion
│   └── Certificable.java
│
├── excepciones
│   └── CupoExcedidoException.java
│
├── hilos
│   └── EnvioTicketsThread.java
│
├── modelo
│   ├── EventoUniversitario.java
│   ├── Estudiante.java
│   ├── Inscripcion.java
│   └── Sala.java
│
└── App.java

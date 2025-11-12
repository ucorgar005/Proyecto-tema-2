# Proyecto-tema-2
Ingeniería del Software
# Planteamiento del proyecto
Cliente: Director/a de la escuela interesada en digitalizar la gestión de libros y préstamos.

Conversación informal simulada con el cliente:
"Me gustaría poder llevar un control de los libros disponibles en la biblioteca de forma digital, que los profesores y alumnos puedan consultar si un libro está disponible, registrar los préstamos y devoluciones, y también poder generar estadísticas sobre el uso de la biblioteca."

# Metodología
Metodología: Scrum (ágil)

Justificación:
Adecuada para proyectos con requisitos parcialmente explorados y cambios frecuentes.

Permite iteraciones rápidas y entregables incrementales.

Ideal si el equipo es pequeño (2-5 miembros), ya que facilita reuniones cortas y coordinación continua.

# Etapas que conforman el ciclo de vida del proyecto
Etapas, roles y reuniones:

Product Backlog: Lista priorizada de funcionalidades y tareas basadas en los requisitos del cliente. Responsable: Product Owner (PO).

Sprint Planning: Definición de qué tareas se implementarán en el sprint. Roles: PO, Scrum Master (SM), Equipo de Desarrollo.

Sprint (2-3 semanas): Desarrollo de funcionalidades; tareas diarias asignadas y ejecutadas por los desarrolladores.

Daily Scrum: Reunión diaria de 15 minutos para coordinar avances, obstáculos y próximos pasos.

Sprint Review: Presentación de lo desarrollado al PO y stakeholders para recibir feedback.

Sprint Retrospective: Evaluación interna del equipo sobre el proceso del sprint y mejoras a implementar.


Roles y distribución:
Product Owner (1): Representa al cliente, prioriza funcionalidades.

Scrum Master (1): Facilita las ceremonias y gestión de impedimentos.

Desarrolladores (2-3): Implementación de código, documentación y pruebas unitarias.

Productos a generar:

Documentación en markdown (README.md, especificaciones).

Incrementos de software funcional al final de cada sprint.

Reportes de estadísticas de uso y logs de pruebas.

# Lista de requisitos funcionales y no funcionales
Funcionales:

Registro y login de usuarios (profesores y alumnos).

Consultar disponibilidad de libros.

Registro de préstamos y devoluciones.

Generación de reportes estadísticos sobre libros más consultados.

Notificaciones de retrasos en devoluciones.

No funcionales:

Interfaz intuitiva y responsive.

Seguridad en el almacenamiento de datos (contraseñas en hash).

Rendimiento adecuado: consultas y reportes en menos de 2 segundos.

Escalabilidad para soportar crecimiento del inventario.

# Herramientas
IDE: Visual Studio Code para desarrollo de front-end y back-end.

Lenguaje de programación: Python (con Flask/Django) para backend, HTML/CSS/JavaScript para frontend.

Base de datos: SQLite o PostgreSQL para almacenamiento de libros y registros de usuarios.

Control de versiones: Git y GitHub para la gestión de código y colaboración (ramas feature, main, develop).

Documentación: Markdown en GitHub README.md y Wiki para guías de usuario.

Pruebas: Pytest para pruebas unitarias, Selenium para pruebas funcionales de UI.

Herramientas de comunicación: Slack o Discord para coordinación del equipo.

Uso en fases:

Planificación: Product Backlog en GitHub Issues y Milestones.

Desarrollo: IDE para codificación, Git para commits diarios y ramas de features.

Pruebas: Pytest/Selenium en ciclo de integración continua.

Entrega: Merge a rama main, despliegue en servidor de pruebas o demo para cliente.

# Resumen
Planificación inicial: Reunión con cliente, definición de requisitos, backlog inicial.

Desarrollo iterativo: Sprints de 2-3 semanas implementando funcionalidades prioritarias.

Pruebas continuas: Validación automatizada y manual de cada módulo.

Revisión con cliente: Feedback y ajustes, actualización del backlog.

Documentación: Actualización de README.md, generación de manual de usuario.

Entrega final: Software funcional con documentación completa, listo para su uso en la biblioteca.

El enfoque ágil permite adaptarse rápidamente a cambios de requisitos, mientras que el control de versiones y las pruebas garantizan la calidad y trazabilidad del proyecto a lo largo de su ciclo de vida.

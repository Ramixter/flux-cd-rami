# flux-cd-rami

GitOps es un marco de trabajo que se utiliza en el entorno ágil actual para gestionar y controlar el proceso de entrega de código a través de un repositorio Git. En este enfoque, el estado deseado del sistema se almacena en un sistema de control de versiones, lo que permite a cualquier persona tener una pista de auditoría completa de los cambios realizados. Git se convierte en la fuente única y verdadera para toda la configuración, infraestructura y código de la aplicación.

Cuando se realiza una actualización del código en Git, se activa una canalización de CI/CD (Integración Continua/Entrega Continua). Esta canalización ejecuta una serie de tareas que resultan en la actualización del entorno en ejecución para que coincida con la fuente. En resumen, GitOps es un proceso automatizado que garantiza que el estado deseado en el repositorio de Git y el estado real en el entorno de Kubernetes siempre estén sincronizados.

Con Git, cualquier cambio o actualización se controla mediante solicitudes de extracción y el historial de Git proporciona una secuencia de actualizaciones, lo que permite recuperar el estado de cualquier instantánea.

En resumen, GitOps es una forma de gestionar y controlar la entrega de código de manera automatizada, utilizando Git como fuente única de verdad y garantizando la sincronización entre el estado deseado y el estado real del sistema.

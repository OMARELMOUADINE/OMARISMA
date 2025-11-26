# OMARISMA
2. Descripción del proyecto (como si hablara el cliente)

“El centro deportivo desea un sistema web que permita a los usuarios registrarse, iniciar sesión, consultar las instalaciones disponibles (pistas, salas, piscina…), ver horarios libres y realizar reservas. También queremos que los administradores puedan añadir instalaciones, gestionar horarios, cancelar reservas y ver estadísticas de uso. El sistema debe ser accesible desde cualquier dispositivo, ser seguro y fácil de usar.”

3. Metodología seleccionada: Modelo en V

He elegido el Modelo en V porque:

Es adecuado para proyectos con requisitos claros desde el principio, como este sistema de reservas.

Permite una fuerte relación entre etapas de desarrollo y etapas de prueba, lo que ayuda a garantizar calidad.

Es muy útil cuando el grupo es pequeño o incluso de una sola persona, ya que cada fase queda bien definida y evita improvisaciones.

Reduce riesgos al tener un proceso secuencial y bien documentado.

4. Etapas del ciclo de vida con el Modelo en V

El Modelo en V está dividido en dos grandes ramas:

Fase descendente (definición y diseño)

Fase ascendente (pruebas)

A continuación se detallan todas las etapas, los roles y los productos generados.

Fase descendente (lado izquierdo de la V)
1. Análisis de requisitos

Producto: Documento de requisitos (funcionales y no funcionales).
Rol: Analista / Cliente.
Se define qué hará el sistema.

2. Especificación de requisitos del sistema

Producto: Especificación formal del sistema.
Rol: Analista.
Se estructura cómo debe comportarse el sistema globalmente.

3. Diseño de la arquitectura

Producto: Diagrama de arquitectura, elección de tecnologías.
Rol: Arquitecto de software.
Se definen módulos, capas y relaciones.

4. Diseño detallado

Producto: Diagramas de clases, modelos de datos, estructuras de interfaces.
Rol: Desarrollador / Arquitecto.
Se detalla cómo se implementará cada componente.

Fase ascendente (lado derecho de la V)
5. Pruebas unitarias

Producto: Casos de prueba por componente.
Rol: Desarrollador.
Se prueba cada módulo aislado.

6. Pruebas de integración

Producto: Pruebas de interacción entre módulos.
Rol: QA / Desarrollador.
Se verifica que los componentes trabajen bien juntos.

7. Pruebas del sistema

Producto: Pruebas globales del sistema completo.
Rol: QA.
Verifica que el sistema respete la especificación funcional.

8. Pruebas de aceptación

Producto: Validación por parte del cliente.
Rol: Cliente.
Confirma que el producto cumple lo que necesita.

Reuniones según el Modelo en V

Reunión de inicio: Aclaración de requisitos.

Revisión del análisis: Validación de requisitos.

Revisión del diseño: Arquitectura y modelo de datos.

Reuniones de seguimiento: Avances del desarrollo.

Revisión de pruebas: Validación final.

5. Requisitos funcionales y no funcionales
Requisitos funcionales

El sistema permitirá a los usuarios registrarse y autenticarse.

El usuario podrá consultar las instalaciones disponibles.

El usuario podrá ver horarios y disponibilidad.

El usuario podrá realizar, modificar o cancelar reservas.

El administrador podrá gestionar instalaciones.

El administrador podrá consultar estadísticas de uso.

El sistema enviará notificaciones de confirmación de reservas.

El sistema permitirá pago opcional de servicios adicionales (si aplica).

Requisitos no funcionales

La interfaz debe ser responsiva (adaptada a móviles, tablets y PCs).

El sistema debe estar disponible el 99% del tiempo.

Los datos deben almacenarse de manera segura (cifrado, HTTPS).

El sistema debe soportar hasta 200 usuarios simultáneos.

El tiempo de respuesta máximo debe ser 2 segundos en operaciones comunes.

El sistema debe implementarse con código mantenible y documentado.

6. Herramientas necesarias
IDE

Visual Studio Code: Desarrollo del front-end y back-end.

Lenguaje de programación

JavaScript / Node.js para el back-end.

HTML, CSS, JS o React para el front-end.

Base de datos

MySQL o PostgreSQL (modelado en fase de diseño detallado).

Control de versiones

Git + GitHub

Usado durante todo el desarrollo, con ramas por funcionalidad.

Herramientas de documentación

Draw.io para diagramas.

Markdown para documentación del sistema.

Herramientas de pruebas

Jest o Mocha para pruebas unitarias.

Postman para pruebas de API.

Selenium para pruebas de interfaz si fuese necesario.

Uso según fases

Diseño → Draw.io, Markdown

Implementación → VSCode, Git

Pruebas unitarias → Jest

Pruebas de integración → Postman, Jest

Pruebas del sistema → Selenium

7. Resumen de cómo se llevaría a cabo el proyecto

Reunión inicial con el cliente y recopilación de requisitos.

Redacción del documento de requisitos y validación.

Diseño de la arquitectura del sistema y tecnologías a usar.

Diseño detallado: base de datos, componentes, pantallas.

Programación de todos los módulos desde lo más básico.

Pruebas unitarias de cada módulo desarrollado.

Integración gradual de módulos + pruebas de integración.

Prueba del sistema completo siguiendo los requisitos.

Pruebas de aceptación con el cliente y corrección de errores.

Entrega final del sistema y documentación completa.

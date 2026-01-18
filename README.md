🐾 SOSANIMALES
SOSANIMALES es una plataforma web diseñada para centralizar y agilizar la búsqueda de animales desaparecidos. El proyecto surge de la necesidad de ofrecer una herramienta eficiente para que los dueños de mascotas puedan generar alertas rápidas y la comunidad pueda colaborar en su hallazgo.

🚀 Descripción del Proyecto
La aplicación gestiona la pérdida de mascotas a través de dos niveles de acceso:

- Usuario Registrado: Tiene control total sobre su perfil. Puede registrar múltiples mascotas, generar avisos de pérdida específicos, editar la información en tiempo real y eliminar los avisos una vez el animal ha sido encontrado.

- Usuario Visitante (Sin registro): Puede visualizar todos los avisos activos en la plataforma para colaborar en la búsqueda, pero no tiene permisos para crear contenido o registrar animales.

El sistema utiliza formularios dinámicos para recopilar datos críticos del animal (raza, fotos, señas particulares) y datos de contacto de emergencia.

🛠️ Tecnologías Utilizadas

Para el desarrollo de este prototipo se han empleado las siguientes herramientas y lenguajes:

- Frontend: HTML5, CSS3, JavaScript.
- Backend: PHP (Arquitectura limpia).
- Base de Datos: MySQL.
- Entorno y Pruebas: VS Code, Postman (para pruebas de API/Rutas).

📋 Requisitos y Análisis

Diseño y UX
- Responsive Web Design: Adaptación completa a dispositivos móviles, tablets y escritorio.
- Diseño Original: Interfaz creada desde cero sin el uso de plantillas (templates prefabricados).
- Frameworks: Se han utilizado frameworks de diseño para optimizar la rejilla y componentes UI.

Lógica de Negocio (Backend)
- Implementación CRUD: Gestión completa de usuarios, mascotas y avisos.
- Seguridad: * Protección contra SQL Injection.
- Validación de datos tanto en cliente (JS) como en servidor (PHP).
- Acceso restringido mediante Login.
- Securización de sesiones mediante Tokens.

📐 Arquitectura del Sistema

El proyecto sigue una estructura lógica basada en los siguientes diagramas:

Modelo Entidad-Relación (E/R)
- Define la estructura de las tablas Usuarios, Mascotas y Avisos, asegurando la integridad referencial.

Modelo de Clases (UML)
- Representa la lógica de objetos, sus atributos y los métodos necesarios para la manipulación de datos.

🛡️ Control de Errores y Validaciones

- JS: Validación en tiempo real de campos obligatorios, formatos de email y tipos de archivo.

- PHP: Control de excepciones y mensajes de error amigables para el usuario, evitando fugas de información técnica.
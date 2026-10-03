# Capítulo IV: Product Implementation & Validation

## 4.1. Software Configuration Management

La gestión de la configuración establece los estándares técnicos, herramientas y procedimientos automatizados que el equipo de desarrollo utiliza para garantizar la escalabilidad, el orden colaborativo y la calidad del código fuente a lo largo del ciclo de vida de HelpMom.


### 4.1.1. Software Development Environment Configuration

Se estandarizó un entorno de desarrollo ágil y moderno que permite al equipo trabajar de manera fluida en todas las capas del sistema (Frontend web, aplicación móvil y Backend de microservicios).

* **Entorno de Desarrollo Integrado (IDE):** Visual Studio Code, estandarizado para todo el equipo con extensiones clave (Prettier, ESLint, GitLens y asistentes de IA CopilotKit) para unificar la sintaxis y agilizar la escritura.
* **Desarrollo Web (Landing Page):** Entorno de ejecución Node.js con el framework React/Next.js y Tailwind CSS para la construcción e hidratación eficiente de componentes visuales con temas minimalistas.
* **Desarrollo Móvil:** Flutter SDK para la compilación multiplataforma (iOS y Android) de la aplicación principal.
* **Desarrollo Backend & IoT:** Entornos configurados con .NET, C# y Python para el procesamiento del triage de inteligencia artificial, la gestión de bases de datos relacionales y la recepción de telemetría desde los dispositivos IoT.

### 4.1.2. Source Code Management

El control de versiones del proyecto se gestiona íntegramente mediante Git, alojando los repositorios centrales en GitHub. Se ha adoptado un modelo de trabajo colaborativo basado en GitHub Flow para asegurar una integración continua robusta.

**Estructura de Ramas:**
* **`main`**: Rama de producción. Contiene el código estable, validado y desplegado. Está protegida contra commits directos.
* **`develop`**: Rama principal de integración donde se unifican todas las nuevas funcionalidades del Sprint antes de pasar a producción.
* **`feature/nombre-de-tarea`**: Ramas efímeras creadas a partir de develop para el desarrollo de nuevas historias de usuario (ej. `feature/landing-page-ui`, `feature/iot-bluetooth-sync`).

**Pull Requests (PR):** 
Toda integración de código requiere la apertura de un Pull Request hacia la rama `develop`, exigiendo la revisión de código (Code Review) por parte de otro miembro del equipo antes del merge.
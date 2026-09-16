<div align="center">

<img src="assets/upc-logo.jpeg" alt="UPC Logo" width="300" />

# Universidad Peruana de Ciencias Aplicadas

### Carrera de Ingeniería de Software

<br>

**Curso:** Aplicaciones para Dispositivos Móviles (1ACC0238)  
**NRC:** 13984

<br>

## Informe del Trabajo Final

**Docente:** Quevedo Velasco, David Gerardo  
**Equipo:** FeluSmart  
**Proyecto:** HelpMom

<br>

### Integrantes

| Código | Apellidos, Nombres |
| :---: | :--- |
| u202218590 | Stephano Espinoza Cueva |
| [Código 2] | [Nombres 2] |
| [Código 3] | [Nombres 3] |
| [Código 4] | [Nombres 4] |
| [Código 5] | [Nombres 5] |

<br><br>

**Período 202620**  
**Setiembre 2026**

</div>
---

# Capítulo I: Introducción

## 1.1. Startup Profile

A continuación, se brindará información sobre a qué se dedica nuestra empresa, FeluSmart.

### 1.1.1. Descripción de la Startup

FeluSmart es una startup que se dedica principalmente al desarrollo de software. Fue creada por estudiantes de la Universidad Peruana de Ciencias Aplicadas (UPC) con la visión de generar un impacto social positivo. El objetivo de FeluSmart es ayudar a mujeres gestantes y a sus familias a transitar la etapa del embarazo con tranquilidad y seguridad. Asimismo, FeluSmart se compromete a ofrecer una aplicación móvil accesible, intuitiva, empática y centrada en brindar paz mental, mejorando significativamente la calidad de vida de los futuros padres mediante autonomía, soporte continuo y conexión compartida.

**Misión:** Desarrollar soluciones tecnológicas móviles accesibles y eficientes que acompañen a las familias durante la gestación, integrando inteligencia artificial y monitoreo inteligente de forma intuitiva y sin generar estrés.

**Visión:** En un futuro cercano, FeluSmart se destacará como una empresa líder en el desarrollo de soluciones de salud materno-infantil digital. Asimismo, se le reconocerá por su compromiso con la accesibilidad, la innovación social, la reducción de la ansiedad prenatal y la mejora continua de la dinámica familiar durante el embarazo.

## 1.2. Solution Profile

En este punto del informe, se presentará información detallada sobre nuestro producto de software, incluyendo su nombre, descripción y el modelo de monetización.

### Product Name

Se decidió llamar a nuestro producto **“HelpMom”**, un nombre compuesto por dos palabras en inglés: “Help” (ayuda) y “Mom” (mamá). Esta combinación refleja claramente el propósito principal de la plataforma: brindar apoyo integral a las madres y herramientas de acompañamiento activo a las parejas durante el embarazo y los primeros meses de vida del bebé.

### Product Description

HelpMom es una aplicación móvil cuya función principal es acompañar a la pareja durante la gestación. A través de una arquitectura optimizada para dispositivos móviles, la app traduce datos médicos complejos de sensores IoT a un sistema de "semáforos" amigable para reducir la ansiedad. Además, integra un Asistente IA disponible 24/7 con triage de emergencias y un "Modo Compañero" que permite al padre o acompañante involucrarse activamente mediante consejos prácticos diarios y alertas de asistencia rápida.

### Monetización

HelpMom funciona mediante un modelo de suscripción mensual o anual. Se ofrecen dos planes diseñados para adaptarse a diferentes niveles de necesidad y acompañamiento tecnológico durante el embarazo y el posparto:

- **Plan Básico:** Dirigido a madres que requieren organización básica e información confiable.
  - Acceso a la vista "Mi Cuerpo" para registro de síntomas y métricas básicas.
  - Desbloqueo de contenido educativo semanal en la sección "Aprendizaje".
  - Píldoras de autoestima y recordatorios básicos.
  - Acceso al "Modo Compañero" con envío de alertas rápidas (Pasa la Voz).

- **Plan Cuidado Integral:** Pensado para una maternidad monitoreada de forma inteligente y segura. Incluye todo lo del Plan Básico, más:
  - Acceso ilimitado al Asistente IA (Chat) 24/7 para consultas de rutina.
  - Triage Inteligente con bloqueos de seguridad y alertas de emergencia.
  - Sincronización y traducción de datos del sensor IoT (Sistema de Semáforo).
  - Guía Diaria avanzada del Acompañante con tips contextualizados a los datos de la madre.


**Análisis 5W2H:**

| Elemento | Descripción |
| :--- | :--- |
| **Who (Quién)** | Madres gestantes (especialmente primerizas) y sus parejas o acompañantes que buscan vivir el embarazo con tranquilidad, conexión y apoyo activo, minimizando la incertidumbre. |
| **What (Qué)** | Plataforma móvil que centraliza el monitoreo de salud mediante IoT simplificado, ofrece soporte emocional y médico de rutina vía un asistente de IA, y sincroniza la experiencia familiar con un Modo Compañero. |
| **Where (Dónde)** | Desde cualquier lugar y en cualquier momento a través de dispositivos móviles (smartphones iOS/Android). |
| **When (Cuándo)** | Durante toda la etapa del embarazo (fase prenatal) y el posparto, adaptando el contenido y el soporte de la IA dinámicamente según la semana exacta de gestación. |
| **Why (Por qué)** | Las madres primerizas suelen sufrir ansiedad por la sobreinformación y la falta de soporte inmediato, mientras que los datos médicos crudos generan más estrés. Además, los padres/acompañantes a menudo se sienten excluidos o no saben cómo ayudar de forma práctica al no contar con herramientas orientadas a ellos. |
| **How (Cómo)** | Mediante una app móvil con navegación por Bottom Bar, un bot conversacional con bloqueos de emergencia, interpretación de datos IoT mediante un sistema de diseño de estado (semáforo) y vinculación de cuentas (madre-acompañante) por código QR. |
| **How Much (Cuánto)** | La plataforma es accesible a través de una suscripción mensual o anual, dependiendo de las características tecnológicas (IA e IoT) habilitadas en cada plan. |

### 1.2.2. Lean UX Process

El proceso Lean UX que adoptamos está orientado a maximizar la eficiencia en el desarrollo de nuestro producto, enfocándose en principios fundamentales como la validación continua, el pensamiento crítico y la acción rápida. A partir de esta filosofía, hemos estructurado nuestro propio enfoque Lean UX, basado en cuatro componentes esenciales: definición de problemas, formulación de suposiciones, creación de hipótesis y desarrollo de un lienzo estratégico.

#### 1.2.2.1. Lean UX Problem Statements

Nuestra aplicación móvil está diseñada con la finalidad de proporcionar tranquilidad, contención emocional e información confiable a madres y padres que desean vivir la etapa del embarazo de forma segura y conectada. En esta etapa, muchas familias enfrentan ansiedad, dudas constantes de madrugada y la necesidad de tomar decisiones informadas sobre su salud, pero los sistemas tradicionales no brindan respuestas inmediatas ni integran al acompañante de manera activa.

HelpMom es una innovadora startup que combina tecnología móvil, sensores inteligentes (IoT) traducidos a un lenguaje amigable, y un Asistente IA 24/7 con triage de emergencias, sumado a un entorno dual que empodera tanto a la madre como a su pareja.

El desafío principal que enfrentamos es generar confianza en madres y padres primerizos para que integren nuestra tecnología IA e IoT como una herramienta aliada en su día a día. A pesar de la precisión de nuestra solución, mostrar datos crudos o depender de un bot puede generar dudas iniciales sobre la fiabilidad en temas delicados. Esto puede dificultar la adopción inicial de la plataforma.

> **¿Cómo podríamos lograr que madres y padres confíen en HelpMom como una solución cálida, intuitiva y segura que traduzca el complejo monitoreo de salud en paz mental, mientras educa y empodera al padre para ser un soporte activo diario?**

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions**

- **Creemos que nuestras usuarias tienen la necesidad de:** recibir respuestas rápidas a dudas de rutina 24/7, monitorear su embarazo sin estrés y poder comunicar sus necesidades físicas a su pareja de forma sencilla.
- **Estas necesidades se pueden satisfacer con:** una app móvil dividida en módulos claros (Inicio, Mi Cuerpo, Aprendizaje, Chat IA) que traduzca la data médica de IoT a íconos de estado y que cuente con un Modo Compañero sincronizado.
- **Nuestros usuarios iniciales son (o serán):** mujeres gestantes primerizas y sus parejas, con acceso a smartphones, que buscan reducir la ansiedad del embarazo mediante tecnología amigable.
- **El valor principal que un usuario quiere obtener de nuestro servicio es:** paz mental, validación emocional y respuestas inmediatas en cualquier momento del día.
- **Los usuarios también pueden obtener estos beneficios adicionales:** empoderamiento del padre/acompañante, celebración de hitos del bebé, educación contextualizada y alertas tempranas de emergencia.
- **Adquiriremos a la mayoría de nuestros usuarios a través de:** estrategias de marketing digital enfocadas en comunidades de futuros padres, redes sociales y campañas centradas en el apoyo emocional y de pareja.
- **Ganaremos dinero mediante:** planes de suscripción mensual o anual para habilitar el uso avanzado de la IA y el monitoreo de datos IoT.
- **Nuestra competencia principal en el mercado será:** aplicaciones genéricas de seguimiento de embarazo que solo muestran el tamaño del bebé, pero carecen de soporte IA, lectura IoT en tiempo real o funciones de involucramiento para el padre.
- **Les superaremos debido a:** nuestra propuesta centrada en el soporte conversacional 24/7, la interfaz "sin estrés" (sistema de semáforo) y la inclusión activa del acompañante.
- **El mayor riesgo para nuestro producto es:** la desconfianza inicial hacia las respuestas generadas por Inteligencia Artificial y el temor a que el triage automático no detecte una emergencia a tiempo.

**User Assumptions (Madre Gestante)**

- **¿Quién es la usuaria?** Mujeres embarazadas, especialmente primerizas, que buscan contención emocional, respuestas rápidas y un seguimiento de su embarazo que no genere ansiedad.
- **¿Dónde encaja nuestro producto en su vida?** En su día a día como un centro de control amigable que consulta para resolver dudas de rutina, registrar sus síntomas y enviar notificaciones rápidas a su pareja.
- **¿Qué problemas resuelve nuestro producto?** La ansiedad por falta de información a deshoras, el estrés de interpretar datos médicos complejos y la dificultad de pedir pequeños favores o expresar malestares a su acompañante sin sentirse una carga.
- **¿Cuándo y cómo se utiliza nuestro producto?** De forma recurrente mediante una navegación por "Bottom Bar", usando el chatbot ante dudas, leyendo las píldoras de autoestima diarias y registrando datos en "Mi Cuerpo".
- **¿Qué características son importantes?** Asistente IA 24/7, Triage inteligente de seguridad, alertas "Pasa la Voz", sistema de semáforo para IoT, e hitos del bebé.
- **¿Cómo debería verse y comportarse nuestro producto?** Debe ser visualmente cálido, tranquilizador, con ilustraciones empáticas y un sistema de notificaciones celebratorio y validador.

**User Assumptions (Padre / Acompañante)**

- **¿Quién es el usuario?** Parejas o acompañantes de las gestantes que desean involucrarse proactivamente pero no saben exactamente cómo ayudar.
- **¿Dónde encaja nuestro producto en su vida?** Como una guía diaria en su smartphone que revisan por las mañanas o cuando reciben una alerta de su pareja.
- **¿Qué problemas resuelve nuestro producto?** La desinformación sobre los cambios físicos y hormonales de la madre, y la sensación de ser un "espectador" durante el embarazo.
- **¿Cuándo y cómo se utiliza nuestro producto?** A través del "Modo Compañero", recibiendo tips diarios y reaccionando a las alertas de la madre.
- **¿Qué características son importantes?** Tips accionables ("¿Cómo ayudar hoy?"), traducción de cambios hormonales, resumen del estado del bebé y recepción de notificaciones de la madre.

**User Outcomes**

- **Reducción drástica de la ansiedad:** Al recibir respuestas 24/7 del asistente IA y ver el estado de salud traducido a colores amigables, las madres sentirán mayor paz mental.
- **Fortalecimiento del vínculo de pareja:** Los acompañantes sabrán exactamente cómo apoyar día a día gracias a los microconsejos prácticos.
- **Prevención y seguridad:** El Triage Inteligente detectará palabras clave de riesgo y derivará a las madres a emergencias reales de manera oportuna.
- **Soporte emocional continuo:** Las píldoras de autoestima y los hitos del bebé mantendrán a la madre motivada y validada durante los cambios corporales.

**Business Outcomes**

- **Conversión de prueba gratuita a planes pagos:** Se espera que al menos un 35% de los usuarios que prueben el chat de IA pasen al Plan Cuidado Integral.
- **Retención mensual mayor al 60%:** El contenido dinámico semanal y las notificaciones de hitos asegurarán el uso recurrente a lo largo de los 9 meses.
- **Recomendación (Boca a boca):** Que el 80% de las parejas usuarias afirmen que HelpMom mejoró su comunicación y tranquilidad durante el proceso.
- **Alianzas tecnológicas:** Establecer convenios con proveedores de hardware IoT (pulseras/monitores) en los primeros seis meses.

**Features Assumptions**

- Flujo de Autenticación unificado con redirección automática por roles (Madre/Acompañante).
- Arquitectura de navegación "Bottom Bar" (Inicio, Mi Cuerpo, Aprendizaje, Asistente IA).
- Asistente IA (Chatbot 24/7) para dudas de rutina.
- Triage Inteligente con modal de emergencia (pantalla roja y botón de llamada directa).
- Interpretación IoT mediante Sistema de Semáforo (tarjetas de estado con íconos y colores).
- Modo Compañero mediante sincronización por código QR.
- Alertas Rápidas ("Pasa la Voz") predefinidas.
- Notificaciones de "Píldoras de Autoestima" e "Hitos del bebé".
- Guía diaria ("Tips para Papá") con acciones concretas de apoyo.


#### 1.2.2.3. Lean UX Hypothesis Statements

- **Creemos que** lograremos una mayor adopción inicial y retención de nuevas usuarias **si** ofrecemos una prueba gratuita de 14 días con acceso parcial al Asistente IA. Al permitir que las madres experimenten la tranquilidad de obtener respuestas inmediatas a sus dudas rutinarias, se aumentará la conversión a planes pagos.
- **Creemos que** aumentaremos la satisfacción de los padres/acompañantes y su participación activa **si** implementamos el "Modo Compañero" con la "Guía diaria". Al recibir tips accionables y sin tecnicismos, se facilitará su involucramiento y se reducirá la fricción en la comunicación de la pareja.
- **Creemos que** fortaleceremos la confianza de las usuarias y reduciremos el riesgo de la IA **si** implementamos el "Triage Inteligente". Al asegurar que el sistema bloquee la conversación y emita un modal de emergencia ante palabras clave críticas, demostraremos que la plataforma prioriza su seguridad física por encima de todo.
- **Creemos que** aumentaremos la fidelidad y el uso recurrente **si** implementamos el "Sistema de Semáforos" para la lectura IoT en lugar de gráficos complejos. Al traducir la data a mensajes tranquilizadores, reduciremos la ansiedad característica del monitoreo de salud constante.
- **Creemos que** mejoraremos el bienestar emocional de la gestante **si** activamos las "Píldoras de Autoestima" y las alertas "Pasa la Voz". Con estas microinteracciones, la plataforma pasará de ser una herramienta clínica a un verdadero soporte de acompañamiento diario.

## Segmentos Objetivo

### Segmento objetivo #1: Madres gestantes peruanas de entre 18 a 35 años de edad

- **Descripción:** Este segmento objetivo está compuesto por mujeres embarazadas, especialmente primerizas, que buscan apoyo inmediato, reducción de estrés y un seguimiento amigable de su gestación a través de su smartphone, sin sentirse abrumadas por datos médicos complejos.
- **Aspectos demográficos:** Sexo: Femenino. Edades: Mayormente entre 18 y 35 años. Nivel socioeconómico: Clases B y C (media-alta y media).
- **Aspectos geográficos:** Nacionalidad: Peruana. Zona geográfica en la que vive: Urbana. Departamento: Lima y Callao.
- **Aspectos psicográficos:** Valoran el autocuidado, la conexión emocional con su bebé y la contención. Se sienten abrumadas por la terminología médica y buscan herramientas visualmente cálidas que celebren sus hitos. Desean sentirse acompañadas y validadas frente a los cambios de su cuerpo.
- **Necesidades:** Requieren respuestas a dudas rutinarias a cualquier hora (madrugadas), monitoreo de salud que no genere pánico, y una forma sencilla de comunicar sus necesidades físicas (antojos, cansancio, dolores) a su pareja sin sentir que son una carga.
- **Requisitos:** Buscan una plataforma móvil confiable, estéticamente tranquilizadora, que filtre lo urgente de lo normal y que centralice sus registros, lecturas de sensores y conexión con su pareja.
- **Objetivo:** Vivir un embarazo seguro, validado emocionalmente y con la menor incertidumbre posible, apoyándose en la IA y en la participación activa de su pareja.

### Segmento objetivo #2: Padres y acompañantes peruanos de entre 18 a 40 años de edad

- **Descripción:** Este segmento objetivo está compuesto por las parejas o acompañantes directos de las gestantes, quienes desean involucrarse de forma proactiva en el proceso del embarazo, pero a menudo carecen de conocimientos técnicos, médicos o guía práctica sobre cómo ser de utilidad en el día a día.
- **Aspectos demográficos:** Sexo: Mayormente masculino (padres), aunque incluye a cualquier acompañante de confianza. Edades: Mayormente entre 18 y 40 años. Nivel socioeconómico: Clases B y C.
- **Aspectos geográficos:** Nacionalidad: Peruana. Zona geográfica en la que vive: Urbana. Departamento: Lima y Callao.
- **Aspectos psicográficos:** Quieren ser útiles y brindar apoyo, pero a veces se sienten desorientados o excluidos ante los cambios hormonales y físicos de su pareja. Valoran la información directa, práctica, accionable ("al grano") y sin rodeos médicos.
- **Necesidades:** Entender el desarrollo del bebé y los síntomas de su pareja semana a semana, recibir sugerencias concretas de cómo ayudar (hacer la cena, dar un masaje, preparar el bolso), y mantener una comunicación rápida para atender las necesidades de la madre.
- **Requisitos:** Buscan una interfaz adaptada a su rol (Modo Compañero) que no invada la privacidad clínica de la madre, pero que les envíe alertas, tips diarios en notificaciones push y un resumen visual del estado del bebé.
- **Objetivo:** Convertirse en un soporte activo, informado y empático, fortaleciendo el vínculo de pareja, aliviando la carga de la madre y preparándose adecuadamente para la llegada del bebé.
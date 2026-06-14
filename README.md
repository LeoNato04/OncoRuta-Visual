# 🎗️ OncoRuta Visual — Portal de Paciente (Prototipo)

Un sistema de navegación hospitalaria e inclusión visual diseñado para optimizar el acompañamiento, reducir la ansiedad y mitigar el riesgo de deserción en pacientes oncológicas del Instituto Nacional de Enfermedades Neoplásicas (INEN).

Este repositorio contiene el prototipo interactivo de la interfaz del paciente, integrado en un único ecosistema web de alta fidelidad.

---

## 📌 Visión del Proyecto

El proceso oncológico suele ser complejo, burocrático y emocionalmente abrumador. **OncoRuta Visual** transforma el camino del paciente en una experiencia guiada paso a paso a través de un **sistema híbrido (físico-digital)**:

1. **El Pasaporte Físico:** Al ingresar, la paciente recibe un colgante reutilizable. Su color e ícono universal indican visualmente la etapa actual en la que se encuentra, permitiendo al personal de salud orientarla ágilmente sin barreras idiomáticas o de lectoescritura.
2. **El Chip QR Protegido:** Ubicado en un compartimento inferior de la credencial, este chip contiene los datos personales y clínicos necesarios para la atención. Por estrictas razones de privacidad, **solo puede ser escaneado por médicos y personal autorizado del hospital** con dispositivos institucionales, blindando la información confidencial de la paciente contra terceros.
3. **El Portal Digital:** Al ser escaneado internamente, el sistema sincroniza el progreso en tiempo real y gestiona alertas críticas (tareas pendientes, riesgos de retraso), complementándose con asistencia de audio y soporte multilingüe adaptado a la diversidad cultural del Perú.

---

## 🗺️ El Sistema Visual (Código de Colores)

El flujo del tratamiento se estructura en 6 niveles claramente diferenciados mediante la iconografía y paleta de colores del pasaporte físico:

*   **🟣 Indigo (Ícono: Estrella - Nivel 0): Registro e Ingreso** — Admisión formal a la OncoRuta y apertura del flujo de navegación.
*   **🟠 Naranja (Ícono: Ojo - Nivel 1): Estudios / Tamizaje** — Ejecución de exámenes preliminares e imágenes (mamografías, ecografías).
*   **💗 Fucsia (Ícono: Documento - Nivel 2): Diagnóstico** — Evaluaciones anatomopatológicas, biopsias y confirmación médica de la patología.
*   **🔵 Azul (Ícono: Casa - Nivel 3): Plan Médico** — Revisión del caso por la junta médica multidisciplinaria y diseño del esquema terapéutico personalizado.
*   **🟢 Verde Vivo (Ícono: Escudo - Nivel 4): Tratamiento Activo** — Desarrollo pleno de las terapias oncológicas principales (quimioterapia, radioterapia o cirugía).
*   **❇️ Verde Esmeralda (Ícono: Corona - Nivel 5): Alta / Ruta Completada** — Culminación exitosa del tratamiento primario y transición a controles periódicos de seguimiento.

---

## 💻 Características del Prototipo HTML

El archivo interactivo proporcionado en este repositorio simula las principales funciones del entorno del paciente y del personal:

*   **Simulador de Progresión Integrado:** Permite avanzar dinámicamente entre las 6 etapas para observar cómo muta la credencial física, los mensajes de soporte y los próximos pasos.
*   **Central de Alertas y Tareas:** Clasificación visual de alertas en semáforo (Urgente 🔴, Pendiente 🟡, Completado 🟢) para el seguimiento de análisis pendientes, firmas o documentación.
*   **Flujo de Activación de WhatsApp:** Módulo interactivo con lógica de verificación en dos pasos (código demo: `1234`) que simula la suscripción a recordatorios automatizados de citas y cambios de nivel.
*   **Diseño Inclusivo y Mobile-First:** Interfaz limpia basada en la tipografía *Public Sans* y la librería *Boxicons*, optimizada para una visualización fluida tanto en computadoras como en pantallas móviles.

---

## 🚀 Instalación y Despliegue Local

Al tratarse de un prototipo construido bajo una arquitectura limpia y unificada, **no requiere de servidores, bases de datos externas ni configuraciones complejas de Node.js/npm**. Todo el diseño (CSS), la estructura (HTML) y la interactividad (JavaScript) residen en el archivo principal.

Para ejecutarlo localmente:
1. Clona este repositorio o descarga el archivo `index.html`.
2. Haz doble clic sobre `index.html` para abrirlo en cualquier navegador web moderno (Chrome, Edge, Firefox, Safari).

### Despliegue en producción (GitHub Pages)
Este proyecto está optimizado para ser publicado de forma gratuita en un par de clics:
1. Sube el archivo `index.html` a la raíz de tu repositorio de GitHub.
2. Ve a **Settings** > **Pages**.
3. Selecciona la rama `main` (o `master`), la carpeta `/(root)` y haz clic en **Save**.
4. ¡Listo! Tu prototipo estará disponible públicamente en la URL provista por GitHub.

---

## 🛠️ Tecnologías Utilizadas

*   **HTML5** — Estructuración semántica de las secciones y componentes del portal.
*   **CSS3** — Diseño responsivo, transiciones animadas para los cambios de estado y maquetación mediante *Grid* y *Flexbox*.
*   **JavaScript (ES6+)** — Lógica de estados del paciente, renderizado dinámico de la ruta y manejo de modales interactivos.
*   **Boxicons (CDN)** — Iconografía universal y minimalista de alta legibilidad.
*   **Google Fonts** — Fuente tipográfica institucional *Public Sans*.

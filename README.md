# Portafolio Web - Vicente Fonseca (ICINF1107)

Este repositorio contiene la entrega de la **Evaluación P2 - Presentación Oral** para la asignatura **Desarrollo de Frontend (ICINF1107)** de la carrera de Ingeniería Civil en Informática en la Universidad Católica de Temuco.

## 1. Definición de Audiencia y Propósito
* **Audiencia Objetivo:** Reclutadores técnicos, docentes evaluadores y pares académicos.
* **Necesidad del Usuario:** Validar rápidamente la estructura de código, comprensión de semántica HTML5, capacidades de diseño responsivo y la aplicación práctica de normas de accesibilidad web (WCAG).
* **Solución de Diseño:** Una interfaz sobria, clara, con jerarquía visual estructurada para que la información académica y los proyectos sean accesibles en menos de 3 clics o desplazamientos rápidos.

## 2. Tecnologías Utilizadas
* **HTML5:** Estructuración semántica pura sin divs superfluos (`header`, `nav`, `main`, `section`, `article`, `footer`).
* **CSS3:** Hoja de estilos externa utilizando CSS Grid, Flexbox y Custom Properties (Variables CSS).
* **Git/GitHub:** Control de versiones y publicación de repositorio.

## 3. Decisiones de Diseño y Responsividad
Se implementaron 3 puntos de quiebre mediante el enfoque **Mobile-First**:
1. **Móvil (< 600px):** Layout en una columna vertical con navegación apilada para facilitar la interacción táctil.
2. **Tablet (>= 600px):** Disposición de proyectos en un Grid de 2 columnas y alineación horizontal de la tarjeta de presentación personal.
3. **Escritorio (>= 900px):** Navegación integrada en la cabecera horizontal y Grid de 3 columnas para optimizar la pantalla ancha.

## 4. Consideraciones de Accesibilidad (WCAG 2.1)
* **Contraste de Color:** Razón de contraste superior a 7:1 en el texto principal sobre el fondo blanco/gris.
* **Navegación con Teclado:** Implementación de enlace de salto (`.skip-link`) y un anillo de foco visible (`:focus-visible`) para navegación por tabulación.
* **Formularios e Imágenes:** Uso estricto de la etiqueta `<label>` vinculada por `id`/`for` y atributos `alt` descriptivos en todas las imágenes.

## 5. Instrucciones de Ejecución
1. Clonar o descargar este repositorio.
2. Abrir el archivo `index.html` en cualquier navegador web moderno (Google Chrome, Mozilla Firefox, Edge).
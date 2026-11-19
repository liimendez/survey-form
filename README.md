# 📝 Survey Form — freeCodeCamp (rediseñado)

Formulario de encuesta del proyecto de certificación de Diseño Web Responsivo de freeCodeCamp, rediseñado con foco en accesibilidad, validación y diseño responsive.

**Demo en vivo:** https://liimendez.github.io/survey-form/
**Repo:** https://github.com/liimendez/survey-form

## Qué es

Proyecto para practicar formularios reales en web: inputs, selects, radios, checkboxes, validación nativa y mensaje de éxito, sin backend.

## Qué incluye

- Inputs de Name, Email y Age (opcional)
- Select de rol actual
- Radios: ¿Recomendarías freeCodeCamp?
- Select de feature favorita
- Checkboxes de mejoras (11 opciones)
- Textarea de comentarios
- Botón Submit con validación y mensaje de éxito

## Qué se mejoró en esta versión

- Se eliminó el `action="procesar_encuesta.php"` que no existía. Ahora el envío se valida en el navegador y muestra un mensaje de éxito con JS mínimo, sin recargar la página.
- Se corrigieron los `id` con espacios (`Open Source Community`, `Gitter help rooms`, etc.) que son inválidos en HTML.
- El select de rol ya no dice `Option 1 / Option 2`: ahora tiene roles reales (Student, Full Time Job, Full Time Learner, etc.).
- `favorite-feature` pasó de ser un `textarea` a un `select`, como pide la consigna original de freeCodeCamp.
- Se agregaron `lang`, `charset`, `viewport` y estructura semántica (`main`, `header`, `fieldset` + `legend`).
- Se reemplazó el fondo de arena + degradado azul + `lizard.png` roto por la estética oscura + verde del proyecto CatDog, para que ambos proyectos combinen en el portfolio.
- Se agregaron estados de `:focus` visibles, `accent-color` en radios/checkboxes y diseño responsive.

## Qué valida

- `Name` y `Email` requeridos, con `type="email"` para validación nativa
- `Age` opcional, con `min="13"` y `max="120"`
- `Role` y `Favorite feature` con placeholder `disabled selected`
- Radios con una opción preseleccionada
- Checkboxes múltiples

## Stack

- HTML5 semántico
- CSS3 (Flexbox + Grid + media queries)
- JS mínimo (validación + mensaje de éxito)
- Google Fonts (Oswald)

## Estructura


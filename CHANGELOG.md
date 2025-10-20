# 🐉 DRAPROMPT Changelog

Todas las actualizaciones notables de este proyecto serán documentadas en este archivo.

## [v2.8.5] - 2025-10-20

Esta es una actualización mayor de sistema y seguridad.

### ⚠️ Corregido (Crítico)

-   **Riesgo de Privacidad (GDPR/CCPA):** Se reescribió la sección `🔒 POLÍTICA DE MEMORIA Y PRIVACIDAD`. Se añadió un *disclaimer* (descargo de responsabilidad) legal explícito que el usuario debe aceptar al usar `memory on`, clarificando que DRAPROMPT no almacena datos y que el usuario consiente el procesamiento por parte del proveedor de la IA (Google, OpenAI, etc.).
-   **Contradicción Lógica (LITE):** Se corrigió un error crítico en `draprompt-lite.md` donde el prompt se contradecía, afirmando tener 3 modos y 8 modos simultáneamente. La versión LITE ahora refleja la arquitectura de 8 modos (en 3 niveles) pero en un formato condensado.

### ⚙️ Cambiado (Lógica del Sistema)

-   **Consistencia de Idioma:** Se refactorizó la lógica de comandos (Punto 6). El "motor" interno del prompt ahora usa **Inglés** como idioma principal (ej. `mode HACKER`). El **Español** se ha definido formalmente como un *alias* (ej. `modo HACKER`).
-   **Centralización de Comandos:** Se creó una nueva sección `🌐 COMANDOS Y LÓGICA DE IDIOMA` como la única fuente de verdad, eliminando la ambigüedad y el "Spanglish".

### ✨ Añadido (Documentación)

-   **Enlaces de Repositorio:** Se actualizaron los *placeholders* `[completar con link...]` en ambos archivos (`v2.8.5` y `LITE v2.8.5`) para que apunten a los archivos correctos dentro del repositorio de GitHub.
-   **Copy README:** Se añadió la sección `📦 LITE vs Completo: ¿Cuál Elegir?` al `README.md` principal para aclarar el valor de cada versión.
-   **Ejemplos Universales:** Se actualizó el `EXAMPLES_FULL.md` para eliminar referencias a proyectos personales ("LogoCodex") y reemplazarlas con ejemplos universales ("Procrastinación").

## [v2.8.2] - (Fecha anterior)

-   Lanzamiento inicial de la versión con 8 modos y sistema de niveles.

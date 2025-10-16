# Changelog

Todas las versiones siguen el formato [SemVer].

## [v1.0.0] - 2025-10-14
### 🆕 Añadido
- ⚙️ **Lista de caracteres especiales — Base táctica XSS**: colección completa de caracteres y combinaciones esenciales que permiten crear, ejecutar y mutar payloads XSS en múltiples contextos web.
- 📚 **Estructura detallada por categoría:**
  - 🧩 Carácteres de sintaxis HTML → apertura/cierre de etiquetas, asignación de atributos, delimitadores y control del parser.
  - 💻 Carácteres de sintaxis JavaScript → operadores, agrupadores, accesos, concatenadores y escapes.
  - 🌐 Carácteres especiales de URL/HTTP → querystring, parámetros, fragmentos, esquemas y credenciales.
  - 🧙 Carácteres escapables → entidades HTML, escapes hexadecimales, Unicode, octales, NCR, etc.
  - 🎭 Invisibles y raros → zero-width, BOM, BIDI, espacio no separable y otros para romper validaciones.
  - 💣 Carácteres de ruptura contextual → cierre de atributos, comentarios HTML/JS/CSS, CDATA y separadores críticos.
  - ⚡ Bonus → separadores multi-contexto y operadores alternativos.
- 📈 **Más de 70+ caracteres documentados** con explicación y ejemplos de uso.
- 📦 **Combinaciones especiales** incluidas: `">`, `</`, `--!>`, `]]>`, `/**/`, `//`, `<!--`, `¬` y más.
- 🧪 **Objetivo del proyecto:** servir como base táctica para la construcción de payloads, bypass de WAF, mutación polimórfica y manipulación avanzada de contexto.

### ✨ Cambiado
- N/A — Primera versión.

### 🐞 Corregido
- N/A — Primera versión.

### 📌 Notas
- Este repositorio es la **base fundamental para cualquier explotación XSS** moderna.  
- Todos los caracteres y combinaciones han sido seleccionados por su capacidad de romper validaciones, escapar contextos y forzar ejecución en entornos protegidos.
- Compatible con navegadores modernos y entornos reales.

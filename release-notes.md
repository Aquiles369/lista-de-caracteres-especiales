# Release Notes — v1.0.0 (2025-10-14)

## 🏹 Resumen
**Lista de caracteres especiales** es una base táctica diseñada para la creación, mutación y evasión de payloads XSS.  
Reúne más de **70 caracteres críticos** y sus combinaciones más útiles, organizados por contexto y con explicación detallada de su función ofensiva.

📺 Demo disponible en el canal de YouTube.

---

## 🧠 Problema que resuelve
Las validaciones rígidas, sanitizadores estrictos y parsers limitados son el mayor obstáculo en la explotación XSS.  
Esta lista resuelve ese problema proporcionando un catálogo completo de caracteres que permiten:

✔️ Escapar de contextos HTML, JS o URL.  
✔️ Romper estructuras de análisis y validación.  
✔️ Crear payloads polimórficos y mutables.  
✔️ Ejecutar código incluso frente a filtros o WAF avanzados.

---

## 📚 Qué aporta
- 🧠 **Control total del contexto:** permite saltar entre HTML, JS, CSS y URL con precisión quirúrgica.
- 🛡️ **Bypass de filtros y WAF:** explota inconsistencias en sanitizadores y parsers.
- 🧬 **Mutación y polimorfismo:** facilita la creación de payloads dinámicos y no detectables.
- 🌍 **Compatibilidad universal:** todos los caracteres son funcionales en navegadores modernos y entornos reales.

---

## 📦 Contenido principal

### 🧩 Carácteres de sintaxis HTML
- `<`, `>`, `/`, `=`, `"`, `'`, `` ` ``, `!`, `?`, `#` — permiten abrir/cerrar etiquetas, romper atributos y manipular el parser.

### 💻 Carácteres de sintaxis JavaScript
- `{ } ( ) [ ] ; , : + - * / % . | & ^ ~ ? : \\ $` — control total de bloques, operadores, accesos, escapes y funciones.

### 🌐 Carácteres URL/HTTP
- `%`, `&`, `?`, `#`, `+`, `:`, `@` — manipulación de parámetros, querystrings y esquemas.

### 🧙 Carácteres escapables
- `&#NN;`, `&#xNN;`, `\xNN`, `\uNNNN`, `\NNN`, `&lt;`, `&gt;`, `&quot;`, `&apos;`, `&amp;`

### 🎭 Invisibles / raros
- `\u200B`, `\u200C`, `\u200D`, `\u2060`, `\uFEFF`, `\u180E`, `\u00A0`, `\u202E`

### 💣 Ruptura contextual
- `">`, `</`, `--!>`, `-->`, `]]>`, `/**/`, `//`, `<!--`

### ⚡ Bonus: Multi-contexto
- `,`, `|`, `~`, `^`, `¬`

---

## 🧪 Uso recomendado
1. Usa la lista para construir payloads XSS adaptados a diferentes contextos (HTML, atributos, JS, URL, etc.).
2. Combina caracteres escapables con invisibles para crear variantes polimórficas.
3. Aplica separadores de ruptura contextual para escapar de estructuras y forzar ejecución.
4. Experimenta con caracteres invisibles en validadores, logs y parsers.

---

## 🛣️ Roadmap
- ✅ Versión base publicada.
- ⏭️ Próximos pasos: ejemplos prácticos por contexto y pruebas automatizadas contra distintos WAF.

---

**“Lista de caracteres especiales — la base para cualquier bypass XSS.”**

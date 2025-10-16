# Política de seguridad

## 🧠 Resumen
**Lista de caracteres especiales** es un recurso puramente informativo diseñado para uso en entornos controlados y con fines educativos.  
Su propósito es servir como base táctica para la creación y mutación de payloads XSS en contextos legales, como laboratorios de pruebas y programas de bug bounty autorizados.

---

## 🔐 Principios de seguridad

- 🧪 **Uso ético y legal:** esta lista debe usarse únicamente en entornos autorizados o laboratorios personales.
- 📁 **Contenido seguro:** no contiene exploits activos ni payloads listos para ejecución automática.
- 🛡️ **Sin backend:** el repositorio es 100% estático y no ejecuta código.
- 📡 **Privacidad:** no almacenes datos sensibles en combinaciones o ejemplos personalizados.

---

## ✅ Buenas prácticas recomendadas

- Usar los caracteres y combinaciones solo en contextos legales y bajo autorización.
- Validar su comportamiento en entornos controlados antes de aplicarlos en un programa real.
- Revisar los estándares de sanitización y validación del entorno antes de intentar bypasses.
- No emplear estos recursos contra sistemas no autorizados.

---

## 🐛 Reporte de vulnerabilidades

Si encontrás algún error o comportamiento inesperado en la documentación:

1. No abras un *issue* público con detalles sensibles.  
2. Contactá al mantenedor por GitHub o Discord.  
3. Incluí detalles del hallazgo y el contexto en el que ocurre.

---

## 🛡️ Alcance de seguridad

| Área                               | Estado                         |
|-----------------------------------|-------------------------------|
| Backend / API                     | ❌ No aplica                  |
| Ejecución de código              | ❌ No incluida                |
| Archivos ejecutables             | ❌ No incluidos              |
| Recursos externos                | ✅ Referencias seguras       |
| Datos sensibles                  | ❌ No deben almacenarse      |

---

## ⚠️ Descargo
Este repositorio tiene fines educativos y de investigación.  
El uso indebido de la información contenida puede ser ilegal.  
El autor no se hace responsable del uso inapropiado del contenido.

---

**“Lista de caracteres especiales — la base para cualquier bypass XSS.”**

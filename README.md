# BUENAS PRÁCTICAS DE DESARROLLO DE SOFTWARE
## Taller Integrador Cortes 1 y 2
**Nombre Completo:** Oscar David Henriquez Ballesteros

### Tabla de Hallazgos

| Defecto encontrado | Por qué era un problema | Cómo lo corrigió |
| :--- | :--- | :--- |
| Nombres de archivos con espacios y mayúsculas | Dificulta la compatibilidad entre sistemas operativos y rompe convenciones web. | Se renombraron usando kebab-case (index.html, style.css). |
| Título de pestaña genérico | No describe el propósito del sitio. | Se cambió a un título descriptivo: "Calculadora de Promedios". |
| Identificadores de HTML poco descriptivos | Dificulta saber qué representan en el HTML, CSS y JS. | Se usaron IDs semánticos (nota1, resultado-promedio, etc.). |
| Nombre de función abreviado (calc) | No expresa claramente la acción con un verbo completo. | Se renombró a "calcularPromedio()". |
| Variables de una sola letra (a, b, c, x) | Obligan a leer todo el código para entender el contexto. | Se renombraron a nota1, nota2, nota3 y cantidadNotas. |
| Variable con mala convención (TempValue2) | Usaba PascalCase rompiendo la convención camelCase estándar en JS. | Se cambió a camelCase con nombre descriptivo (promedioFinal). |
| Variable declarada y no utilizada (data1) | Ocupaba espacio sin cumplir ninguna función. | Se eliminó del código. |
| Código muerto o comentado | Genera ruido visual innecesario, el control de versiones ya guarda el historial. | Se eliminó el bloque de código comentado por completo. |
| Impresiones en consola innecesarias | No aportan funcionalidad al usuario final en producción. | Se eliminaron todos los console.log. |

### Enlace al sitio publicado en Netlify

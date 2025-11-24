# Reto 1 — Catálogo de **Vistas en Odoo 19** (Markdown + capturas)

**Objetivo**: Documentar en un **único archivo Markdown** todos los **tipos de vista** de Odoo 19 con **capturas reales** y **comprobación en modo desarrollador** (Developer Mode) para cada una.

Debes **localizar ejemplos reales** en módulos instalados (Community/Enterprise según disponibilidad) y explicar **cómo llegar** a cada vista.

## Entregable
- Carpeta del reto completa con:
  - `docs/` → contiene **un único documento** `00-vistas_odoo19.md` + `99-bibliografia.md`.
  - `assets/img/<NN-vista>/` → capturas por vista (`pasoNN_descripcion-kebab.png`).
  - `rubric/R01_Vistas_Odoo19_rubrica.md` → rúbrica para auto-revisión.

## Tipos de vista a cubrir
### Vistas estándar
1. **List / Tree**
2. **Form**
3. **Kanban**
4. **Search**
5. **Calendar**
6. **Graph**
7. **Pivot**

### Vistas especiales (según módulos)
8. **Activity**
9. **Cohort** *(Enterprise)*
10. **Gantt** *(Enterprise)*
11. **Grid** *(Enterprise)*
12. **Map** *(Enterprise)*
13. **Hierarchy**
14. **QWeb (reportes/dashboards)**

> Si no dispones de Enterprise, documenta el **intento** y usa **fuentes oficiales** con captura donde la **URL sea visible** para evidenciar el tipo de vista.

## Normas de capturas y enlaces
- Nombra las capturas como: `assets/img/<NN-vista>/pasoNN_descripcion-kebab.png`
- Inserta con **ruta relativa** en el Markdown.
- Añade `alt` y `title` informativos.
- Cuando uses documentación web, incluye **captura con URL visible**.

## Modo desarrollador (imprescindible)
Actívalo y muestra en cada vista cómo confirmar el **tipo de vista** (ej.: *bug icon → Edit View*, nombre técnico, arquitectura).

## Estructura sugerida
- `docs/00-vistas_odoo19.md` → documento único con índice, secciones por vista y checklist final.
- `docs/99-bibliografia.md` → fuentes oficiales/artículos técnicos.

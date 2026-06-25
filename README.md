# Dashboard EVT Nacional — Transelec

Dashboard ejecutivo interactivo del **Estudio de Valorización de la Transmisión (EVT)** — Segmento Nacional.

🔗 **Ver dashboard:** https://blynchtranselec.github.io/Dashboard-Resultados-Informes-EVT/

---

## Contenido

Visualización de los resultados del estudio EVT Nacional para el propietario Transelec (P_032), incluyendo:

- Totales de VI por versión del estudio
- Composición de componentes del VI (Cu, MoD, MoF, Fl, Bo, Ing, GG, II)
- Comparación contra estudio anterior 7T
- Análisis por familias de activos
- Estado del universo BDATx (Vigente / EN_REVISION / Eliminados)

> **Nota:** Esta es la versión web del dashboard. Las tablas de detalle P/Q (comparación fila a fila entre versiones) no están disponibles aquí. Para el análisis completo, usar el archivo `Reporte_Nacional.xlsx`.

---

## Actualización

Cuando se genera un nuevo reporte:

1. Ejecutar `generar_reporte_nacional.py` → genera `Reporte_Nacional.xlsx`
2. Ejecutar `generar_dashboard_html_nacional_ejecutivo.py` → genera el HTML completo local
3. Ejecutar `preparar_para_github.py` → genera `GitHub/index.html` (versión web)
4. Subir `GitHub/index.html` al repositorio reemplazando el anterior

# Prompt 5 · Evolución posterior: dashboard reutilizable

**Nota:** este prompt prepara el siguiente paso del proyecto; no debe confundirse con la auditoría del episodio 01.

Actúa como desarrollador de aplicaciones de análisis contable. Evoluciona el dashboard HTML que acabamos de construir: actualmente incorpora los movimientos en el código; debe convertirse en una herramienta reutilizable que permita cargar nuevos Excel sin reconstruir el dashboard ni volver a consultar a la IA.

**OBJETIVO:** Agrega «Cargar nuevo Excel», conservando indicadores, filtros, gráficas y controles actuales.

**FUNCIONALIDAD:**
1. Permite seleccionar archivos .xlsx; admite .xls solo si lo soportas de forma fiable. Informa los formatos admitidos.
2. Lee exclusivamente la hoja «Movimientos». Utiliza exactamente los encabezados y tipos del Excel de práctica, que contiene únicamente «Movimientos»; primero inspecciónalos y enuméralos. No inventes columnas ni supongas equivalencias ambiguas.
3. Valida esquema, fechas, importes, tipos de movimiento, unidades y referencias; muestra errores por fila y no aceptes silenciosamente datos inválidos.
4. Si la validación falla, conserva el conjunto anterior sin alteraciones. Si pasa, reemplaza por completo los movimientos anteriores: nunca los acumules ni dupliques.
5. Recalcula ingresos, gastos, resultado, margen, gráficas, agrupaciones, filtros y controles. Restablece filtros y opciones después de importar.
6. Si ingresos = 0, muestra N/D en margen; conserva correctamente los resultados negativos.
7. Muestra nombre del archivo, filas leídas, aceptadas, rechazadas y fecha/hora de importación.
8. Incluye «Restaurar datos de ejemplo» para regresar a los 240 movimientos ficticios originales.

**SEGURIDAD Y OPERACIÓN:**
- Debe funcionar localmente en el navegador, sin servidor ni cuentas; no envíes los datos a terceros.
- No uses eval ni insertes valores del Excel como HTML ejecutable.
- Si requieres una biblioteca de lectura de Excel, identifica versión, licencia y archivos auxiliares, e inclúyela localmente para permitir operación sin internet.
- No modifiques el Excel de práctica ni el archivo maestro reservado ni alteres el Design System existente.

**PRUEBAS QUE DEBES EJECUTAR Y DOCUMENTAR:**
A. Importar Excel original: 240 registros y mismos importes auditados, hasta centavos.
B. Importarlo dos veces: ningún duplicado.
C. Importar otro Excel válido con importes distintos: indicadores actualizados.
D. Rechazar un archivo sin columnas obligatorias.
E. Detectar fechas/importes inválidos sin destruir los datos anteriores.
F. Comprobar junio 2026 / CDMX y febrero 2026 / Guadalajara (margen N/D).
G. Comprobar las 40 combinaciones de filtros con el Excel original.

**ENTREGABLES:** HTML actualizado y dependencias locales, instrucciones de uso, reporte de pruebas realmente ejecutadas y explicación de cambios. No declares que una prueba pasó si no la ejecutaste. No agregues funciones ajenas a este alcance.

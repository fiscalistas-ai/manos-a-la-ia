# Prompt 3 · ChatGPT audita los datos

Actúa como auditor independiente de datos contables. Analiza el Excel adjunto mediante cálculos ejecutados. Contiene una única hoja llamada «Movimientos». No utilices los resultados de Claude ni cifras de control externas para construir tus resultados de referencia.

1. Inspecciona la hoja, sus nueve columnas, el periodo y el número de movimientos.
2. Recalcula ingresos, gastos y resultado generales, por mes y por unidad, usando Tipo = «Ingreso» o «Gasto» y Resultado = Ingresos − Gastos. Conserva los centavos y utiliza precisión decimal.
3. Desglosa los gastos por concepto y verifica que las agrupaciones sumen los totales generales.
4. Revisa fechas inválidas, discrepancias entre Fecha y Mes, referencias duplicadas o vacías, importes vacíos o no numéricos, tipos inesperados, importes negativos y posibles errores de precisión.
5. Comprueba la consistencia interna: total de registros por mes y unidad, suma de ingresos y gastos por agrupación, y resultado calculado a partir de esos importes. No pidas ni utilices una hoja «Control»: la comparación contra cifras reservadas la hará posteriormente el presentador.
6. Calcula de manera independiente junio de 2026 / CDMX y febrero de 2026 / Guadalajara; incluye conteos, importes y margen, mostrando «N/D» cuando ingresos = cero.

Entrega un informe con tablas, pruebas realmente ejecutadas, incidencias y limitaciones. No modifiques el Excel. No construyas otro dashboard. No afirmes que has validado existencia, materialidad o validez fiscal de operaciones: esta revisión es aritmética y de integridad de datos.

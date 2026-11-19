# Prompt 4 · ChatGPT audita el dashboard

Ahora adjunto el archivo HTML que Claude generó a partir del mismo Excel de una sola hoja «Movimientos» que ya auditaste. Utiliza tus cálculos independientes anteriores como referencia; no asumas que el dashboard es correcto.

1. Inspecciona el HTML, los registros incrustados y su JavaScript. Compara los nueve campos conservados contra el Excel original por Referencia.
2. Comprueba ingresos, gastos, resultado y, si está disponible, el margen de resultado sobre ingresos.
3. Verifica las 40 combinaciones de filtros: diez estados de mes (Todos + nueve meses) por cuatro estados de unidad (Todas + tres unidades). Contrasta importes, conteos y tratamiento de resultados negativos.
4. Comprueba junio de 2026 / CDMX y febrero de 2026 / Guadalajara (margen «N/D» cuando ingresos = cero).
5. Inspecciona las gráficas, el botón «Mostrar todo», los controles internos de calidad, posibles comparaciones circulares, dependencias externas y riesgos de presentación móvil.
6. Distingue las pruebas ejecutadas de las revisadas únicamente mediante código. No declares probadas las interacciones visuales si no las ejecutaste en un navegador real.

Entrega una matriz con prueba, esperado, obtenido, diferencia, estado y observaciones. Concluye APTO, APTO CON OBSERVACIONES o NO APTO, explicando el alcance. No modifiques ningún archivo.

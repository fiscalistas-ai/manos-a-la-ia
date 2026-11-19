# Episodio 01 · De Excel a dashboard con IA

**Video:** https://www.youtube.com/live/44lfNpzv--E  
**Fecha:** 18 de noviembre de 2026

## Qué se hizo

Partimos de 240 movimientos contables ficticios de nueve columnas, en una sola hoja llamada `Movimientos`. Claude construyó un dashboard y se le pidió incorporar un indicador de margen. ChatGPT realizó cálculos independientes y revisiones del HTML.

## Materiales

- [Prompts](prompts/): cinco instrucciones completas; los prompts 1–4 corresponden a construcción y auditoría, mientras que el 5 es una **evolución posterior** hacia un dashboard reutilizable.
- [Validación](VALIDACION.md): cifras de referencia y límites de las comprobaciones.
- **Excel `movimientos-ficticios.xlsx`: pendiente de subida**. Contendrá exclusivamente la hoja `Movimientos`.
- **HTML `dashboard-v3-ensayo.html`: pendiente de subida**. Es una versión preparada durante ensayos previos, no necesariamente el archivo producido durante la transmisión.

## Cómo reproducir

1. Descarga el Excel de práctica cuando esté publicado y adjúntalo a una conversación nueva de Claude.
2. Ejecuta [Prompt 1](prompts/01-claude-construccion.md) y luego [Prompt 2](prompts/02-claude-margen.md).
3. En una conversación independiente de ChatGPT, adjunta el mismo Excel y ejecuta [Prompt 3](prompts/03-chatgpt-auditoria-excel.md).
4. Adjunta el HTML obtenido de Claude y ejecuta [Prompt 4](prompts/04-chatgpt-auditoria-html.md).
5. Compara resultados y documenta diferencias. El [Prompt 5](prompts/05-evolucion-dashboard-reutilizable.md) se reserva para la evolución posterior.

No se requieren datos reales.

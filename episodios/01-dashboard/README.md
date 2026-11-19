# Episodio 01 · De Excel a dashboard con IA

**Video:** https://www.youtube.com/live/44lfNpzv--E  
**Fecha:** 18 de noviembre de 2026

## Qué se hizo

Partimos de 240 movimientos contables ficticios de nueve columnas, en una sola hoja llamada `Movimientos`. Claude construyó un dashboard y se le pidió incorporar un indicador de margen. ChatGPT realizó cálculos independientes y revisiones del HTML.

## Materiales disponibles

- [Descargar Excel de práctica · movimientos.xlsx](movimientos.xlsx): contiene exclusivamente la hoja `Movimientos`.
- [Descargar dashboard de ejemplo · dashboard-ejemplo.html](dashboard-ejemplo.html): versión preparada durante ensayos previos; no necesariamente corresponde al archivo producido durante la transmisión. Descárgalo y ábrelo localmente en tu navegador.
- [Prompts](prompts/): cinco instrucciones completas. Los prompts 1–4 corresponden a construcción y auditoría; el 5 propone una **evolución posterior** hacia un dashboard reutilizable.
- [Validación](VALIDACION.md): cifras de referencia y límites de las comprobaciones.

## Cómo reproducir

1. Descarga [movimientos.xlsx](movimientos.xlsx) y adjúntalo a una conversación nueva de Claude.
2. Ejecuta [Prompt 1](prompts/01-claude-construccion.md) y luego [Prompt 2](prompts/02-claude-margen.md).
3. En una conversación independiente de ChatGPT, adjunta el mismo Excel y ejecuta [Prompt 3](prompts/03-chatgpt-auditoria-excel.md).
4. Adjunta el HTML obtenido de Claude y ejecuta [Prompt 4](prompts/04-chatgpt-auditoria-html.md).
5. Compara resultados y documenta diferencias. El [Prompt 5](prompts/05-evolucion-dashboard-reutilizable.md) se reserva para la evolución posterior.

No se requieren datos reales. El dashboard de ejemplo es material de referencia, no una sustitución del ejercicio.

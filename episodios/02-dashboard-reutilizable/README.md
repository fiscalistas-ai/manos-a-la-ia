# Episodio 02 · Tu dashboard no debería morir con el Excel

25 de noviembre de 2026 · Manos a la IA · Fiscalistas.AI

[Ver sesión completa en YouTube](https://youtube.com/live/XhJnVCZx3W8)

## Materiales
- [Dashboard base E01](../01-dashboard/dashboard-ejemplo.html)
- [Excel original (240 movimientos)](../01-dashboard/movimientos.xlsx)
- [Dashboard reutilizable v4 de la sesión en vivo](dashboard-reutilizable.html): descarga y abre localmente en Chrome o Edge actualizado.
- [Excel nuevo (48 movimientos)](movimientos-nuevos.xlsx)
- [Excel inválido para pruebas de rechazo](movimientos-invalidos.xlsx)
- [Cinco prompts de la práctica](prompts/)
- [Validación y limitaciones](VALIDACION.md)

Datos ficticios. Los controles internos no sustituyen una auditoría independiente.

## Reproduce la práctica

1. Adjunta el dashboard base y los dos Excel válidos en Claude y ejecuta [Prompt 1](prompts/01-claude-construccion.md).
2. Adjunta el Excel inválido y ejecuta [Prompt 2](prompts/02-claude-pruebas.md).
3. En ChatGPT, inicia una conversación nueva con los dos Excel válidos y ejecuta [Prompt 3](prompts/03-chatgpt-auditoria-excel.md).
4. Adjunta la aplicación y el Excel inválido en esa conversación y ejecuta [Prompt 4](prompts/04-chatgpt-auditoria-aplicacion.md).
5. Evalúa los hallazgos. El [Prompt 5](prompts/05-correccion-opcional.md) es opcional y requiere una nueva auditoría.

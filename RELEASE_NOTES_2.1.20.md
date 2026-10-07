# Punto & Gestión 2.1.20

## Reintentos de guardado de promociones

- Si se corta la conexión al guardar un combo desde Acciones del POS, se conserva el borrador y se ofrece **Reintentar guardado**, sin recargar la pantalla ni perder el carrito o el cliente seleccionado.
- El servidor reconoce cada operación de guardado. Si ya se había completado, confirma el mismo resultado sin crear otra promoción ni repetir la edición.
- Se consulta el catálogo vigente después de confirmar el reintento; una promoción editada, pausada o eliminada posteriormente no se reconstruye con datos anteriores.
- Los permisos existentes y el gestor de promociones de Productos mantienen su funcionamiento.

Esta actualización incluye todas las mejoras de 2.1.17, 2.1.18 y 2.1.19: productos y variantes, categorías y subcategorías, combos, clientes, cuentas corrientes, caja diaria, A5 horizontal y prueba de 30 días.

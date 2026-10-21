# Punto & Gestión 2.1.37 · productos y venta por metro

- El formulario de productos usa Unidad de venta y stock, sin los campos de Presentación. Se conservan las descripciones históricas al editar.
- El catálogo y la ficha muestran la unidad real de venta.
- Las instalaciones antiguas que sólo tenían Unidad y Kilogramo incorporan Metro. Se respetan IDs, unidades personalizadas y un Metro desactivado por el usuario.
- El editor aclara que el precio y el stock se expresan por metro y que se pueden vender fracciones, por ejemplo 0,50 m o 1,25 m.
- Guías e ilustraciones actualizadas para Unidad/kg/Metro.
- Se retira el texto redundante de días y páginas del encabezado del Historial de Estadísticas, conservando la paginación inferior.
- El aviso «Preparando impresión» adopta el encabezado, colores y botón de los modales del POS, con indicador separado y adaptación a celular y modo oscuro. Conserva el envío en segundo plano y la protección contra copias duplicadas.

Las pruebas verificaron venta por metro, fracciones, variantes, límites de stock, anulación y devolución, registros históricos y unidades en cinco formatos y tickets ESC/POS. No se emitieron facturas reales ni se imprimió físicamente durante QA.

Esta preparación no modifica productos ni ventas existentes: únicamente completa el catálogo de unidades con Metro si falta.

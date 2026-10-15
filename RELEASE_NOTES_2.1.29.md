# Punto & Gestión 2.1.29

15 de octubre de 2026 · Corrección urgente del POS y de impresión directa.

## Agregar productos al pedido

- Corregido el error `Cannot access 'totalQty' before initialization` que impedía volver a agregar un producto desde el buscador o la entrada rápida.
- Se conservan cantidades fraccionadas por peso, variantes, precios y pedidos guardados.
- Si se cambia de pedido mientras una búsqueda o selección sigue abierta, el sistema evita agregar el producto al cliente equivocado y permite repetir la entrada.

## Impresión directa

- Corregida la llamada incompatible con Windows que provocaba el error `PyCDC ... SetStretchBltMode`.
- Controles de papel y orientación para A5 vertical, A5 horizontal y A4, sin cambiar las preferencias generales de la impresora.
- Mejor liberación de recursos y cancelación de trabajos incompletos ante errores del controlador.
- A5 vertical con carga horizontal reutiliza el PDF verificado y rota sus páginas sin volver a generar todo el documento, conservando el contenido y las copias.
- Protección contra doble clic y solicitudes repetidas. Si se pierde la conexión, se consulta la misma impresión antes de permitir otra copia.
- Mensajes que distinguen el envío confirmado a la cola de Windows de un resultado incierto. No se repite automáticamente un trabajo que pudo haberse enviado.
- Vista previa disponible cuando hace falta revisar el comprobante. Los tickets respetan el ancho de 58 u 80 mm elegido.

Incluye las mejoras de la versión 2.1.28. No incluye los cambios en desarrollo de ARCA.

La actualización conserva los datos del comercio. El instalador no contiene bases ni documentos de clientes.

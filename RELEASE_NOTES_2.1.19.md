# Punto & Gestión 2.1.19

## Ficha del cliente

- El detalle de una venta desde la cuenta corriente usa la venta vinculada al movimiento. Los ajustes sin venta asociada se presentan como movimientos y ya no intentan abrir un comprobante inexistente.
- El modal de detalle permite volver a intentar si falla la conexión y conserva abierta la ficha, sus filtros y las anotaciones que se estaban editando.
- Los artículos se muestran como texto seguro, sin interpretar nombres de productos como HTML.

## Historial del POS

- Venta, cliente, hora, productos, medio de pago, operador y totales se distribuyen en bloques legibles, también en celulares y en ambos temas.
- Se distinguen los pagos recibidos al vender y el saldo pendiente que quedó en esa operación. Un fallo al consultar el resumen diario se puede reintentar sin borrar el historial.
- Se reemplaza la etiqueta genérica «Recibo» por información del estado de la venta.

## Combos desde Acciones del POS

- Consultar y administrar las promociones desde el POS, sin salir de la venta.
- Cajeros pueden consultar y aplicar las ofertas; los permisos actuales de inventario siguen siendo necesarios para crearlas, editarlas o pausarlas.
- La lista muestra combos activos y evita duplicar una promoción que se aplica a más de una lista de precios.

## Presentación y errores

- Los cuadros de error mantienen sus acciones y resultados, con textos legibles en modo claro, oscuro, PC y celular. Los avisos breves del POS conservan su comportamiento.
- Se quitó el segundo acceso desplazable a Tutoriales; se mantiene el botón fijo del menú.

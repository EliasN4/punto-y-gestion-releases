# Punto & Gestion 2.1.16

## Caja simple y auditorias

- Caja simple muestra todos los cobros del POS y de cuenta corriente: efectivo, transferencias y Posnet (QR, debito y credito), con su detalle de origen.
- Control del cierre con efectivo contado y transferencias controladas frente a las recibidas. Las tarjetas y QR se informan sin exigir conciliacion manual.
- Fondo inicial, ingresos y retiros de efectivo, gastos con categoria y medio de pago. Los gastos bancarios y digitales no descuentan dinero del cajon.
- Cierres completos conservados en Historial y en las planillas A4, A5 horizontal y tickets de 80/58 mm; los registros guardados no cambian al modificar ventas posteriores.
- Auditorias por fecha: apertura, consulta, correccion con motivo y revisiones anteriores conservadas. Cambio de perfil o eliminacion con permisos y protecciones para no perder movimientos.
- Solo se ofrecen Caja simple y cierre operativo contra Z. Las otras modalidades mantienen sus registros anteriores disponibles.
- Categorias de gastos predefinidas y propias, adelantos al personal separados y analisis por categoria. Clasificacion de gastos anteriores sin alterar importes.
- Pantalla simple mas compacta y ordenada en claro, oscuro y celular. Sin fondos ni marcos duplicados; auditoria abierta y nueva auditoria integradas en la barra superior.
- Las planillas de Windows se abren en una ventana de la aplicacion con regreso al sistema. No se modifican los calculos del cierre contra Z.

## Estadisticas

- General reorganizado en Resumen, Clientes y Productos, manteniendo Ventas e Historial y el periodo seleccionado.
- Ventas nuevas separadas de recaudacion y cobros de deuda; comparativas, evolucion del periodo y primeros clientes/productos.
- Ranking completo de clientes con busqueda, orden, paginacion, frecuencia, ticket, ultima compra y participacion. Clientes nuevos, recurrentes y habituales sin compra reciente.
- Productos con ranking por importe y cantidad, categorias, marcas y unidades configuradas. Sin conversiones de peso inferidas por el nombre ni estimaciones fijas de ganancia.
- Se excluyen anulaciones y pagos tecnicos duplicados; los saldos anteriores no cuentan como compras nuevas. La analitica no modifica el stock.

## POS y stock opcional

- Interruptor Stock ON/OFF visible en el POS, con permisos y preferencia guardada para el comercio.
- OFF permite vender sin existencias y sin descontar inventario. ON conserva la validacion de existencias y el descuento FIFO; cambiar la opcion no borra el carrito ni modifica cantidades existentes.
- Unificado el valor inicial sin descuento para configuraciones nuevas o ausentes, respetando las preferencias ya guardadas.
- Avisos de stock como notificaciones flotantes, sin estirar el espacio de trabajo.
- Corregida la recuperacion repetida de borradores al entrar al POS. Se distinguen cambios reales del orden de las claves y se conservan ambos pedidos ante un conflicto real.
- Restaurar un pedido no guarda estados intermedios ni duplica un borrador recuperado despues de un fallo de conexion.

## Instalacion y actualizacion

- Lector de PDF y dependencia de red actualizados para corregir alertas de seguridad detectadas durante la preparacion de esta version.
- El compilador revisa tanto las dependencias declaradas como las realmente instaladas antes de empaquetar.
- Instalador completo con recursos, servicios y plantillas nuevos; conserva las mejoras anteriores de impresion de precios, modo oscuro, tutorial y celular.
- Manifiesto de actualizacion firmado y SHA-256 del instalador. Los datos del negocio permanecen fuera del paquete y se respaldan antes de migrar.

Las pruebas operan sobre bases aisladas. La emulacion movil y las verificaciones PDF no sustituyen la comprobacion final en telefonos e impresoras fisicos.

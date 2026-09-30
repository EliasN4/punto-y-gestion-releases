# Punto & Gestion 2.1.15

## Impresion y estadisticas

- Las listas imprimen los precios minoristas, mayoristas o ambos en un documento independiente del tema y la navegacion del sistema.
- En la aplicacion Windows, la lista abre una ventana propia que se puede cerrar sin cerrar el sistema. En el navegador conserva su pestaña independiente y agrega Volver a listas.
- Generacion de PDF: valida el archivo generado, reintenta con otro navegador instalado si el primero falla y conserva el PDF anterior ante un error.
- Nuevo selector de mes con nombre completo, navegacion por año y teclado, adaptado a modo claro, oscuro y celular.
- Historial de estadisticas con rango de fechas, ventas generadas, recaudacion y comparativas; cabecera adaptable con menu abierto o contraido.
- Graficos excluyen ventas anuladas; informes distinguen ventas generadas de cobros reales y deudas anteriores.

## POS, clientes y stock

- Corregida la carga y seleccion de clientes y Nuevo Pedido; busqueda cancelable con reintento y scroll movil.
- Medio de pago mostrado correctamente, reparto Todo/Resto y validacion de vuelto en pagos digitales.
- Pedidos sincronizados con versiones independientes; conflictos entre puestos conservan un borrador local recuperable.
- Stock opcional: sigue siendo posible vender sin descontar stock. Con descuento activo, las asignaciones FIFO y su restitucion al anular son exactas y la sobreventa se rechaza sin cambios parciales.
- Comprobantes y enlaces restringidos al comercio correspondiente.

## Auditoria diaria y celular

- Caja simple, movimientos, multimedio y turno/cajero conservan el cierre completo en Historial y sus movimientos detallados.
- Impresiones coherentes con cada estilo en A4, media A4 horizontal y tickets de 80/58 mm; transferencias y gastos bancarios se distinguen del efectivo.
- No se modifican los calculos de auditoria contra Z.
- Mejoras de modales, teclado, formularios, scroll y controles en iOS/Android, con verificaciones WebKit/Chromium en ambos temas.
- Pedidos: corregida una referencia inexistente y seleccion por teclado limitada a resultados visibles. Reposicion cancela la consulta del aviso al salir; barra de carteles adaptable en horizontal.
- Incluye los ajustes de modo oscuro, tutorial, soporte, configuracion, perfil y aviso de prueba comercial del sistema.

## Seguridad y actualizacion

- Restauracion de respaldos antiguos con migracion previa de esquema; actualizacion bloqueada si no se puede verificar un respaldo.
- Alcance de cambios masivos de precios validado y vista previa firmada; respuestas antiguas de busqueda descartadas.
- Instalador completo y manifiesto de actualizacion firmado; los datos del negocio permanecen fuera del paquete.

Las verificaciones usan bases aisladas. La emulacion movil y los PDF no sustituyen la prueba final en dispositivos o impresoras fisicas.

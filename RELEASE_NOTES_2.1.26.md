# Punto & Gestión 2.1.26

14 de octubre de 2026

## Cobros, cuentas y POS

- Edición de recibos y ajustes de saldo con controles de cambios simultáneos. El recibo y los medios de pago de su venta se actualizan juntos; los pagos mixtos deben sumar el importe recibido. Los saldos a favor conservan su signo.
- El POS consulta la deuda vigente antes de cobrar. Los pagos registrados durante un pedido se reflejan al abrir el cobro. También revisa precios actuales y permite verificar las diferencias antes de finalizar.
- Mejor protección ante pulsaciones repetidas, respuestas tardías y cambios de pedido. Los intentos de cobro mantienen su identidad para recuperar el resultado sin duplicar la venta.
- Cantidades fraccionarias admitidas según la unidad de venta. Los combos respetan el pedido activo y los bloqueos durante un cobro pendiente.
- La eliminación de clientes con ventas o movimientos se bloquea para conservar su historial. Las fichas vacías siguen pudiendo eliminarse.

## Anulaciones, devoluciones y caja

- Resolución explícita del dinero al anular: operación administrativa, crédito en cuenta o devolución inmediata.
- Los cobros originales se conservan. La devolución se registra una sola vez, con fecha real, medio, importe y operador, y requiere caja abierta del día.
- El importe reembolsable se limita al dinero realmente aplicado a los productos de esa compra. Los pagos de deuda anterior no aumentan ese tope.
- El efectivo devuelto modifica el cajón. Las salidas bancarias y digitales se presentan por separado para evitar descontarlas nuevamente del efectivo en el cierre contra Z.
- Los cierres guardados permanecen intactos. Los comprobantes de anulación muestran su resolución y hora local.

## Informes y recuperación de datos

- Informes y estadísticas diferencian ventas, cobros reales, devoluciones y recaudación neta. Los pagos posteriores reducen el pendiente actual sin trasladar la recaudación a otra fecha.
- Los días que sólo contienen devoluciones aparecen en el historial. Los traslados técnicos de deuda no se cuentan como dinero recibido; los importes imprimibles conservan centavos.
- Recuperación e importación de respaldos coordinadas con operaciones y tareas en curso. Las pantallas abiertas reciben un aviso y deben recargarse antes de volver a modificar datos recuperados.
- Notificaciones, actualizaciones y generación de PDF respetan ese mantenimiento. Los trabajos de una base anterior no escriben documentos sobre una base recuperada.
- Diagnóstico más claro de diferencias de cuenta, referencias históricas incompletas y registro de cobros. Los créditos coherentes son válidos y los registros grandes se identifican como revisión parcial. No se reparan ni borran datos por suposición.

## Productos, listas y carteles

- Códigos internos y de barras validados en altas, ediciones e importaciones. La numeración automática evita códigos ocupados y no toma un EAN largo como secuencia interna.
- Validaciones coherentes de importes, unidades, existencias y ajustes masivos. Los errores de un lote impiden cambios parciales. Una edición fallida conserva la foto anterior.
- Búsquedas que reconocen tildes, ñ y mayúsculas. Productos actualiza sólo los resultados necesarios; fichas y rankings usan consultas agrupadas y excluyen ventas anuladas.
- Carteles y selector de listas paginados, con selección y copias conservadas entre páginas y filtros. El regreso desde impresión mantiene los controles utilizables.
- WhatsApp permite elegir Minorista, Mayorista o Ambas, comenzando por la lista del cliente. Los documentos aclaran cuándo las variantes pueden tener precios propios diferentes del producto normal.
- Mejor presentación del catálogo en celular y comprobación de carteles destacados con código interno o de barras, nombres centrados y aviso de variantes.

## Navegación

- Menú lateral con selección violeta discreta e iconos más finos. Los controles fijos son más pequeños que los iconos de las secciones.
- El menú conserva su desplazamiento y el despliegue de Configuración. Al navegar o recargar mantiene visible la sección seleccionada, en escritorio y celular.
- Ajustes de contraste en el historial del POS y presentación del formulario de devolución en pantallas pequeñas.

Incluye las funciones de la versión 2.1.25. El nuevo A5 vertical queda para una etapa posterior de pruebas y no forma parte de esta publicación. Los perfiles por rubro y la conversión automática de packs siguen postergados.

## Comprobaciones previas

Las correcciones tienen evidencia combinada de 231 casos distintos aprobados y 9 omitidos; no es una única ejecución final. Se realizaron comprobaciones de sintaxis y revisiones visuales con datos ficticios en modos claro, oscuro y tamaños móviles emulados. El instalador se prepara desde código versionado sin bases, respaldos ni datos privados del comercio. No se certifican teléfonos o impresoras físicos.

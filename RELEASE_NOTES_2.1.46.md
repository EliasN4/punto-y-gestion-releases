# Punto & Gestión 2.1.46 · 2 de noviembre de 2026

Corrección urgente de impresión de tickets de 80 y 58 mm.

- Se acepta el ancho imprimible que informan controladores de rollo: por ejemplo, 72/72,1 mm para rollos de 80 mm y 48 mm para rollos de 58 mm.
- Se negocia correctamente el tamaño personalizado con Windows y se aprovechan los formatos disponibles del controlador.
- Los tickets que exceden el largo fijo continúan completos, sin reducir toda la venta a letra diminuta. Se buscan espacios en blanco entre el contenido para dividir las páginas.
- Se conservan la impresora elegida, la impresión directa y la protección contra envíos duplicados. No se cambia automáticamente a ESC/POS.

Sin cambios en la base de datos, la configuración de ARCA ni la carpeta habitual de instalación. Validado con controladores simulados y documentos PDF reales; la impresora física de la clienta requiere comprobarse tras actualizar.

# Punto & Gestión 2.1.18

## Guardado e historial de Auditoría diaria

- Los controles de Caja simple y Caja contra Z se guardan en la base de datos, con confirmación visible y recuperación al volver o reiniciar.
- El historial muestra cajas abiertas, cerradas y en corrección. Una caja abierta conserva sus controles; el cierre definitivo mantiene su planilla guardada.
- Los cierres Z consultan los importes conservados al cerrar, evitando que ventas o cambios posteriores alteren el resultado histórico.
- Un conflicto entre ventanas se informa antes de sobrescribir controles. Los errores de conexión conservan los campos para reintentar.
- Reintentar un gasto, aporte, retiro o transferencia después de perder la respuesta no duplica el movimiento.
- Se protege el reinicio de cajas que ya contienen información y el apagado con controles pendientes de confirmar.

## Clientes en agenda y POS

- Alta compartida desde Clientes y POS: solo el nombre es obligatorio; perfil, negocio, ubicación, contacto y datos fiscales siguen siendo opcionales.
- Títulos y campos legibles en claro y oscuro; adaptación a celular vertical y horizontal, con scroll y acciones accesibles.
- Perfil modernizado con datos de contacto, ubicación, información fiscal, métricas, compras, productos y anotaciones.
- Guardar anotaciones mantiene el perfil abierto. Los errores conservan el texto y permiten reintentar; editar y cancelar vuelve a la ficha.

## Impresión A5 horizontal y A4

- A5 horizontal (210 × 148 mm) para el POS. Cada copia comienza en su propia hoja; el pie del comprobante no genera una hoja vacía adicional.
- A5 y A4 conservan sus márgenes internos y eliminan el título, dirección, fecha y numeración adicionales del navegador.
- Los PDF anteriores se regeneran cuando cambian el diseño, las copias o el contenido del comprobante.
- La impresión directa utiliza las páginas reales del PDF, con papel y orientación configurados para ese trabajo, sin modificar las preferencias generales de la impresora.
- Se informa un error si el controlador rechaza el papel u orientación; no se presenta un comando de navegador como impresión confirmada.

La prueba para instalaciones nuevas sigue siendo de 30 días. Las licencias, fechas de pruebas existentes y datos del negocio se conservan. Esta actualización incluye las mejoras de 2.1.17.

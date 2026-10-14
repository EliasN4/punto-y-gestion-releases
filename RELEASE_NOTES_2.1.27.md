# Punto & Gestión 2.1.27
14 de octubre de 2026 · Corrección urgente de ventas por peso.

- Corregida la venta de 0,300 kg y otras fracciones cuando una unidad antigua de peso, longitud o volumen conservaba el indicador de enteros.
- Modal de cantidad, entrada rápida (0.300*30 / 0,300*30), edición del carrito, pedidos guardados y validación del cobro usan el mismo criterio de unidad de venta.
- Las cantidades por unidad, caja o pack mantienen su configuración; la presentación Madeja no cambia la unidad ni convierte existencias.
- Stock inicial, variantes, ajustes e importaciones reconocen las unidades de medida fraccionables.
- Corregida la opción de API de producto para informar el permiso de decimales.
- Corregida la suma repetida de cantidades del carrito para evitar residuos de coma flotante en pantalla.
- El modal de Pedidos mantiene su altura y posición al filtrar, incluso sin resultados.
- Corregida la llamada al controlador de impresión de Windows.

La actualización conserva los datos del comercio. No se empaquetan bases, copias de seguridad, documentos de usuarios ni claves privadas. La base real del puerto5000 no se abrió ni modificó durante la preparación.

A5 vertical sigue en la etapa local de pruebas acordada y no se incorpora a esta corrección urgente.

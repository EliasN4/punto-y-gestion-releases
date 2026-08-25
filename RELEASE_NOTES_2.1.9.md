# Punto & Gestion 2.1.9

## Incluye

- Importacion de listas de precios desde Excel, CSV y PDF de texto.
- Vista previa antes de crear productos, con seleccion de filas, mapeo de
  columnas, precios y categoria.
- OCR local incluido en el instalador para PDFs escaneados compatibles.
- Correcciones de pagos a cuenta, recibos, caja diaria y comprobantes A5.
- Correcciones de busqueda y entrada rapida del POS.
- Mejoras de catalogo, categorizacion masiva y fichas de productos.
- Compatibilidad de actualizacion desde el manifiesto firmado del sistema.

## Importante

La emision fiscal ARCA permanece bloqueada y fuera del alcance comercial de
esta version. Los comprobantes internos no tienen validez fiscal.

## Verificacion

La compilacion se valido con la suite automatizada, `pip check`, auditoria de
dependencias y guardia de datos privados. El instalador contiene el runtime
OCR local y no incluye la base de datos del negocio usado para las pruebas.

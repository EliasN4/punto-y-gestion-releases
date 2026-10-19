# Punto & Gestión 2.1.34 · Primeros pasos e impresión

Esta edición permite operar el POS interno. La facturación electrónica de ARCA continúa deshabilitada para clientes.

## Si ya usás el sistema

1. Terminá la venta en curso y guardá una copia de seguridad desde Seguridad.
2. Cerrá Punto & Gestión desde su ventana habitual.
3. Ejecutá el instalador de la actualización y volvé a abrir el sistema.
4. Comprobá que aparecen tu comercio, tus productos y tus clientes. No vuelvas a registrar el negocio. Si aparece un alta nueva inesperada, detené la configuración y pedí asistencia para revisar la carpeta de datos.

## Si es tu primera instalación

1. Abrí Punto & Gestión y completá los datos de tu comercio.
2. Elegí el PIN del propietario. Conservá ese PIN: se usa para autorizar acciones dentro del sistema.
3. Cargá tus productos y revisá sus precios y unidades antes de empezar a vender.
4. Configurá la impresora y realizá una prueba antes de cobrar la primera venta.

## Preparar tickets de 58 u 80 mm

1. Instalá el controlador del fabricante de la impresora en la PC donde corre Punto & Gestión. Primero comprobá que Windows puede imprimir una página de prueba.
2. En Caja, abrí Configuración y entrá en Impresión.
3. Elegí **Ticket 58 mm** o **Ticket 80 mm**, según el rollo y la impresora.
4. En **Cómo imprimir el ticket**, comenzá con **Windows · mayor compatibilidad**.
5. En **Impresora del comercio**, seleccioná la impresora térmica correcta. Evitá dejar elegida una impresora PDF o una impresora de hojas si querés un ticket físico.
6. Pulsá **Imprimir prueba**. La prueba usa lo que elegiste en ese momento, aunque todavía no hayas guardado. Deben verse completos el rectángulo, los acentos y los números. Esta prueba no registra una venta.
7. Pulsá **Guardar cambios**. El formato y la impresora quedan guardados para el comercio; el modo Windows o ESC/POS se guarda para el dispositivo desde el que estás trabajando.

Desde un celular conectado al sistema, la impresión se envía a la impresora de la PC que ejecuta Punto & Gestión. No hace falta cargar otra venta para reimprimir: usá Imprimir en el historial.

## Si no sale el ticket

- **Windows tampoco imprime:** revisá conexión, papel, estado de la cola y controlador del fabricante.
- **La impresora no acepta el tamaño:** revisá el ancho del rollo en las propiedades del controlador. El sistema detiene el envío antes de imprimir un documento con otro tamaño. Algunos controladores requieren definir el formulario del rollo en Windows.
- **El modo rápido no imprime o muestra símbolos:** volvé a Windows. **ESC/POS · rápido** es una alternativa para impresoras que admiten ese lenguaje; probalo antes de usarlo para ventas. Su tabla de caracteres está documentada por [Epson](https://download4.epson.biz/sec_pubs/pos/reference_en/escpos_dm/esc_lt.html).
- **El sistema no pudo confirmar el envío:** mirá la cola de Windows y el papel antes de solicitar otra copia. No registres nuevamente la venta. El sistema conserva el intento y evita reenviarlo automáticamente.
- **Necesitás revisar el resultado:** abrí la vista previa del comprobante y comprobá el formato elegido. Si imprimís desde el navegador, seleccioná el papel del rollo y desactivá encabezados y pies del navegador si se muestran.

Para asistencia, indicá la versión del sistema, el modelo de impresora, el ancho del rollo, el modo Windows/ESC/POS y el mensaje que aparece. No compartas PIN ni claves.

## Facturación electrónica

Esta actualización no habilita Caja fiscal ni permite emitir comprobantes de ARCA. La guía de conexión se está preparando y probando en la edición privada. Cuando se habilite para clientes, será necesario completar y verificar la conexión de cada comercio; una actualización por sí sola no autoriza a facturar.

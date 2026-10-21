# Punto & Gestión 2.1.37 · Guía para empezar y seguir trabajando

Versión 2.1.37. La conexión fiscal se prepara y verifica para cada comercio. Esta guía te acompaña a actualizar, empezar y usar el sistema.

## Si ya tenés Punto & Gestión

1. Terminá la operación en curso. Desde **Seguridad y copias**, creá y descargá una copia de seguridad; guardala fuera de la carpeta del programa.
2. Cerrá el sistema desde su ventana habitual.
3. Ejecutá el instalador que te entregue quien te acompaña y seguí sus indicaciones. Si Windows pide permiso para actualizar el programa, comprobá que sea el instalador esperado.
4. Volvé a abrir Punto & Gestión. Deben aparecer tu comercio, productos y clientes habituales. **No hace falta registrar otra vez el negocio.** Si aparece una pantalla de alta inesperada, pedí asistencia para revisar la ubicación de los datos antes de completarla.

Las mejoras no requieren volver a cargar tus ventas ni tu catálogo. Una actualización tampoco conecta automáticamente tu CUIT con ARCA.

## Si lo abrís por primera vez

1. Completá los datos de tu negocio y elegí el PIN del propietario. Ese PIN es del sistema; es distinto de tu clave fiscal.
2. Al terminar vas a ver **Tu negocio, paso a paso**. Empezá por una tarjeta. **Ver cómo se hace** abre la explicación; **Ir a la sección** te lleva al lugar donde hacés la tarea.
3. Revisá nombre y contacto, cargá un producto, comprobá su unidad y precio, probá la impresora, conocé Clientes y prepará Caja Simple y tus copias.
4. Volvé cuando quieras desde el menú → **Tutoriales** → **Empezar sin apurarte**.

**Datos cargados** significa que el sistema encontró información del negocio. No asegura que el precio sea correcto o que el papel haya salido bien. Las pruebas de impresión y caja quedan **Para revisar** porque las comprobás vos.

La campana ofrece sugerencias según tu perfil y lo que ya usaste. Podés abrir la guía, posponerla o marcarla como hecha. Leer o completar una guía no carga ventas, abre cajas ni imprime por vos.

## Vender productos por metro

En **Productos → Nuevo producto**, elegí **Metro (m)** en **Unidad de venta**.
Cargá el precio de un metro y las existencias en metros. Por ejemplo: con un
precio de $1.200 por metro, una venta de 1,25 m suma $1.500 antes de descuentos
o recargos. En el POS podés ingresar fracciones como 0,25 m, 0,50 m y 1,25 m.
Las variantes también pueden tener su propio stock y precio por metro.

Las instalaciones anteriores incorporan Metro al actualizar si todavía no lo
tenían. No necesitás volver a crear los productos existentes. Para un artículo
que ya vendías, revisá su unidad antes de cambiarla: el precio y el stock deben
corresponder a esa medida. Los registros anteriores conservan su unidad histórica.

El formulario usa una sola **Unidad de venta** y ya no pide Presentación. Si antes
habías guardado una descripción de presentación, se conserva al editar el producto.

## Dejar listo el ticket de 58 u 80 mm

Hacé esta preparación en la PC que ejecuta Punto & Gestión, antes de atender:

1. Instalá la impresora con el controlador del fabricante. Comprobá primero que imprime una página de prueba desde Windows.
2. En **Caja → Configuración → Impresión**, elegí **Ticket 58 mm** o **Ticket 80 mm** según el rollo de tu impresora.
3. En **Cómo imprimir el ticket**, empezá con **Windows · mayor compatibilidad**. En **Impresora del comercio**, elegí la impresora térmica correcta.
4. Pulsá **Imprimir prueba**. No registra una venta. Revisá en el papel que entren completos el marco, los números y los acentos.
5. Cuando esté bien, pulsá **Guardar cambios**. La prueba usa la selección actual, aunque todavía no la hayas guardado.

**ESC/POS · rápido** es una alternativa para impresoras compatibles; usalo después de comprobarlo con tu modelo. El formato y la impresora se guardan para el comercio; el modo Windows/ESC/POS corresponde al dispositivo desde el que trabajás. Desde el celular, el sistema envía el trabajo a la impresora de la PC del negocio.

El aviso **Preparando impresión** permite pulsar **Seguir trabajando** mientras se envía el comprobante a la cola de Windows. Cerrar ese aviso no cancela el envío.

Si no sale el papel, mirá primero el mensaje y la cola de Windows. Si el resultado no está confirmado, revisá la cola y la impresora antes de pedir otra copia. **No vuelvas a registrar la venta.** Una venta guardada se reimprime desde **Historial**.

Si el controlador rechaza el tamaño, revisá el ancho del rollo y el formulario de papel en sus propiedades. Si necesitás ayuda, indicá modelo de impresora, versión del sistema, ancho de rollo, modo de impresión y mensaje exacto.

Se verificó la generación de ambos tamaños en el programa compilado. Queda pendiente la prueba de papel con la impresora y el controlador de cada comercio.

## Caja común y Facturación ARCA

En Caja común, la tarjeta muestra el cliente del pedido o **Consumidor final** si no elegiste uno. Al pulsar **Facturación**, aparece **¿Cambiar al POS fiscal?**: elegí **Sí, cambiar al POS fiscal** para entrar o **Seguir en caja** para quedarte. El modo fiscal tiene un fondo **cobre** en toda la pantalla, tanto en claro como en oscuro. Cambiar de modo no emite una factura.

- **Caja común → Historial:** ventas internas y sus acciones.
- **Modo fiscal → Comprobantes:** facturas y notas de crédito de ARCA, con su numeración fiscal.
- Si el cliente cambia cómo te pagó una venta interna, buscala en Historial y abrí **Anular → Corregir medio de pago**, cuando esté disponible. Elegí el medio real y autorizá según tu perfil. Cambiar el cobro no requiere anular la venta.

## Conectar tu comercio con ARCA

Abrí **Configuración → Facturación**. La guía tiene cuatro pasos; podés guardar y continuar después desde la misma PC. Si ya dice **Facturación habilitada**, revisá sus datos en **Ver conexión fiscal**: no repitas el alta.

Tené a mano la constancia de inscripción y acceso autorizado a ARCA. El CUIT emisor es el del comercio, aunque quien ingrese sea su titular o representante.

### 1. Tu comercio

Copiá CUIT, razón social, domicilio, condición de IVA, Ingresos Brutos e inicio de actividades. Revisá la constancia. Si todavía no tenés el punto de venta, dejalo vacío y completalo en el paso 3. Pulsá **Guardar y continuar**.

### 2. Certificado

El sistema prepara una solicitud pública, llamada **CSR**, para entregarla a ARCA. Seguí el botón indicado para prepararla y descargarla. Si ya reconoce un certificado cargado para ese comercio, continuá a revisar la conexión; no prepares otro sin necesidad.

### 3. En ARCA

Abrí una tarea por vez. La guía permite copiar nombres y tiene enlaces oficiales con pantallas:

1. En **Administración de Certificados Digitales**, elegí el comercio y usá la solicitud del paso 2 para obtener el certificado público.
2. En **Administrador de Relaciones de Clave Fiscal**, autorizá **Facturación Electrónica (WSFE)** para el CUIT del comercio y el certificado correcto.
3. En **Administración de puntos de venta y domicilios**, revisá o creá el punto para factura electrónica por **Web Services** de este sistema. Elegí la actividad y el domicilio reales y completá su número en el paso 1. Si la actividad te genera dudas, revisala con tu contador.

Las casillas de la guía guardan tu avance. La comprobación de conexión se hace en el siguiente paso.

### 4. Conexión

Importá el certificado público descargado de ARCA y pulsá **Verificar con ARCA**. Esta consulta comprueba la conexión y el punto de venta; no emite facturas ni mueve caja o stock.

Cuando el sistema lo permita, revisá CUIT, razón social y punto de venta, marcá la confirmación e ingresá el **PIN del propietario de Punto & Gestión**. Pulsá **Habilitar facturación** y esperá el resultado. El estado **Facturación habilitada** permite continuar a Facturar.

La clave fiscal se escribe solamente en ARCA; el PIN, dentro de Punto & Gestión. Cada negocio conserva sus propios certificados y autorizaciones.

### Completar un receptor por CUIT

La consulta automática usa un permiso separado: **Consulta de Constancia de Inscripción**, asociado al mismo comercio y certificado. La ayuda del paso 3 explica cómo vincularlo. Si falta ese permiso, puede estar habilitada la facturación y quedar pendiente la consulta por CUIT; podés completar y revisar manualmente al receptor.

Antes de emitir, revisá los datos e importe reales. El sistema propone el tipo de comprobante según emisor y receptor; las dudas sobre el encuadre impositivo se revisan con el contador. No hace falta emitir una factura real ficticia para probar la conexión.

## Encontrar y entregar una factura

En **Comprobantes**, buscá por receptor o número. Podés verla, descargar el PDF, imprimir y abrir las acciones disponibles de nota de crédito. Una nota de crédito conserva el vínculo con la factura original y requiere su propia autorización.

En la aplicación de escritorio, al descargar, el aviso muestra la ubicación y ofrece **Abrir PDF** y **Abrir carpeta**. Al imprimir, elegí el formato de tu impresora. Para WhatsApp, revisá el destinatario y adjuntá el PDF: abrir el borrador no adjunta el archivo automáticamente ni confirma su entrega.

## Para quien acompaña el alta de otro comercio

La skill **pyg-alta-arca-asistida** contiene el recorrido y los casos de recuperación. En una sesión con esa skill instalada y acceso autorizado al sistema del cliente, podés iniciar con:

> Usá $pyg-alta-arca-asistida para conectar Punto & Gestión con ARCA para este comercio. La instalación del cliente está accesible por el canal autorizado y el titular va a iniciar sesión directamente en ARCA. Revisá lo existente, retomá el avance y verificá la conexión y la consulta por CUIT sin emitir facturas ni modificar ventas, caja, stock o clientes. No reutilices datos de otro comercio.

Abrir ARCA en tu PC no da acceso por sí solo al sistema instalado en la PC del cliente. Al terminar, dejá anotados comercio, punto, fecha de comprobación, estado de emisión y consulta por CUIT, y cualquier tarea pendiente. No incluyas claves ni PIN.

Consultá también [las notas de esta versión](RELEASE_NOTES_2.1.37.md).

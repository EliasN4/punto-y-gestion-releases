# Punto & Gestion 2.1.11

## Interfaz y navegacion

- Navegacion lateral organizada por operacion, clientes, catalogo, analisis, ayuda y configuracion, con buscador compacto y acceso QR para celular.
- Perfil del negocio centraliza identidad, comprobantes y seguridad. Gestion del Sistema reune licencia, actualizaciones y copias.
- Productos, Clientes y Cuentas Corrientes comparten encabezados, controles, colores y modales renovados.
- Caja Diaria pasa a llamarse Auditoria Diaria y presenta un resumen y formulario mas compactos.
- Lista de precios aprovecha el ancho disponible con herramientas alineadas y desplazamiento de la vista previa.
- Ajustes en Estadisticas, carteles, historial de precios y presentacion de importes.

## Uso desde el celular

- POS con un unico encabezado, acciones circulares, acceso a WhatsApp y cantidades decimales legibles.
- Drawer con cierre por fondo o boton y herramientas inferiores accesibles.
- Modales de clientes, pedidos y cantidades ubicados arriba, con desplazamiento y acciones accesibles.
- Mejoras de espacio para teclado, medios de pago, PAGAR y FINALIZAR.
- Fichas y formularios de Productos y Clientes adaptados a pantallas pequenas.

## Integridad y continuidad

- Validacion de importes y cantidades en el servidor y proteccion frente a reintentos de ventas y pagos.
- Mejoras de concurrencia en cuentas corrientes, numeracion de recibos e importacion de productos.
- Copias verificadas, recuperacion y manejo de errores de licencia mas robustos.
- Proteccion CSRF, limites persistentes de acceso y escape de contenido dinamico.
- Correccion del arranque de la ventana Windows al conectar la recuperacion de WebView2.
- El paquete excluye explicitamente los logos cargados y documentos generados del entorno de desarrollo.

El instalador conserva los datos locales del comercio. Realizar una copia de seguridad antes de actualizar.

La interfaz movil fue revisada en navegador con anchos de 390 y 430 px y altura reducida para simular el teclado. Esto no reemplaza una prueba en dispositivos iOS y Android reales.

ARCA permanece fuera del alcance comercial de esta version.

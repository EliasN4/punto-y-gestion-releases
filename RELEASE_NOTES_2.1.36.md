# Punto & Gestión 2.1.36

- Cuentas corrientes carga sus datos por grupos y reutiliza el libro para mostrar perfiles y recibos. Evita consultas repetidas por cliente y por pago.
- Corregido el detalle de deudas que podía fallar al mostrar el número del comprobante; conserva separados el movimiento, el remito y la factura fiscal.
- La consulta heredada de pendientes respeta anulaciones, ajustes y pagos del estado de cuenta.
- El contador de clientes activos usa el mismo criterio de compra del directorio.
- El editor de productos descarta respuestas tardías de otro producto o de una ventana cerrada. La carga de colores y partidas evita consultas por cada variante.
- El gráfico horario excluye los recibos que sólo trasladan saldo anterior y coincide con los totales de ventas.
- Estadísticas muestra la referencia visible del comprobante y protege el detalle frente a respuestas tardías y contenido que debe presentarse como texto.

Incluye las mejoras de impresión, Caja Simple, guías y conexión ARCA por comercio de las versiones anteriores. Cada negocio conserva sus propios datos y permisos fiscales.

Se instala encima de la versión anterior en la misma carpeta. No modifica las reglas de asignación de pagos ni reescribe ventas, saldos o fechas históricas.

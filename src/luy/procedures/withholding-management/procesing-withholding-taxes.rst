.. |Documentos Relacionados Barra de Herramientas| image:: resources/documentos-relacionados-barra-de-herramientas.png

**Cálculo de retenciones y creación de Resguardos a Proveedores**
=================================================================

**Cálculo de Retenciones automático**
-------------------------------------

Cada vez que se completa un Documento por pagar (Factura Proveedor o
Nota de Crédito Proveedor), automáticamente el sistema verifica si el
Proveedor al que se ingresó la factura tiene alguna retención definida,
(esto lo podemos ver en las ventanas “Definición de retenciones” o
ventana “Socio del Negocio” pestaña "Retenciones".

Si tiene una retención definida y la factura cumple con la definición de
la misma, una retención será generada automáticamente por el importe
correspondiente. Para poder acceder a ella desde el Documento por Pagar
podremos navegar desde los Documentos relacionados en la barra de
herramientas.

|Documentos Relacionados Barra de Herramientas|

Esta retención se completa de forma automática al completar el Documento
por pagar.

**Generar Resguardos Masivos**
------------------------------

Una vez con las retenciones generadas automáticamente a medida que se
vayan generando los Documentos por Pagar, para generar los resguardos se
deberá buscar aquellas Retenciones que aún no hayan sido generados sus
correspondientes resguardos para generarlos.

Para generar los resguardos podrémos realizarlos mediante el proceso de
Generar Resguardos Masivos. Realizaremos la búsqueda inteligente, la
cual permite filtrar por:

-  Socio del Negocio (Proveedor)
-  Organización
-  Fecha del documento
-  Retención
-  Factura fuente
-  Tipo de retención

Una vez seleccionemos todas aquellas retenciones sobre las cuales se
desea generar un resguardo, procederemos a correr el proceso, el cual va
a generar los documentos "Resguardo" requeridos a partir de los
“Documentos Retención” Completos.

Estos resguardos generados los vamos a visualizar en la ventana
“Resguardos”.

Tener en cuenta que los Resguardos son CFE y se generarán siempre en la
moneda pesos uruguayos convertidos según Tasa de Cambio de la fecha del
Documento por Pagar.

**El formato de impresión de Resguardo podrémos visualizarlo desde el proceso del Documento “Impresión de resguardo”**

**¿Cómo se Asigna un Resguardo?**
---------------------------------

Un Resguardo se agrega en un Recibo de Pago como una Nota de Crédito
Proveedor, descontando el Importe a Pagar o en una Selección de pagos.

**Contra Resguardos**
---------------------

Cuando se anula un resguardo se genera un reverso (contra-resguardo) que
tendrá la siguiente secuencia y será el negativo del original.

**Creación de Resguardo Recibido**
----------------------------------

Los resguardos que nos realiza un cliente y nos lo descuenta en un
Recibo de Cobro los ingresaremos desde la ventana Recibo de Cobro.

Aquí seleccionaremos el botón Cobro Contado y completaremos los campos
seleccionando “Resguardo” en el campo Regla de pago, y el banco
“Retenciones Recibidas” en el campo Cuenta Bancaria.

Este banco tiene una definición contable que va a mover la cuenta de
"Retenciones Recibidas" (Ver definición de Cuentas Bancarias).

|Documentos Relacionados Barra de Herramientas|
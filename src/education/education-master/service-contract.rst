.. |Pestaña Lineas del Contrato| image:: resources/contract-lines-tab.png
.. |Pestaña Descuentos de Linea| image:: resources/discounts-tab.png
.. |Pestaña Cuotas| image:: resources/fee-tab.png
.. |Cabezal Contrato de Servicio| image:: resources/service-contract-window-header.png

**Contrato de Servicio Educación**
==================================

El Contrato de Servicios resume en un documento la representación de
determinado acuerdo realizado entre una Institución Educativa y un
Alumno y regulará condiciones para las transacciones a realizar entre
ambos.

Este se generará definiendo en Socio del Negocio al Alumno y en el campo
"Responsable de Pago" al responsable de pago que se define en la
Familia. La Factura por los servicios brindados en cada contrato será
generada al Responsable de Pago definido.

**Cabezal ventana de Contrato de Servicio**
-------------------------------------------

|Cabezal Contrato de Servicio|

**Socio del Negocio**
~~~~~~~~~~~~~~~~~~~~~

**Alumno:** Identifique la contraparte del contrato.

**Responsable de pago:** Seleccionar a quién se le facturará este
contrato. En este campo se mostrará además del Alumno, al miembro de la
familia del Alumno que esté definido como Responsable de Pago (Check
Responsable de Pago=Y").

**Familia:** Se deberá definir la Familia a la que pertenece el
Estudiante. Este dato es utilizado para definir el "Responsable de Pago"
y también para la definición de los Descuentos por Hijos.

**Curso:** Se podrá identificar el Curso al que pertenece el Alumno.
Este dato podrá irse actualizando año a año a medida que se avance en el
curso

**Fechas del Contrato**
~~~~~~~~~~~~~~~~~~~~~~~

**Fecha del Documento:** Fecha en que se suscribe el Contrato.

**Fecha Inicio Contrato:** Ingresar la fecha de comienzo del servicio y
facturación.

**Fin Programado Contrato:** Ingresar la fecha de finalización del
servicio y facturación.

**Unidad de Duración:** Unidad de facturación del servicio, generalmente
es "Mes".

**Duración:** Duración del Contrato en Unidad de duración.

**Facturación**
~~~~~~~~~~~~~~~

**Lista de Precio:** Seleccionar la Lista de Precios que le corresponda.

**Moneda:** Es definida por la lista de precios.

**Regla de Pago:** Cheque, deposito, efectivo, etc.

**Término de pago:** Inmediato, 10 días.

**Pestaña Líneas del Contrato**
-------------------------------

|Pestaña Lineas del Contrato|

Se define los distintos Productos/Servicios que intervienen en el
Contrato de Servicios de manera recurrente.

-  **Producto:** Servicio que se brinda, el año que corresponde
-  **Actividad:** Será el Centro de Costo que se utilizará para
   identificar dicho Curso y comparar ingresos y Gastos existentes.
-  **Fechas:**

   -  Recurrente (SI/NO): SI
   -  Tipo de Frecuencia:

      -  Semana
      -  Mes (SI)
      -  Trimestre
      -  Año

   -  Frecuencia: 1 (mes)

-  **Totales:**

   -  Precio Neto: Precio a facturarse cada vez. Dependerá de la forma
      en que se definan los descuentos. Pueden ser dos:

      -  En la línea del contrato: Será calculado según el % de
         Descuento que se defina en la línea. El Precio puede tener
         varios dígitos decimales para que el importe impuesto incluido
         sea redondo.
      -  Como línea negativa (línea de descuento a parte): Este precio
         será simplemente el precio de lista del producto.

   -  Impuesto: Tasa de Impuesto que tendrá el Producto seleccionado. \* Precio de Lista: Precio del
Producto definido en la Lista de Precios. \* % Descuento: \* En el caso
que el descuento se defina en la línea del contrato este se definirá
aquí mediante el Proceso de Actualizar Descuento de Líneas de Contrato.
\* En el caso que el Descuento se defina como línea negativa, este campo
indicará "0".

**Pestaña Descuentos**
----------------------

Un Contrato de Servicios podrá contar con más de un Descuento
establecido, la Suma de ambos descuentos se podrán aplicar de dos
maneras distintas: como línea negativa o en la línea del contrato.

Esta pestaña podrá actualizar de manera automática desde el proceso
"Crear Descuento de contrato" para que se acualice el Descuento según
cantidad de hermanos.

Adicionalmente podrá definir un descuento especial pero de manera manual
seleccionando el tipo, el porcentaje que corresponda y la Categoría de
Producto sobre la cuál se deberá aplicar el descuento.

|Pestaña Descuentos de Linea|

**Pestaña Cuotas**
------------------

Las cuotas podrán visualizarse con descuento incluido (en el caso que se
definan descuentos en la línea del contrato) o con descuento aparte (en
el caso que se definan descuentos como línea negativa) .

Para poder visualizar desde la Ventana de Contrato de Servicios todas
las cuotas y descuentos que el Contrato ya tiene generados se debe ir a
la pestaña “Cuotas” debajo de la Pestaña “Descuento de Líneas”.

Una vez facturado se agregará el Check de Facturado a la línea de cuota
misma como a la línea de su descuento.

|Pestaña Cuotas|
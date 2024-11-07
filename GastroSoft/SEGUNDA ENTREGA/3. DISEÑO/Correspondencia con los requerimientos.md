# Correspondencia con los requerimientos

## Requerimientos Funcionales:
* **RF-001 Registrar pedidos. El sistema permitirá al mesero registrar los pedidos realizados por el cliente.**
El mesero puede registrar los pedidos de un cliente por medio de su interfaz, asociando a cada cliente con un número de mesa, el proceso inicia desde que el mesero selecciona el número de mesa hasta que envía a la comanda el pedido.

* **RF-002 Editar platilllos. El software permitirá que el mesero pueda editar los ingredientes en los platillos y adaptarlo a los gustos y necesidaddes de cada cliente. El cliente también podrá realizar está acción por medio de la aplicación móvil.**  
En la interfaz del mesero y el cliente, cada que se seleccione un platillo para agregarse a la orden desplegará una ventana que muestra los ingredientes que contiene el platillo proporcionando al ususario la opción de reducir su cantidad, aumentarla o eliminar el ingrediente definitivamente.

* **RF-003 Determinar que un pedido ha sido completado. El software notificará al mesero que realizó el pedido una vez que este haya sido completado.**  
Un pedido se ha completado una vez que se haya pagado la cuenta, el mesero cuenta con una opción de finalizar que se encuentra al final de todo el proceso con el que se asegura que el el servicio ha sido completado.

* **RF-004 Proporcionar un mapa de las mesas del establecimiento. El software mostrará un mapa de las mesas del establecimiento y señalará el estado de estas (libre, ocupada, reservada o en espera de su orden.**
La interfaz del recepcionista cuenta con la opción que le permite visualizar el mapa del establecimiento con un código de colores que le muestra el estatus de cada mesa.

* **RF-005 Proporcionar stock de ingredientes. El software permitirá ver el inventario de insumos y productos en el establecimiento.** 
La interfaz del ropietario cuenta con un apartado que le permite acceder al inventario del establecimiento, mostrando información como el nombre del producto, costo del mismo, la cantidad que queda disponible y la fecha de caducidad.

* **RF-006 Notificar cuando un insumo esté agotándose. El sistema dará un aviso cuando haya poca cantidad de un insumo para prevenir que estos se agoten y no se pueda preparar algún platillo.**  
El propietario podrá visualizar el estatus de cada producto desde el inventerio y le notificará la necesidad de reabastecerlo.

* **RF-007 No permitir realizar un pedido si un platillo está agotado El sistema no permitirá que un platillo sea registrado en un pedido si este ha sido registrado como “agotado” en el sistema.** 
Si el mesero o el cliente intentan registrar un platillo que utiliza algún producto que no está disponible el registro será rechazado.

* **RF-008 Información de ingresos y egresos del restaurante El software registrará las ventas realizadas en el establecimiento, así como los gastos para que al finalizar el mes proporcione estadísticas de ganancias del negocio.** 
Las interfaces del mesero y el cliente cuentan con la opción de realizar los pagos, los cuales se registrarán y almacenarán para que posteriormente el propietario pueda visualizar desde su interfaz los registros y estdísticas de los mismos.


## Requerimientos No funcionales:
  * **RNF-001 Intuitivo El software permitirá que todas las personas que estén en contacto con él logren una fácil interacción.**
  Todas las interfaces cuentan con botones de colores para cada opción, resaltando las funciones principales en  cada ventana.

  * **RNF-002 Capacidad El software podrá registrar N número de pedidos en las horas pico sin presentar problemas.**
   El software podrá realizar una gran cantidad de pedidos sin problema ya que cada orden será asociada con un usuario específico.

  * **RNF-003 Rapidez El sistema deberá responder de forma rápida para evitar la demora en la toma de pedidos.**
  El sistema es intuitivo y fácil de manejar por lo que permitirá el registro rápido de una orden.

  * **RNF-004 Disponibilidad El sistema estará disponible en el horario laboral del restaurante.**
    El sistema se inicializará desde que el personal realice su incio de sesión hasta que la finalice.

  * **RNF-005 Seguridad El software tendrá un sistema de autenticación para acceder a él.**
   Cada interfaz cuenta con la sección de incio de sesión que requiere de un  usuario y contraseña para acceder al sistema

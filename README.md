# Prueba Practica Proceso de Selección Ecx-labs

# EJERCICIO 1

1. Consultar el valor de cambio de una de las siguientes opciones en 5 días diferentes de la siguiente página https://finance.yahoo.com/:
  Euros a dólares
  Pesos chilenos a dólares
  Soles a dólares
2. Almacenar los datos de valor de cambio en una base de datos.
3. Desarrollar un prototipo de API REST que permita consultar el valor de cambio almacenado en la base de datos
4. Al finalizar el proceso que golpee el webhook con URL https://webhook.site/7fe30324-a42c-480c-82c2-343664d57232 con un body que incluya el valor de cambio consultado

# EJERCICIO 2

1. Desarrollar una función Lambda que consulte a la página https://dweet.io/follow/thecore los valores de “temperature” y “humidity” cada minuto durante 15 minutos
2. Almacenar los valores consultados en una base de datos
3. Pasados los quince minutos, que la función Lambda de forma automática golpee el webhook URL https://webhook.site/7fe30324-a42c-480c-82c2-343664d57232 con un body que incluya todos los valores almacenados en la base de datos

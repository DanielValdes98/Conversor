# Project-Conversor

![Image text](https://github.com/DanielValdes98/Project-Conversor/blob/master/img/menu-seleccion.png)

Se solicitó crear un conversor de divisas utilizando el lenguaje Java. Las características solicitadas por nuestro cliente son las siguientes:

**Requisitos:**

El convertidor de moneda debe:

      - Convertir de la moneda de tu país a Dólar
      - Convertir de la moneda de tu país  a Euros
      - Convertir de la moneda de tu país  a Libras Esterlinas
      - Convertir de la moneda de tu país  a Yen Japonés
      - Convertir de la moneda de tu país  a Won sul-coreano

Recordando que también debe ser posible convertir inversamente, es decir:

        - Convertir de Dólar a la moneda de tu país
        - Convertir de Euros a la moneda de tu país
        - Convertir de Libras Esterlinas a la moneda de tu país
        - Convertir de Yen Japonés a la moneda de tu país
        - Convertir de Won sul-coreano a la moneda de tu país

**Extra:**
Como desafío extra, si puedo convertir divisas, ¿tal vez pueda añadir a mi programa otros tipos de conversiones como temperatura por ejemplo?

## La solución a este challenge se presenta a continuación:

Este cuadro de dialogo permite al usuario escoger entre las opciones de conversión:

![Image text](https://github.com/DanielValdes98/Project-Conversor/blob/master/img/menu-seleccion.png)
![Image text](https://github.com/DanielValdes98/Project-Conversor/blob/master/img/menu-seleccion2.png)


***Tipos de conversores:***
Esta ventana recibe el valor que desea convertir dependiendo el conversor que se elija. Este input está validado y no acepta otro tipo de caracteres que no sean del tipo numérico. Permite también escoger entre las diferentes opciones a la que desea convertir y muestra el valor de la conversión realizada..

![Image text](https://github.com/DanielValdes98/Project-Conversor/blob/master/img/conversor-moneda.png)
![Image text](https://github.com/DanielValdes98/Project-Conversor/blob/master/img/conversor-temperatura.png)

Nuestro cliente desea que nuestro usuario decida que desea hacer después de realizar la primera conversión. Se presentan las siguientes opciones:

-Yes: Debe llevar nuevamente a nuestro usuario a menu principal para escoger una opción de conversión.
- No: Debe mostrar un mensaje de "Programa Finalizado"
- Cancel: Debe mostrar un mensaje de "Programa Finalizado"

Utilice el método showConfirmDialog para preguntar al usuario si desea continuar usando el programa.

![Image text](https://github.com/DanielValdes98/Project-Conversor/blob/master/img/select-option.png)

Como se define en en el menu ¿Desea continuar?, si el usuario selecciona la opción No o Cancel se usa showMessageDialog para que pueda cerrar el programa con el mensaje "Programa Terminado"

![Image text](https://github.com/DanielValdes98/Project-Conversor/blob/master/img/programa-terminado.png)





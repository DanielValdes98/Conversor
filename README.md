# Challenge : Conversor - Oracle | Alura Latam | Especialización Back-End en Java

Se solicita crear un conversor de divisas utilizando el lenguaje Java. Las características requeridas por el cliente son las siguientes:

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
Como desafío extra, si puede convertir divisas, ¿tal vez pueda añadir al programa otros tipos de conversiones como temperatura, por ejemplo?

## La solución a este challenge se presenta a continuación:
Para este desafío se hace uso del lenguaje de programación Java utilizando la herramienta Windows Builder para el diseño de la interfaz gráfica. Se hace uso de clases e interfaces, aplicando los conceptos de herencia, polimorfismo y manejo de errores con excepciones brindados en la ruta de aprendizaja. Exite una clase padre llamada "Conversor" y dos clases hijas "ConversorMoneda" y "ConversorTemperatura", ambas heredan los atributos y métodos de la clase padre e implementan los métodos establecidos de la interfaz "Convertir". Soy consciente que el código puede depurarse aún más, incluso incorporando API's para tomar la TRM actual y poder hacer la conversión de divisas más automática, pero esto será una mejora para más adelante. Sin embargo, esta es mi solución propuesta para el challenge del programa ONE de Oracle y Alura Latam. Todo el código lo encuentran en este repositorio, pueden hacer uso y probarlo sin problema.

### Conversor:

Este cuadro de dialogo permite al usuario escoger entre las opciones de conversión:

![Image text](https://github.com/DanielValdes98/Project-Conversor/blob/master/img/menu-seleccion.png)
![Image text](https://github.com/DanielValdes98/Project-Conversor/blob/master/img/menu-seleccion2.png)

**Tipos de conversores:**
Esta ventana recibe el valor que desea convertir dependiendo el conversor que se elija. El input está validado y no acepta otro tipo de caracteres que no sean del tipo numérico. Permite también escoger entre las diferentes opciones a la que desea convertir y muestra el valor de la conversión realizada.

![Image text](https://github.com/DanielValdes98/Project-Conversor/blob/master/img/conversor-moneda.png)
![Image text](https://github.com/DanielValdes98/Project-Conversor/blob/master/img/conversor-temperatura.png)

El cliente desea decidir que desea hacer después de realizar la primera conversión. Se presentan las siguientes opciones:

- Yes: Debe llevar nuevamente al usuario al menu principal para escoger una opción de conversión.
- No: Debe mostrar un mensaje de "Programa Finalizado"
- Cancel: Debe mostrar un mensaje de "Programa Finalizado"

Nota: Se usa el método showConfirmDialog para preguntar al usuario si desea continuar usando el programa.

![Image text](https://github.com/DanielValdes98/Project-Conversor/blob/master/img/select-option.png)

Como se define en en el menu ¿Desea continuar?, si el usuario selecciona la opción No o Cancel se usa showMessageDialog para que pueda cerrar el programa con el mensaje "Programa Terminado"

![Image text](https://github.com/DanielValdes98/Project-Conversor/blob/master/img/programa-terminado.png)





# Convertidor de Monedas

Bienvenido este es un programa compacto desarrollado en Java que utiliza la API de ExchangeRate-API para realizar conversiones entre diversas monedas basadas en el dólar estadounidense.

## Características

-Conversión de Monedas: Permite convertir dólares estadounidenses (USD) a y desde soles peruanos (PEN), pesos argentinos (ARS), y pesos chilenos (CLP).
-Integración con ExchangeRate-API: Utiliza la API de ExchangeRate-API para obtener tasas de cambio actualizadas en tiempo real.
-Manejo de JSON: Implementa Gson para mapear datos JSON a objetos Java de manera eficiente.
-Solicitudes HTTP: Usa HttpClient para realizar solicitudes HTTP de forma simple y robusta.
-Interfaz de Usuario Intuitiva: Proporciona una interfaz de línea de comandos fácil de usar para seleccionar el tipo de conversión y la cantidad deseada.

## Uso

1. Después de compilar, ejecuta el programa con el siguiente comando `Main.java`.
2. Interactuar con el programa:
    -El programa mostrará un menú interactivo en la consola, donde podrás seleccionar la conversión deseada.
    -Ingresa el número correspondiente a la opción deseada y presiona Enter.
    -Si seleccionas una opción de conversión, el programa solicitará la cantidad de dólares a convertir.
    -Después de ingresar la cantidad, mostrará el resultado de la conversión y esperará a que presiones Enter para continuar.
    
-ds
3. Salir del programa:
-Para salir del programa, selecciona la opción 7 en el menú principal.

## Requisitos

- Java 11 o superior.
- Acceso a Internet para realizar las consultas a la API de ExchangeRate-API.


# Convertidor de Moneda

Este es un simple convertidor de moneda desarrollado en HTML, CSS y JavaScript. Utiliza la API de `exchangerate-api.com` para obtener las tasas de cambio actuales.

## Funcionalidades

- Conversión de moneda de una moneda origen a una moneda destino.
- Validación de campos de entrada.
- Manejo de errores para entradas inválidas y problemas de red.

## Estructura del Proyecto

- `index.html`: Archivo HTML principal que contiene la estructura de la página web.
- `styles.css`: Archivo CSS que contiene los estilos para la página web.
- `script.js`: Archivo JavaScript que maneja la lógica de conversión de moneda.

## Uso

1. Abre `index.html` en tu navegador.
2. Introduce el monto, la moneda origen y la moneda destino.
3. Haz clic en el botón `Convertir`.
4. Verás el resultado de la conversión en la página.

## Ejemplo

1. Introduce `100` en el campo de monto.
2. Introduce `USD` en el campo de moneda origen.
3. Introduce `EUR` en el campo de moneda destino.
4. Haz clic en `Convertir`.
5. Verás el resultado: `100 USD es igual a X.XX EUR`.

## Instalación

Para instalar y ejecutar este proyecto en tu máquina local:

1. Clona el repositorio:

    ```bash
    git clone https://github.com/tu-usuario/currency-converter.git
    ```

2. Navega al directorio del proyecto:

    ```bash
    cd currency-converter/src
    ```

3. Abre `index.html` en tu navegador.

## API

Este proyecto utiliza la API de `exchangerate-api.com`. La URL de la API utilizada es:
https://v6.exchangerate-api.com/v6/65b86fc2d10f063fe5f144b7/latest/{fromCurrency}

# Realizar las siguientes figuras:

1. Un cuadrado de 5 cm de lado.
2. Un triángulo equilátero de 5 cm de lado.
3. Un rectangulo de 3cm de ancho por 6cm de largo.
4. Un círculo de 4 cm de diámetro.

## Utilizar el html
```html
    <div class="container">
        <div class="cuadrado"></div>
        <div class="triangulo"></div>
        <div class="rectangulo"></div>
        <div class="circulo"></div>
    </div>
```

## Investigar las propiedades css necesarias
width
margin
background-color
border
border-radius
#optional
display: flex
flex-direction
align-items

```css
   .container {
        display: flex;
        flex-direction: row;
        gap: 10px;
        justify-content: center;
        align-items: center;
    }
    .cuadrado {
        /*Escribir css aqui*/
        }
        /* Triángulo equilátero de 10 cm de lado */
        .triangulo {
            /*Escribir css aqui*/

        }
        /* Rectángulo de 5cm de ancho por 10cm de largo */
        .rectangulo {
            /*Escribir css aqui*/
        }
        /* Círculo de 10cm de diámetro */
        .circulo {
         /*Escribir css aqui*/
        }
```
## Salida del programa
![Descripción de la imagen](./images/primer-practica.png)

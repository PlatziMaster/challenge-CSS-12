reto css 12
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Reto Css 11</title>
        <style>
            body 
            {
                font-family: Arial, Helvetica, sans-serif;
                background-color:rgb(103,68,194);
            }
            .container
            {   
                padding: 30px;
                display: grid;
                grid-template-columns: repeat(5 ,50px);
                grid-template-rows: 8px 50px;
                grid-gap:50px;
                background:white;
                border-radius:5px 5px 40px 40px;
                height: 200px;
                width: 500px;
            }
            .item-1
            {
                border-radius: 30px 30px 30px 30px;
                grid-column-start: 1;
                grid-column-end: 3;
                grid-row: 2;
                background:  rgba(157, 132, 219, 0.479);
                color:rgb(103,68,194);
                font-size: x-large;
            }
            .item-2
            {   
                grid-column: 3;
                grid-row: 2;
                font-size: 40px;
                justify-self: center;
            }
            .item-3
            {
                grid-column: 4;
                grid-row: 2;
                background:rgb(83, 82, 82);
                justify-self: center;
            }
            .item-4
            {
                grid-column: 5;
                grid-row: 2;
                background:rgb(83, 82, 82);
                justify-self: center;
            }   
        </style>
    </head>    
   <body>
        <section class="container">
            <div class="item-1"><pre>    ± Home</pre></div>
            <div class="item-2">♥</div> 
            <div class="item-3"><img src="../Learning/desarrollo-web-portafolio/images/twitter.svg" width="45" width="45" alt="image-twitter"></div>
            <div class="item-4"><img src="../Learning/desarrollo-web-portafolio/images/github.svg" width="45" width="45"alt="image-github"></div> 
        </section>
   </body>
</html>


# 🥕 Challenge CSS 12

CSS Grid: Navbar

## 🥕 ¿En qué consiste?

La idea de este reto es que repliques el siguiente componente usando CSS Grid. En CSS Grid tenemos diferentes propiedades para los elementos padres y para los elementos hijos, por lo que la clave principal para resolver este reto es poder identificar qué elementos tenemos y que "rol" juegan, para así, identificar qué propiedades se le deben aplicar (recueda que hay hijos que también son padres).

<kbd>
<img width="400" src="https://i.ibb.co/6wKxCNX/Screen-Shot-2020-07-26-at-3-48-08-AM.png" />
</kbd>

> [Fuente de la imagen | Dribbble](https://dribbble.com/shots/5925052-Bottom-Bar-Navigation-Pattern)

Te dejo la siguiente documentación útil para resolver el reto:

* [CSS Grid Garden| Juego](https://cssgridgarden.com/#es)
* [A Complete Guide to Grid | CSS Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/)
* [Grid in CSS | CSS Reference](https://cssreference.io/css-grid/)
* [Learn CSS Grid](https://learncssgrid.com/)
* [Grid by Example](https://gridbyexample.com/examples/)

## 🥕 Pasos a seguir:

1. Hacer un "Fork" de este proyecto.
2. Revolver el reto.
3. Crear un Pull Request hacia este repositorio.

## 🥕 ¿Cómo contribuir?

Si quieres agregar o mejorar algo, te invito a colaborar directamente en este repositorio: [challenge-css-13](https://github.com/platzimaster/challenge-css-13/)

## 🥕 Licencia

challenge-CSS-12 se lanza bajo la licencia [MIT](https://opensource.org/licenses/MIT).

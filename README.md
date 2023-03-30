# BaseGrid Framework
BaseGrid Framework es un sistema de grilla responsive basado en 12 columnas, diseñado para ayudar en la maquetación de sitios web de manera rápida y sencilla.

## Características
- Basado en 12 columnas
- Clases predefinidas para diseños de una o varias columnas
- Opciones para offsets, push y pull para ajustar la posición de las columnas
- Media queries para dispositivos móviles y tablets
- Escrito en SASS
- Personalizable para adaptarse a los requisitos específicos del proyecto
- Licencia Creative Commons 3.0

## Uso básico
Para utilizar el framework, simplemente incluye el archivo basegrid.css en tu documento HTML:

```bash
<link rel="stylesheet" href="basegrid.css">
```
Luego, utiliza las clases predefinidas para crear diseños de una o varias columnas:

```php
<div class="row">
  <div class="col-12">Columna de ancho completo</div>
</div>
<div class="row">
  <div class="col-6">Columna de ancho medio</div>
  <div class="col-6">Columna de ancho medio</div>
</div>
```
También puedes utilizar opciones como offsets, push y pull para ajustar la posición de las columnas:

```php
<div class="row">
  <div class="col-6 col-offset-3">Columna centrada</div>
</div>
<div class="row">
  <div class="col-6 col-push-6">Columna empujada hacia la derecha</div>
  <div class="col-6 col-pull-6">Columna tirada hacia la izquierda</div>
</div>
```

## Media Queries
El framework cuenta con media queries para dispositivos móviles y tablets, que permiten que los diseños sean adaptables a diferentes tamaños de pantalla.

### Small Screens (≤ 576px)
En dispositivos con pantallas pequeñas, las columnas se apilan verticalmente y tienen un ancho de 100%.

### Medium Screens (> 576px)
En dispositivos con pantallas medianas, las columnas se ajustan a un ancho de 50% y se colocan lado a lado.

### Large Screens (> 992px)
En dispositivos con pantallas grandes, las columnas se ajustan a un ancho de 33.33% y se colocan lado a lado.

## Personalización
El framework está escrito en CSS y se puede personalizar fácilmente para adaptarse a los requisitos específicos del proyecto. Simplemente modifica los estilos CSS en el archivo basegrid.css según sea necesario.

## Contribuir
Si quieres contribuir al desarrollo del framework, ¡tus contribuciones son bienvenidas! El código fuente del proyecto se encuentra en GitHub: https://github.com/shadax-dev/basegrid/

Licencia
Este proyecto está licenciado bajo la Licencia Creative Commons 3.0. Consulta el archivo LICENSE para más detalles.

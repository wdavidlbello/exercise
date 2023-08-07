# Este es un diseño web para ejercitar

## Errores encontrados:
### En el html
1. Haber creado un **div** que agrupara el **section**, el **aside** y el footer.  
2. No haber definido el elemento **article** dentro del **section**
3. No haber definido la etiqueta **time** para representar la fecha de publicacion del articulo con los elementos de dia del mes y de la semana con *divs*, como sigue a continuación:
```
<time datetime="2023-07-24" pubdate>
	<div class="numerodia">24</div>
	<div class="nombredia">Lunes</div>
</time>
```

## Estructura de un pagina web

* __El head__: Con sus elementos title, meta y link para los archivos externos.
* __El body__
  ### Se divide en:
  1. __header__: Aquí se ubica el encabezado de la página.
  2. __nav__: Un menú de navegación.
  3. __main__: Aquí dentro van los elementos del motivo de la página, ejemplo: 
    * section:
      * article
         * p 
         * figure 
             * img
    * aside:
      * h1 
      * p 
* __El footer__: pie de página. Puede dividirse en **section**, una con los distintos enlaces del sitio, otra con el contacto de la página y otra con el código tradicional:
```
<section class="seccionpie">
      <address>Toronto, Canada</address>
			<small>&copy; Derechos Reservados 2023</small>
		</section>
		<div class="recuperar"></div>

```
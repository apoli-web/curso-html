## 2. Enlaces

En HTML, la etiqueta `<a>` se conoce como **anchor** (ancla) y se utiliza para crear enlaces de navegación, tanto dentro de la misma página como hacia otros sitios web.

### Enlace interno

Para enlazar a una sección dentro de la misma página, usamos el atributo `href` con el identificador (`id`) de esa sección:

```html
<a href="#proyectos">Ir a la sección de Proyectos</a>
```

Enlace externo

Si queremos dirigir al usuario a otro sitio web, simplemente colocamos la URL completa como valor del atributo href:

```html
<a href="https://www.youtube.com/">Visitar YouTube</a>
```

Si quieres que el enlace se habra en otra pagina lo que puedes hacer es utilizar `target="_blank"`

```html
<a href="https://www.youtube.com/" target="_blank">Visitar en otra pagina</a>
```

<p> Si quieres ver como funciona hax click </p>
<a href='https://www.tiktok.com/@apoliweb/video/7481541926794120503' style="
margin-top:2rem;           
            text-decoration: none;
            color: #fff;
            font-size: 20px;
            background-color: #1D508B;
            padding: 16px;
            border-radius: .3rem;" >ver video</a>

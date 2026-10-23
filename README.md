# Página de Surti2

La página de presentación de Surti2, una app de ventas, inventario y fiado para tiendas de barrio. La hice sin frameworks y sin nada que instalar: HTML, CSS y JavaScript.

![Portada](docs/captura-hero.png)

## Lo que tiene

- En la portada, una venta completa como se hace en la app: entran los productos, el total sube, se elige Nequi y se cobra. Corre una vez al abrir, se puede repetir con un botón y no se mueve si el sistema pide reducir el movimiento.
- Un día en la tienda hora por hora, desde que se abre la caja hasta que se cierra.
- La lista del fiado con quién debe, cuánto y quién lleva días sin abonar, y preguntas frecuentes que se abren también con el teclado.
- Se adapta al celular.

<img src="docs/captura-movil.png" alt="Vista en el celular" width="280">

Usa la misma letra (IBM Plex Sans) y los mismos colores de la app: blanco, gris claro y un solo azul para lo que se puede tocar. Los textos hablan como el tendero: fiado, cuadre de caja, Nequi.

## Verla

Abre `index.html` en el navegador, o sirve la carpeta:

```bash
npx serve .
```

Los botones "Probar con la tienda de ejemplo" y "Crear mi tienda" abren la app real en `app/index.html`. Es la versión portátil de [surtido-app](https://github.com/orlandocastillo-dev/surtido-app), que se regenera allá con `npm run build:portable`.

En vivo: https://surti2.vercel.app

Surti2 es una marca inventada para un proyecto de portafolio; los datos son de ejemplo.

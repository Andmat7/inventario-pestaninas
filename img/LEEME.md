# Fotos de los productos

Por ahora **todos los productos** usan las mismas dos fotos:

| Foto | Archivo |
|---|---|
| Cómo se ve empacada | `img/empacada.jpg` |
| Cómo se ve en la tienda | `img/imagen_tienda.jpg` |

Para darle fotos propias a un producto, súbelas a esta carpeta (ej. `P1532_caja.jpg` y `P1532_tienda.jpg`) y agrégalo en `FOTOS` dentro de cada HTML:

```js
const FOTOS={
  P1532:{caja:"img/P1532_caja.jpg",tienda:"img/P1532_tienda.jpg"},
};
```

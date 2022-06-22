# Practica Integradora

### Parte 1

- Crear un componente ListaDeFavoritos que hara un map() del array inicial que les damos. Importarlo en App.js
- Crear un componente Pelicula que recibira la info del map() desde ListaDeFavoritos y renderizara la informacion.
- Dar estilos diferentes segun si isWatched es true o false.

```
const watchList = [
    {
        id: 1,
        img: "https://es.web.img3.acsta.net/pictures/22/05/14/13/26/5638861.jpg",
        name: "Stranger Things",
        isWatched: false
    },
    {
        id: 2,
        img: "https://cdn.hobbyconsolas.com/sites/navi.axelspringer.es/public/styles/480/public/media/image/2022/06/obi-wan-kenobi-cartel-nuevo-2721977.jpg?itok=nVyLrY8_",
        name: "Obi-Wan Kenobi",
        isWatched: true
    },
    {
        id: 3,
        img: "https://pics.filmaffinity.com/Sense8_Serie_de_TV-122389805-large.jpg",
        name: "Sense 8",
        isWatched: true
    }
]
```

### Parte 2

- Crear un boton para cada Pelicula que permita cambiar la propiedad isWatched de false a true.
- Crear un boton para cada Pelicula que permita eliminarla de la watchList.

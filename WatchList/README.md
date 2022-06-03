# Practica Integradora

### Parte 1

- Clonar este repo e instalar sus dependencias

```
git clone "linkDelRepo"
cd "nombreDelProyecto"
npm i
```

- Crear un componente ListaDeFavoritos que hara un map() del array inicial que les damos. Importarlo en App.js
- Crear un componente Pelicula que recibira la info del map() desde ListaDeFavoritos y renderizara la informacion.
- Dar estilos diferentes segun si isWatched es true o false.

```
const watchList = [
    {
        id: 1,
        name: "Stranger Things",
        isWatched: false
    },
    {
        id: 2,
        name: "Obi-Wan Kenobi",
        isWatched: true
    },
    {
        id: 3,
        name: "Sense 8",
        isWatched: true
    }
]
```

### Parte 2

- Crear un componente Formulario que tendra un input text y un boton type submit.
- Al escribir y dar en submit, se debe agregar lo que el usuario ingresa en la lista de ListaDeFavoritos.

### Parte 3

- Crear un boton para cada Pelicula que permita cambiar la propiedad isWatched de false a true.
- Crear un boton para cada Pelicula que permita eliminarla de la watchList.
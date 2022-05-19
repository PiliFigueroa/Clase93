# Practica componentes, props y map()
### Parte 1
- Clonar este repositorio e instalar las dependencias con el siguiente comando. Verificar estar paradxs en la carpeta del proyecto.
```
npm i
```
- Limpiar el proyecto.
- Crear un componente Navbar e importarlo en App.js
- El Navbar debe contener un logo (utilizar imagen de la carpeta assets).
- Los links del Navbar deberan ser generados con un map() a partir de un array de objetos (utilizar el array de la carpeta assets).
- Crear un componente Footer con los nombres de ustedes. Importarlo en App.js

### Parte 2
- Crear un componente ContenedorArticulos e importarlo en App.js.
    - Este componente hace un map() de los articulos que encontraran en un array de objetos de la carpeta assets.
    - Crear un componente Articulo que recibira la informacion del map() en ContenedorArticulos mediante props y la renderizara.
- Crear un componente Aside e importarlo en App.js. Este componente mostrara un listado de articulos relacionados con un map(). El array esta en assets.
- Posicionar el Aside a la derecha de Contenedor Articulos.

### Parte 3
- Crear una funcion en ContenedorArticulos que tome por parametro un titulo y haga un console.log del mismo.
    - Pasar esta funcion a cada Articulo mediante props.
    - Recibir la funcion en Articulo.
    - Crear un boton que ejecute la funcion con un onClick={}

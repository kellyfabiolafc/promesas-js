# Práctica de Consumo de API REST

## Descripción

En esta práctica se desarrollaron cuatro ejercicios utilizando HTML, CSS, Bootstrap y JavaScript, con el objetivo de consultar información de diferentes API REST mediante `fetch()` y mostrar los resultados en una página web.

## Tecnologías utilizadas

- **HTML5:** estructura de las páginas.
- **CSS3:** diseño y estilos.
- **Bootstrap 5:** presentación de los formularios.
- **JavaScript:** consultas y manejo de datos.
- **API REST:** obtención de información externa.

## Ejercicios desarrollados

### Ejercicio 01 - Buscador de planetas

Se utilizó la API de Star Wars (SWAPI) para buscar planetas mediante su ID.

**Datos mostrados:**
- Nombre
- Clima
- Terreno
- Población
- Periodo de rotación

**API:** https://swapi.dev/api/planets/3/

### Ejercicio 02 - Buscador de naves espaciales

Se utilizó SWAPI para consultar información de naves espaciales ingresando su ID.

**Datos mostrados:**
- Nombre
- Modelo
- Fabricante
- Tripulación
- Pasajeros

**API:** https://swapi.dev/api/starships/9/

### Ejercicio 03 - Buscador de personajes de Dragon Ball

Se desarrolló un formulario que permite buscar personajes de Dragon Ball mediante su ID.

**Datos mostrados:**
- Nombre
- Descripción
- Imagen del personaje

**API:** https://dragonball-api.com/api/characters/1

### Ejercicio 04 - Buscador de Pokémon

Se utilizó PokéAPI para buscar Pokémon ingresando su nombre o ID.

**Datos mostrados:**
- Nombre
- Número
- Altura
- Peso
- Imagen del Pokémon

**API:** https://pokeapi.co/api/v2/pokemon/pikachu

## Funcionalidades generales

- Búsqueda de información mediante API REST.
- Uso de `fetch()` y `async/await`.
- Visualización de los datos obtenidos.
- Validación de registros inexistentes.
- Mensajes de error sin utilizar `alert()`.
- Aplicación de estilos con CSS y Bootstrap.

## Ejecución

1. Abrir la carpeta del proyecto en Visual Studio Code.
2. Ejecutar el archivo HTML del ejercicio con Live Server.
3. Ingresar el ID o nombre solicitado.
4. Presionar el botón **Buscar** para visualizar la información.

## Conclusión

Mediante estos ejercicios se practicó el consumo de API REST utilizando JavaScript, permitiendo obtener información en formato JSON y mostrarla dinámicamente en formularios y elementos HTML.

También se aplicaron estilos CSS y Bootstrap para mejorar la presentación de las páginas web.

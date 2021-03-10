## My first FETCH-API

# Comsumir API Publica con JavaScript.

# Preview 🚀

![](docs/pokemon.jpeg)


* **API Fetch:** Es un nuevo estandar que viene a dar una alternativa para interactuar con el protocolo http. 


En este proyecto haremos una peticion a esta url 'https://pokeapi.co/api/v2/pokemon/1/' y traeremos los datos de pokemon.

_Fetch está basado en promesas y nos brinda mayor flexibilidad y capacidad de control a la hora de realizar llamadas al servidor. Su sintaxis es bastante sencilla y ecibe como parametro la url que para este caso la guardaremos dentro de constante pero podriamos pasarsela directamente._

```
Ejemplo: fetch('https://pokeapi.co/api/v2/pokemon/1/');
```

Entonces,

la promesa seria 
```
.then
```
y la respuesta viene en formato json 

```
response.json());
```

_Para imprimir por consola usamos data. El cual es el resultado de nuestro JSON y en caso de haber un error usariamos catch.
``` 
.catch(); 
```

_Debemos observar en el navegador que ya tenemos la peticion y una vez traidos los datos. Creamos nuestro template para mostrarlos. _
_En nuestro index tenemos un id=element. Y alli vamos a usar el template de strings. Colocamos una etiqueta p con el nombre e interpolamos y cerramos etiquetas.
_La interpolacion ocurre en las ${} y dentro de las llaves es donde solicitaremos la data._

¡muy simple!

Made with 💕



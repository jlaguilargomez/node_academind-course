🧙 [***Link to notes in Notion***](https://www.notion.so/jlaguilargomezdevelop/S1-Introduction-44ab2f6768ae44448d74d25567fd03ae) 👨‍💻

## Intro

NODE es un runtime de JS, esto es, nos permite "utilizar" JS fuera del navegador (que no es más que otro runtime para JS también).

Al igual que  chrome, utiliza el motor de google V8 para transpilar código JS a lenguage máquina.

[V8](https://v8.dev/)

Como nota, V8 está escrito en C++

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/149fcc64-57f3-453c-9977-bf25942048f5/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/149fcc64-57f3-453c-9977-bf25942048f5/Untitled.png)

## Creating our first app

Al instalar NODE, este trae consigo una serie de módulos pre-configurados (o librerías), como puede ser, por ejemplo, el gestor de archivos `fs`

```jsx
const fs = require('fs');

fs.writeFileSync('hello.txt', 'Something cool'); // acepta dos argumentos: ruta y contenido del archivo
```

Con est pequeño "script" creamos un archivo `.txt` con el contenido "*Something coo*l" en él

## Understanding the role & usage of NodeJS

Con NODE podemos manejar la lógica del servidor: conexión a BBDD, autenticación, input validator, lógica de negocio ... todo lo que NO queremos que el usuario pueda controlar desde el cliente.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e6845519-eb9c-4ade-8c06-1cb10deb4d21/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e6845519-eb9c-4ade-8c06-1cb10deb4d21/Untitled.png)

No se limita únicamente a manejar la lógica del servidor, sino que, además, nos permite gestionar el SERVIDOR como tal (manejar las peticiones, redirigirlas ...) tal y como hacemos en PHP con Apache, ngInx ...

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/edca53ec-7bbc-4b18-9be4-3f13dddd6044/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/edca53ec-7bbc-4b18-9be4-3f13dddd6044/Untitled.png)

Alternativa a NODE, tenemos otros lenguajes que podemos utilizar en el lado del servidor:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1acb090f-6e10-4976-8a54-c3d0e44da34a/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1acb090f-6e10-4976-8a54-c3d0e44da34a/Untitled.png)

**Lo bueno de NODE es que nos permite seguir utilizando NODE tanto en el lado del cliente como en el servidor. 1 lenguaje para dominar BACK y FRONT**

## Course outline

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5cd9d395-dae0-4636-9ccc-33f0bf899f17/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5cd9d395-dae0-4636-9ccc-33f0bf899f17/Untitled.png)

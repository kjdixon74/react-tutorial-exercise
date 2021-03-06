# `03.1` Your first functional component

Cuando creas funciones que devuelven HTML, JSX te dejará tratarlos como **Componentes**. Básicamente ellos se convertirán tus propias etiquetas HTML.

> Creando nuestro primer componente funcional

> Una de las cosas que podemos hacer gracias a JSX es llamar funciones com si fueran etiquetas HTML, por ejemplo:

```js
// si declaramos una función llamada `MyFunction`
const MyFunction = () => {
    return <h1>I Love React</h1>;
}

// podemos llamar la función como una etiqueta HTML así 
<MyFunction />

// en vez de hacerlo de la típica forma usando llaves
MyFunction();
```

Cuando llamas a una función así, se convierte en un **Componente de React**, que es una función que genera (devuelve) HTML dinámicamente. Lo que sea que devuelva la función será reemplazado en el mismo lugar que el lugar original del `<MyFunction />`.

## 📝 Instrucciones:

1. En la 9º línea de `app.jsx`, cambia la forma en la que se llama a la función, llama a la función como un **componente React** usando `<` y `>` como una etiqueta HTML (en lugar de paréntesis).

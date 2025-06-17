# Crear una variable en Postman desde el body de la respuesta

```js
// Guardar un valor desde el body en una variable de entorno
const jsonData = pm.response.json(); // Convierte la respuesta en JSON
pm.environment.set("miVariable", jsonData.token); // Guarda el valor en el entorno

// También puedes usar variables de colección
// pm.collectionVariables.set("miVariable", jsonData.token);
```

🔍 **Explicación rápida:**
- `pm.response.json()` convierte la respuesta de la API en un objeto para poder acceder a sus campos.
- `pm.environment.set("clave", valor)` guarda el valor en una variable del entorno activo.

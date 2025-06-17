# Extraer token de autenticación y guardarlo

```js
const jsonData = pm.response.json();
pm.environment.set("authToken", jsonData.token);
```

🔍 **Explicación:**
- Extrae un `token` desde la respuesta de una API y lo guarda como variable de entorno para usarlo en futuras peticiones.

# Generar un timestamp antes de enviar la petición

```js
const timestamp = new Date().toISOString();
pm.environment.set("timestamp_actual", timestamp);
```

🔍 **Explicación:**
- Genera la fecha y hora actual en formato ISO y la guarda como variable de entorno.

# Validar el código de estado HTTP

```js
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
```

🔍 **Explicación:**
- Este script valida que la respuesta de la API tenga el código 200 (OK).

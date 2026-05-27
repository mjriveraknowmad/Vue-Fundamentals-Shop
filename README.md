# vue-fundamentals-shop

Código siguiendo el curso de Vue JS - Guía Completa: https://knowmadmood.udemy.com/course/vue-guia-completa/learn/lecture/50913561#overview

Detalles:
- Usa Vue 3, pero con javascript
- Usa Pinia 3 ( con options API en themeStore y con composition API en authStore )
- Usa Firebase 11.4
- Las comprobaciones de formulario se hacen de forma manual al intentar submitir, creando un array de mensajes de error para mostrarlo a continuación.


## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

Renombra firebaseConfig.template.js por firebaseConfig.js. Y añade la configuración de tu aplicación (que deberías tambien añadirle una base de datos firebase).
En mi caso en la ruta lo encuentro en https://console.firebase.google.com/project/vue-fundamental-shop/settings/general/web:MzE2NDQzMmQtOTE0YS00NGFhLWFjZDktZDQ1MzQ5NDc4NmJj?hl=es-419
También debe tener activada el proveedor de email, para poder registrarse y logarse con email, en mi caso lo encuentro en https://console.firebase.google.com/project/vue-fundamental-shop/authentication/providers?hl=es-419 . Tras registrar un email, hay que ir al firebase y modificar el valor del campo "rol" poniendole admin

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

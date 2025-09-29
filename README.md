# Trabajo Práctico Opcinal - Hola Mundo en ReactJS

## Requisitos

- Node.js >= 18
- pnpm (o npm/yarn, pero se recomienda pnpm)

## Instalación

1. Clona el repositorio o descarga los archivos del proyecto.
2. Instala las dependencias:

   ```sh
   pnpm install
   ```

   > Si usas npm:
   > ```sh
   > npm install
   > ```

## Ejecución en modo desarrollo

Inicia el servidor de desarrollo con:

```sh
pnpm dev
```

> O con npm:
> ```sh
> npm run dev
> ```

Luego abre [http://localhost:5173](http://localhost:5173) en tu navegador.

## Compilar para producción

Para generar los archivos de producción:

```sh
pnpm build
```

Los archivos generados estarán en la carpeta `dist/`.

## Previsualizar la build de producción

Puedes previsualizar la build con:

```sh
pnpm preview
```

## Linting

Para analizar el código con ESLint:

```sh
pnpm lint
```

---
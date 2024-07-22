## Inicializar proyecto en Angular
```bash
 ng new project [nombre-del-proyecto]
 ng serve 
```

## Componentes
- ng new component nombre-componente
- Importar el componente en app.component.ts en la parte superior
> import { PruebaComponentComponent } from './prueba-component/prueba-component.component';

- Importar el compontente dentro de @Component en la etiqueta import
> imports: [RouterOutlet, PruebaComponentComponent],


## Instalar Tailwind Css como dependencia
- Instalar Tailwind como dependencia
npm install -D tailwindcss postcss autoprefixer
```bash
npx tailwindcss init
```

- Una vez instalado Tailwind, se generará un archivo llamado tailwind.config.js, añadir el path necesario a la etiqueta content

 content: [
    "./src/**/*.{html,ts}",
  ],

- Añadir el siguiente bloque a las hojas css donde se usará Tailwind

@tailwind base;
@tailwind components;
@tailwind utilities;
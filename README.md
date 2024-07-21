## Inicializar proyecto en Angular
- ng new project [nombre-del-proyecto]
- ng serve 

## Componentes
- ng new component nombre-componente
- Importar el componente en app.component.ts en la parte superior
> import { PruebaComponentComponent } from './prueba-component/prueba-component.component';
- Importar el compontente dentro de @Component en la etiqueta import
> imports: [RouterOutlet, PruebaComponentComponent],

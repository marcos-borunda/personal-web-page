# Página personal de Marcos Borunda

Código de [Marcos Borunda | IA para empresas](https://marcos-borunda-ia.elboru.chatgpt.site/).

## Archivos

- `dist/index.html`: contenido de la página.
- `dist/style.css`: estilos y diseño adaptable.
- `dist/app.js`: interacciones e idioma.
- `dist/*.webp`: imágenes.
- `.openai/hosting.json`: configuración del sitio en Sites.

## Ver la página localmente

Con Python 3 instalado, ejecuta desde la raíz del repositorio:

```sh
python3 -m http.server 8000 --directory dist
```

Abre http://localhost:8000 en tu navegador.

La página es estática y no requiere instalar dependencias ni compilar. Edita los archivos dentro de `dist/`.

## Publicación

El sitio actual está alojado en Sites. Este repositorio guarda una copia de su código; los cambios en GitHub no se publican automáticamente en Sites.

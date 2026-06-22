# La Genia - Bitácora de Entrenamiento y Paseos

Este repositorio contiene la aplicación **La Genia**, una bitácora de entrenamiento físico y registro de paseos con la Corte Canina.

La aplicación está construida como un **Design Component** y corre de manera completamente local y autocontenida.

## Estructura del Proyecto

- `La Genia.dc.html` / `index.html`: Archivo principal con la estructura HTML, estilos, y la lógica del componente React.
- `support.js`: El motor runtime local que compila y renderiza el Design Component.
- `genia_*.png`: Las imágenes utilizadas en la interfaz para representar las distintas actividades físicas y estados de la aplicación.

## Cómo Ejecutar Localmente

Para evitar restricciones de CORS del navegador al cargar recursos dinámicos, se recomienda servir la carpeta utilizando un servidor HTTP básico.

### Opción 1: Usando Node.js (npx)
Ejecuta la siguiente línea en la terminal dentro de esta carpeta:
```bash
npx http-server -p 8080
```
Luego abre en tu navegador: [http://localhost:8080](http://localhost:8080)

### Opción 2: Usando Python
Ejecuta en la terminal:
```bash
python -m http.server 8080
```
Luego abre en tu navegador: [http://localhost:8080](http://localhost:8080)

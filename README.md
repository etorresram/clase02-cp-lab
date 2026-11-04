# Clase 2 · Laboratorio de restricciones

Aplicación para coloreo de grafos y Sudoku 4 × 4, con celdas editables de Python ejecutadas en el navegador y resultados visuales.

**Aplicación:** https://etorresram.github.io/clase02-cp-lab/

Pulsa **Ejecutar ejercicio**, cambia el código y vuelve a ejecutarlo. La aplicación identifica variables, dominios y restricciones y distingue el espacio de búsqueda del número de soluciones. El editor incluye colores de sintaxis y comentarios que explican cada paso. El diseño usa un estilo editorial: fondo marfil, títulos con serif y acentos rojos, sin morado.

No necesitas instalar Python ni crear una cuenta. Usa un navegador actualizado e internet para cargar Pyodide 314.0.7 desde jsDelivr. **Guardar mi archivo** descarga un HTML con tus celdas editadas para llevarlo a otra computadora; no se garantiza funcionamiento sin conexión.

El código se ejecuta en el navegador. Este repositorio contiene únicamente la aplicación estática; el material completo del curso se mantiene en su repositorio separado.

## Publicación

GitHub Pages sirve la rama `gh-pages`, carpeta raíz. La aplicación está publicada en https://etorresram.github.io/clase02-cp-lab/.

Para actualizarla, reemplaza `index.html` por la versión actual de `artefacto/clase02-laboratorio-cp.html` en el repositorio del curso, crea el commit en `main` y sincroniza ambas ramas:

```bash
git push --atomic origin main HEAD:gh-pages
```

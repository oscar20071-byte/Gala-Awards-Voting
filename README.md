# Gala Awards Voting

Web estática para votar en categorías de una gala. Los nominados son elegidos por administración.

## Admin
El panel permite añadir categorías, añadir/edit/borrar nominados. La configuración local se guarda en ese navegador. Exporta el archivo `nominees.json` y súbelo al repositorio para que todos vean los nominados públicos.

## Votos
El botón abre un Issue prellenado en GitHub. Para registrarlo, el votante inicia sesión y pulsa enviar. Los votos quedan públicos, no son anónimos y este sistema no impide votos duplicados.

## Deploy
GitHub Pages automatizado por `.github/workflows/pages.yml`.

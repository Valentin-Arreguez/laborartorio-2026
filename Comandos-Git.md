Mi pimer repositorio
1) git --version
2) git config --global user.name "Tu Nombre" (Configura el nombre en entorno local)
3) git config --global user.email "Tu Mail" 
4) git config --global core.editor "code --wait" (cambiar a vs code)
5) git config --list (ver los datos del git)
6) cd (navegar)
7) mkdir (crear carpeta)
8) cd.. (volver)
9) ls (mirar el contenido en la carpeta)
10) clear (borrar)
11) git init (inicializar el repositorio)
12) git status (verifica el esgado del repo)
13) git add "nombre del archivo"(agregar un archivo)
14) git add . (agregar todos los archivos)
15) git commit -m "nota referencial cambio del commit"
16) git log (se muestan los commits realizados)
17) q para salir cuando aparezca (END)
18) git branch -M main (renombra la rama principal a "main")
19) git remote add origin "https://github.com/Valentin-Arreguez/laborartorio-2026.git"
(agrega el repo local con el de la nube)
20) git push -u origin main (sube todos los cambios a la nube)
-----------Ramas nuevas en Git------------------
21) git checkout -b nueva-rama      # 1. crear y moverme a la rama
# [hacer cambios + commits]     # 2. trabajar en la rama
22) git checkout main               # 3. volver a main
23) git merge nueva-rama            # 4. traer los cambios
24) git branch -d nueva-rama        # 5. limpiar

# SI HAY CONFLICTO:
# → abrir el archivo
# → elegir qué versión conservar
# → borrar los marcadores <<<<, ====, >>>>
# → git add + git commit
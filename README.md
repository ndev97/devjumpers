git clone


cd devjumpers


touch README.md


echo 'modificacion'>README.md


git add .


git commit -m 'commit inicial'


git push


touch privado.txt


mkdir privada


touch .gitignore


git status


touch 1.txt


git branch v0.2


git checkout v0.2


touch 2.txt


git add .


git commit -m 'se crea la rama remota'


git push = (ERROR) fatal: The current branch v0.2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin v0.2

git push --set-upstream origin v0.2


git checkout main


echo 'Hola' >1.txt


git add .


git commit -m 'Hola agregado a 1.txt'


git checkout v0.2


echo 'Adios' >1.txt


git add .


git commit -m 'Adios ahora en 1.txt'


git checkout main


git merge v0.2 = CONFLICT (content): Merge conflict in 1.txt
Automatic merge failed; fix conflicts and then commit the result.
git branch --merged = muestra las ramas fusionadas con la rama activa


git branch --no-merged = muestra las ramas que tienen trabajos sin fusionar


Solucionar Conflicto


git add .


git commit -m 'Conflicto resuelto'


git branch -d v0.2


git branch -D v0.2


git push


git log --oneline --decorate --all --graph


*   5435bc0 (HEAD -> main, origin/main) Conflicto resuelto
|\
| * 4616ba0 Adios ahora en 1.txt
* | 7f9fb57 Hola agregado a 1.txt
|/
* 60af772 (origin/v0.2) se crea la rama remota
* 47880da commit inicial

``` 
Nombres			Perfil GitHub

Franco Formigo		https://github.com/francobenjaminformigo

Camila Calegari		https://github.com/camilacalegari

Ivan De La Parte		https://github.com/ivandelaparte

Alejo Paiva		https://github.com/BLUHD823/repositorio_DevJump

Leandro Cuevas		https://github.com/leandro-cuevas ´´´
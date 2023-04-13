# Ind7
Ejercicio individual 7

# Se clona el repositorio
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio
$ git clone git@github.com:DavidHotspur1988/Ind7.git
Cloning into 'Ind7'...
The authenticity of host 'github.com (20.201.28.151)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? y
Please type 'yes', 'no' or the fingerprint: yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

# Se lista la informacion del escritorio
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio
$ ls
'Anexo N°3 Informe de Actividades Camila M Febrero 2023.pdf'
'Anexo N°6 Declaración Jurada de Incompatibilidad Horaria Camila M Febrero 2023.pdf'
'Anexo N°9 Recibo Simple Movilización N°36 Cami ENE2023 (2).pdf'
'Anexo N°9 Recibo Simple Movilización N°36 Cami ENE2023.pdf'
 Bootcamp/
 Escaneado_20220722-0134.pdf
 HOBOware.lnk*
 Ind7/
 TESIS_PRESENTACION/
 Untitled_06122022_150401.pdf
'Visual Studio Code.lnk'*
 Zoom.lnk*
 desktop.ini
 logos.pptx
 pendant/

# Me posicionó en la carpeta
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio
$ cd ind7

# Inicio mi trabajo en el repositorio
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ git init
Reinitialized existing Git repository in C:/Users/cnbma/OneDrive/Escritorio/Ind7/.git/

# Creo la carpeta fullstackjava
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ mkdir fullstackjava

# Muestro los archivos
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ ls
README.md  fullstackjava/

# Chequeo la informacion
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ vvvvvvvvv
bash: vvvvvvvvv: command not found

# Creo el archivo y escribo la información
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ nano ejercicio.txt

# Verifico los archivos
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ ls
README.md  ejercicio.txt  fullstackjava/

# Verifico el status con el primer cambio
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ejercicio.txt

nothing added to commit but untracked files present (use "git add" to track)

# Se hace el primer commit
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ git commit -m "Primer cambio para el ejercicio 7"
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ejercicio.txt

nothing added to commit but untracked files present (use "git add" to track)

# Realizo el add para indexar el archivo
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ git add ejercicio.txt
warning: in the working copy of 'ejercicio.txt', LF will be replaced by CRLF the next time Git touches it

cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ git commit -m Primer cambio del ejercicio 7
error: pathspec 'cambio' did not match any file(s) known to git
error: pathspec 'del' did not match any file(s) known to git
error: pathspec 'ejercicio' did not match any file(s) known to git
error: pathspec '7' did not match any file(s) known to git

cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ git commit -m "Primer cambio del ejercicio 7"
[main ce6d23e] Primer cambio del ejercicio 7
 1 file changed, 4 insertions(+)
 create mode 100644 ejercicio.txt

cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ git pull
Already up to date.

cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ git push origin master
error: src refspec master does not match any
error: failed to push some refs to 'github.com:DavidHotspur1988/Ind7.git'

# Se sube el archivo
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 394 bytes | 394.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:DavidHotspur1988/Ind7.git
   4a79900..ce6d23e  main -> main

# Accedo nuevamente el archivo para hacer el segundo cambio
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ nano ejercicio.txt

# Verifico el estado
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ejercicio.txt

no changes added to commit (use "git add" and/or "git commit -a")

# Indexo el archivo
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ git add .
warning: in the working copy of 'ejercicio.txt', LF will be replaced by CRLF the next time Git touches it

# Agrego el segundo commit
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ git commit -m "Segundo cambio del ejercicio 7"
[main b7b0bbc] Segundo cambio del ejercicio 7
 1 file changed, 1 insertion(+), 1 deletion(-)

cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ git diff

cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ git checkout A
error: pathspec 'A' did not match any file(s) known to git

# Creo una nueva rama para no perder el archivo original
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ git checkout -b A
Switched to a new branch 'A'

# Subo los cambios finales
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (A)
$ git push origin A
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 422 bytes | 422.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'A' on GitHub by visiting:
remote:      https://github.com/DavidHotspur1988/Ind7/pull/new/A
remote:
To github.com:DavidHotspur1988/Ind7.git
 * [new branch]      A -> A
# Ind7
Documentación del ejercicio individual 7

# Se clona el repositorio
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio <br>
$ git clone git@github.com:DavidHotspur1988/Ind7.git <br>
Cloning into 'Ind7'... <br>
The authenticity of host 'github.com (20.201.28.151)' can't be established. <br>
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU. <br>
This key is not known by any other names. <br>
Are you sure you want to continue connecting (yes/no/[fingerprint])? y <br>
Please type 'yes', 'no' or the fingerprint: yes <br>
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts. <br>
remote: Enumerating objects: 3, done. <br>
remote: Counting objects: 100% (3/3), done. <br>
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 <br>
Receiving objects: 100% (3/3), done. <br>

# Se lista la informacion del escritorio
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio <br>
$ ls <br>
'Anexo N°3 Informe de Actividades Camila M Febrero 2023.pdf' <br>
'Anexo N°6 Declaración Jurada de Incompatibilidad Horaria Camila M Febrero 2023.pdf' <br>
'Anexo N°9 Recibo Simple Movilización N°36 Cami ENE2023 (2).pdf' <br>
'Anexo N°9 Recibo Simple Movilización N°36 Cami ENE2023.pdf' <br>
 Bootcamp/ <br>
 Escaneado_20220722-0134.pdf <br>
 HOBOware.lnk* <br>
 Ind7/ <br>
 TESIS_PRESENTACION/ <br>
 Untitled_06122022_150401.pdf <br>
'Visual Studio Code.lnk'* <br>
 Zoom.lnk* <br>
 desktop.ini <br>
 logos.pptx <br>
 pendant/ <br>

# Me posicionó en la carpeta
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio <br>
$ cd ind7 <br>

# Inicio mi trabajo en el repositorio
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main) <br>
$ git init <br>
Reinitialized existing Git repository in C:/Users/cnbma/OneDrive/Escritorio/Ind7/.git/ 

# Creo la carpeta fullstackjava
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ mkdir fullstackjava

# Muestro los archivos
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main)
$ ls
README.md  fullstackjava/

# Chequeo la informacion
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main) <br>
$ git status <br>
On branch main <br>
Your branch is up to date with 'origin/main'. <br>

nothing to commit, working tree clean <br>

# Creo el archivo y escribo la información
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main) <br>
$ nano ejercicio.txt

# Verifico los archivos
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main) <br>
$ ls <br>
README.md  ejercicio.txt  fullstackjava/ <br>

# Verifico el status con el primer cambio
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main) <br>
$ git status <br>
On branch main <br>
Your branch is up to date with 'origin/main'. <br>

Untracked files: <br>
  (use "git add <file>..." to include in what will be committed) <br>
        ejercicio.txt <br>

nothing added to commit but untracked files present (use "git add" to track) <br>

# Realizo el add para indexar el archivo <br>
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main) <br>
$ git add ejercicio.txt <br>
warning: in the working copy of 'ejercicio.txt', LF will be replaced by CRLF the next time Git touches it <br>

# Se hace el primer commit
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main) <br>
$ git commit -m "Primer cambio del ejercicio 7" <br>
[main ce6d23e] Primer cambio del ejercicio 7 <br>
 1 file changed, 4 insertions(+) <br>
 create mode 100644 ejercicio.txt <br>

# Se sube el archivo
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main) <br> 
$ git push <br>
Enumerating objects: 4, done. <br>
Counting objects: 100% (4/4), done. <br>
Delta compression using up to 8 threads <br>
Compressing objects: 100% (3/3), done. <br> 
Writing objects: 100% (3/3), 394 bytes | 394.00 KiB/s, done. <br>
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 <br>
To github.com:DavidHotspur1988/Ind7.git <br>
   4a79900..ce6d23e  main -> main <br>

# Accedo nuevamente el archivo para hacer el segundo cambio
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main) <br>
$ nano ejercicio.txt <br>

# Verifico el estado
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main) <br>
$ git status <br>
On branch main <br>
Your branch is up to date with 'origin/main'. <br>

Changes not staged for commit: <br>
  (use "git add <file>..." to update what will be committed) <br>
  (use "git restore <file>..." to discard changes in working directory) <br>
        modified:   ejercicio.txt <br>

no changes added to commit (use "git add" and/or "git commit -a") <br>

# Indexo el archivo
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main) <br>
$ git add . <br>
warning: in the working copy of 'ejercicio.txt', LF will be replaced by CRLF the next time Git touches it

# Agrego el segundo commit
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main) <br>
$ git commit -m "Segundo cambio del ejercicio 7" <br>
[main b7b0bbc] Segundo cambio del ejercicio 7 <br>
 1 file changed, 1 insertion(+), 1 deletion(-) <br>

# Creo una nueva rama para no perder el archivo original
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (main) <br>
$ git checkout -b A <br>
Switched to a new branch 'A' <br>

# Subo los cambios finales
cnbma@LAPTOP-O8DEHI5G MINGW64 ~/OneDrive/Escritorio/ind7 (A) <br>
$ git push origin A <br>
Enumerating objects: 5, done. <br>
Counting objects: 100% (5/5), done. <br>
Delta compression using up to 8 threads <br>
Compressing objects: 100% (3/3), done. <br>
Writing objects: 100% (3/3), 422 bytes | 422.00 KiB/s, done. <br>
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 <br>
remote: <br>
remote: Create a pull request for 'A' on GitHub by visiting: <br>
remote:      https://github.com/DavidHotspur1988/Ind7/pull/new/A <br>
remote: <br>
To github.com:DavidHotspur1988/Ind7.git <br>
 * [new branch]      A -> A <br>
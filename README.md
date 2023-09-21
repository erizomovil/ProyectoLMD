apuntes de utilizar github

Jorge Gabriel Arcalá@Profesor MINGW64 ~/Documents/Proyecto_LMD (master)
$ git add .

Jorge Gabriel Arcalá@Profesor MINGW64 ~/Documents/Proyecto_LMD (master)
$ git commit -m "first commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Jorge Gabriel Arcalá@Profesor.(none)')

Jorge Gabriel Arcalá@Profesor MINGW64 ~/Documents/Proyecto_LMD (master)
$ git config --global user.email "jg.arcalagonzalez@gmail.com"

Jorge Gabriel Arcalá@Profesor MINGW64 ~/Documents/Proyecto_LMD (master)
$ git config --global user.name "erizomovil"

Jorge Gabriel Arcalá@Profesor MINGW64 ~/Documents/Proyecto_LMD (master)
$ git commit -m "first commit"
[master (root-commit) 0185101] first commit
 1 file changed, 2 insertions(+)
 create mode 100644 README.md

Jorge Gabriel Arcalá@Profesor MINGW64 ~/Documents/Proyecto_LMD (master)
$ git push origin master
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 306 bytes | 306.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/erizomovil/ProyectoLMD.git
 * [new branch]      master -> master

Jorge Gabriel Arcalá@Profesor MINGW64 ~/Documents/Proyecto_LMD (master)    
$ git add .

Jorge Gabriel Arcalá@Profesor MINGW64 ~/Documents/Proyecto_LMD (master)    
$ git commit -m "ADD proyect.xml"
[master 043bcbc] ADD proyect.xml
 1 file changed, 6 insertions(+)
 create mode 100644 proyect.xml

Jorge Gabriel Arcalá@Profesor MINGW64 ~/Documents/Proyecto_LMD (master)    
$ git push origin master
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 336 bytes | 336.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/erizomovil/ProyectoLMD.git
   0185101..043bcbc  master -> master
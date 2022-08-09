 Instrucciones para conectar clave ssh de git hub con git en computadora local
 
 
 cd .ssh
❯ lsa
drwx------. marco marco  22 B Mon Aug  8 14:08:51 2022  .
drwx------. marco marco 818 B Mon Aug  8 14:15:37 2022  ..
.rw-r--r--. marco marco  92 B Mon Aug  8 14:08:51 2022  known_hosts
 
 Generando clave
❯ ssh-keygen -t rsa -C "marco.jaramillocast@gmail.com"

confirmando-verificando coneccion

❯ ssh -T git@github.com


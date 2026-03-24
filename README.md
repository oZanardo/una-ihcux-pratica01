# una-ihcux-pratica01
Primeiro exercicio da aula de IHCUX do Daniel
ozanardo@oZanardo:~/Documents$ dir
Conclusao.jpeg	   Estudos\ TI(antigos)  Projects
CurriculoTech.pdf  Frente.jpeg		 Trás.jpeg
ozanardo@oZanardo:~/Documents$ ls -lh
total 480K
-rw-rw-r-- 1 ozanardo ozanardo  85K Mar 10 17:06  Conclusao.jpeg
-rw-rw-r-- 1 ozanardo ozanardo  55K Mar 21 08:03  CurriculoTech.pdf
drwxrwxr-x 5 ozanardo ozanardo 4.0K Mar 23 01:24 'Estudos TI(antigos)'
-rw-rw-r-- 1 ozanardo ozanardo 148K Mar 10 17:06  Frente.jpeg
drwxrwxr-x 7 ozanardo ozanardo 4.0K Mar 24 10:14  Projects
-rw-rw-r-- 1 ozanardo ozanardo 177K Mar 10 17:06  Trás.jpeg
ozanardo@oZanardo:~/Documents$ cd ..
ozanardo@oZanardo:~$ cd ..
ozanardo@oZanardo:/home$ cd ..
ozanardo@oZanardo:/$ ls
bin                dev   lib64              mnt   run                 srv       usr
bin.usr-is-merged  etc   lib.usr-is-merged  opt   sbin                swap.img  var
boot               home  lost+found         proc  sbin.usr-is-merged  sys
cdrom              lib   media              root  snap                tmp
ozanardo@oZanardo:/$ cd home/
ozanardo@oZanardo:/home$ ls
ozanardo
ozanardo@oZanardo:/home$ cd ozanardo/
ozanardo@oZanardo:~$ ls
Desktop  Documents  Downloads  Music  Pictures  Public  snap  Templates  Videos
ozanardo@oZanardo:~$ cd Documents/
ozanardo@oZanardo:~/Documents$ dir -lh
total 480K
-rw-rw-r-- 1 ozanardo ozanardo  85K Mar 10 17:06 Conclusao.jpeg
-rw-rw-r-- 1 ozanardo ozanardo  55K Mar 21 08:03 CurriculoTech.pdf
drwxrwxr-x 5 ozanardo ozanardo 4.0K Mar 23 01:24 Estudos\ TI(antigos)
-rw-rw-r-- 1 ozanardo ozanardo 148K Mar 10 17:06 Frente.jpeg
drwxrwxr-x 8 ozanardo ozanardo 4.0K Mar 24 11:48 Projects
-rw-rw-r-- 1 ozanardo ozanardo 177K Mar 10 17:06 Trás.jpeg
ozanardo@oZanardo:~/Documents$ cd Projects/
ozanardo@oZanardo:~/Documents/Projects$ ls
 algoritmosSeverino   Facul       'Projeto Faculdade IHCUX Daniel'
 CSharpProjects       LearnLinux   receitas
ozanardo@oZanardo:~/Documents/Projects$ mkdir Exercicios
ozanardo@oZanardo:~/Documents/Projects$ cd Exercicios/
ozanardo@oZanardo:~/Documents/Projects/Exercicios$ mkdir Logica
ozanardo@oZanardo:~/Documents/Projects/Exercicios$ cd ..
ozanardo@oZanardo:~/Documents/Projects$ git --version
git version 2.53.0
ozanardo@oZanardo:~/Documents/Projects$ java --version
openjdk 21.0.10 2026-01-20
OpenJDK Runtime Environment (build 21.0.10+7-Ubuntu-124.04)
OpenJDK 64-Bit Server VM (build 21.0.10+7-Ubuntu-124.04, mixed mode, sharing)

# Terminal y Línea de Comandos

## Organizar Sistema de Archivos
- [`ls` - list directory contents](https://linuxcommand.org/lc3_man_pages/ls1.html)
- [`pwd` - Print the name of the current working directory](https://linuxcommand.org/lc3_man_pages/pwdh.html)
- [`touch` - change file timestamps](https://linuxcommand.org/lc3_man_pages/touch1.html)
- [`cd` - Change the shell working directory](https://linuxcommand.org/lc3_man_pages/cdh.html)
- [`mkdir` - make directories](https://linuxcommand.org/lc3_man_pages/mkdir1.html)
- [`cp` - copy files and directories](https://linuxcommand.org/lc3_man_pages/cp1.html)
- [`mv` - move (rename) files](https://linuxcommand.org/lc3_man_pages/mv1.html)
- [`rm` - remove files or directories](https://linuxcommand.org/lc3_man_pages/rm1.html)
- [`rmdir` - remove empty directories](https://linuxcommand.org/lc3_man_pages/rmdir1.html)

## Manejo de Archivos de Texto
- [`vim` - Vi IMproved, a programmer's text editor](https://linuxcommand.org/lc3_man_pages/vim1.html)
- [`nano` - Nano's ANOther editor, inspired by Pico](https://linuxcommand.org/lc3_man_pages/nano1.html)
- [`cat` - concatenate files and print on the standard output](https://linuxcommand.org/lc3_man_pages/cat1.html)
- [`head` - output the first part of files](https://linuxcommand.org/lc3_man_pages/head1.html)
- [`tail` - output the last part of files](https://linuxcommand.org/lc3_man_pages/tail1.html)
- [`grep`, `egrep`, `fgrep` - print lines that match patterns](https://linuxcommand.org/lc3_man_pages/grep1.html)
- [`sed` - stream editor for filtering and transforming text](https://linuxcommand.org/lc3_man_pages/sed1.html)
- [`awk`, `gawk` - pattern scanning and processing language](https://linuxcommand.org/lc3_man_pages/awk1.html)

## I/O Redirection
- [`ls > file_list.txt`, `ls >> file_list.txt` - Standard Output](https://linuxcommand.org/lc3_lts0070.php)
- [`sort < file_list.txt`, `sort < file_list.txt > sorted_file_list.txt` - Standard Input](https://linuxcommand.org/lc3_lts0070.php)
- [`ls -l | less` - Pipelines](https://linuxcommand.org/lc3_lts0070.php)

### Filtros
- [more - file perusal filter for crt viewing](https://linuxcommand.org/lc3_man_pages/more1.html)
- [wc - print newline, word, and byte counts for each file](https://linuxcommand.org/lc3_man_pages/wc1.html)

## Procesos en background y foreground
- [`<orden_a_ejecutar> &` - Putting a Program into the Background](https://linuxcommand.org/lc3_lts0100.php)
- [`bg` - Move jobs to the background](https://linuxcommand.org/lc3_man_pages/bgh.html)
- [`fg` - Move job to the foreground](https://linuxcommand.org/lc3_man_pages/fgh.html)
- [`fg` - Move job to the foreground](https://linuxcommand.org/lc3_man_pages/fgh.html)
- [`ps` - report a snapshot of the current processes](https://linuxcommand.org/lc3_man_pages/ps1.html)
- [`top` - display Linux processes](https://linuxcommand.org/lc3_man_pages/top1.html)
- [`jobs` - Display status of jobs](https://linuxcommand.org/lc3_man_pages/jobsh.html)
- [`kill` - Send a signal to a job](https://linuxcommand.org/lc3_man_pages/killh.html)

## Sistemas de Permisos
- [`chmod` - change file mode bits](https://linuxcommand.org/lc3_man_pages/chmod1.html)
- [`su` - run a command with substitute user and group ID](https://linuxcommand.org/lc3_man_pages/su1.html)
- [`sudo`, `sudoedit` — execute a command as another user](https://linuxcommand.org/lc3_man_pages/sudo8.html)
- [`chown` - change file owner and group](https://linuxcommand.org/lc3_man_pages/chown1.html)
- [`chgrp` - change group ownership](https://linuxcommand.org/lc3_man_pages/chgrp1.html)

### Procesos de apoyo
- [`ls -l /bin/bash` - File Permissions](https://linuxcommand.org/lc3_lts0090.php)

## Manejo de Paquetes
- [`sudo apt install nmap` - Install a Package](https://ubuntu.com/server/docs/package-management)
- [`sudo apt remove nmap` - Remove a Package](https://ubuntu.com/server/docs/package-management)
- [`sudo apt update` - Update the Package Index](https://ubuntu.com/server/docs/package-management)
- [`sudo apt upgrade` - Upgrade Packages](https://ubuntu.com/server/docs/package-management)

### Archivos y carpetas con los datos de apt
- `/etc/apt/sources.list` - file
- `/etc/apt/sources.list.d` - directory

## Compresión y combinación de archivos

## Referencias
- [Linux Commands - Manual Pages](https://linuxcommand.org/lc3_man_page_index.php)
- [Linux Commands - I/O Redirection](https://linuxcommand.org/lc3_lts0070.php)
- [Linux Commands - Job Control](https://linuxcommand.org/lc3_lts0100.php)
- [Ubuntu - Package Management](https://ubuntu.com/server/docs/package-management)

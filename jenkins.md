# Jenkins
## Instalación y Configuración Básica
- [Instalación Java 8](https://www.jenkins.io/doc/book/installing/linux/#installation-of-java)
- [Instalación Jenkins](https://www.jenkins.io/doc/book/installing/linux/#long-term-support-release)
  - [Jenkins 2.235.3: New Linux Repository Signing Keys](https://www.jenkins.io/blog/2020/07/27/repository-signing-keys-changing/#debianubuntu)
```
$ sudo su
# wget -qO - https://pkg.jenkins.io/debian-stable/jenkins.io.key | apt-key add -
# exit
$ sudo sh -c 'echo deb https://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
$ sudo apt update
$ sudo apt install git jenkins
```
- [Crear una llave ssh](https://www.ssh.com/ssh/keygen/#creating-an-ssh-key-pair-for-user-authentication)
- [Start y Status Jenkins](https://www.jenkins.io/doc/book/installing/linux/#start-jenkins)
- [Post-instalación](https://www.jenkins.io/doc/book/installing/linux/#unlocking-jenkins)

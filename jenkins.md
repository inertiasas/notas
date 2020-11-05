# Jenkins
## Instalación y Configuración Básica
- [Instalación Java 8](https://www.jenkins.io/doc/book/installing/linux/#installation-of-java)
  - `sudo apt install openjdk-8-jdk wget gnupg`
- [Instalación Jenkins](https://www.jenkins.io/doc/book/installing/linux/#long-term-support-release)
  -[gpg: no valid OpenPGP data found](https://stackoverflow.com/a/38039880)
    `wget --no-check-certificate -qO - http://pkg.jenkins-ci.org/debian/jenkins-ci.org.key | sudo apt-key add -`

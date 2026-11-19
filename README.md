# INFOM124-STUDENTS-26-27 test PR

## Practical courses - 2026-2027

This repository contains the JPacman project that will be used during the practical courses of "INFOM124 - Vérification et validation logicielle"

## Requirements

All the requirements discussed in this section refer to Linux or macOS distributions. If you are on Windows, you can install a Linux kernel so that you can use the same command lines as Linux or macOS, by following [this tutorial](https://www.ssl.com/fr/comment/activer-le-sous-syst%C3%A8me-linux-installer-ubuntu-windows-10/).

The only mandatory requirement is IntelliJ. The execution of the tests and almost all commands can be executed within the IntelliJ environment. For those who do not want to go through IntelliJ can follow the below sections to install and configure their computer to run the commands.

### Java

JDK 17 (or openJDK 17) or newer JDK version is required for this project. Here are the steps of installation of openJDK 17 on Linux and macOS distributions (for Windows, see [this tutorial](https://java.tutorials24x7.com/blog/how-to-install-openjdk-17-on-windows)).

Installation:

```console
sudo apt update
sudo apt install openjdk-17-jdk openjdk-17-jre
```

Check the successful installation:

```console
java --version
```

If the returned version is openjdk 17, the installation is complete!

### Maven

This project uses Maven. The installation of Maven is not mandatory but you can do it if you want.

> "Apache Maven is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information."
> -- <cite>[Apache Maven website](https://maven.apache.org/)</cite>

Maven should be installed on your computer. There are two possibilities:

1. Command line: check the [Maven website](https://maven.apache.org/install.html) (or [this tutorial for Windows](https://phoenixnap.com/kb/install-maven-windows)) for installation.
2. Maven integration with your IDE: check in function of the IDE you use

After the installation is complete, run:

```console
mvn -v
```

The result should be similar to the image below. Make sure the Java version is 17!
![](images/maven-version.png)

## Documentation

If you find any relevant doc, tell me so that I can add it to this section ;)

### AssertJ

- AssertJ official doc: [https://assertj.github.io/doc/](https://assertj.github.io/doc/)
- Basic assertions: [https://ngeor.com/2018/04/22/assertj-cheatsheet.html](https://ngeor.com/2018/04/22/assertj-cheatsheet.html)
- Iterable contains assertions: [https://ted.dev/assets/AssertJ%20Iterable%20contains%20assertions%20%5BCheat%20Sheet%5D%20-%20draft%20Jan%209%202023.pdf](https://ted.dev/assets/AssertJ%20Iterable%20contains%20assertions%20%5BCheat%20Sheet%5D%20-%20draft%20Jan%209%202023.pdf)

### jUnit 5

- Official jUnit 5 website: [https://junit.org/junit5/](https://junit.org/junit5/)
- Cheat sheet: [https://cheatography.com/cs8898/cheat-sheets/junit-5/pdf/](https://cheatography.com/cs8898/cheat-sheets/junit-5/pdf/)

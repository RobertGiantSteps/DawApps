# DawAppspara instalar el paquete completo del entorno de ejecución o JRE:
~$ sudo apt install -y default-jre

Y para su versión headless:
~$ sudo apt install -y default-jre-headless

En en caso de necesitar el kit de desarrollo o JDK, podemos instalar el paquete completo:
~$ sudo apt install -y default-jdk

O su versión headless:
~$ sudo apt install -y default-jdk-headless
Versión instalada

Sea cual sea la versión de Java instalada en Ubuntu 20.04 es fácil comprobarla simplemente lanzando en consola el comando java -version
:


[java copia.md](https://github.com/RobertGiantSteps/DawApps/files/7375351/java.copia.md)
![java](https://user-images.githubusercontent.com/91851811/137957222-3958997b-ed45-435a-8574-8a22424cd438.png)


Comprobar la versión de Maven

La instalación de Apache Maven es un proceso muy simple. Está disponible en el repositorio oficial de Ubuntu 16.04. Puede verificar la versión exacta ejecutando el siguiente comando

apt-cache show maven | Versión grep Versión: 3.3.9-3
Para continuar con la instalación, ejecute el siguiente comando

apt-get -y install maven
Esto instalará la última versión de Maven 3 disponible en el repositorio entre todas las dependencias de Maven, incluida Java.

Una vez completada la instalación, puede verificar si Maven se instaló correctamente en su servidor Ubuntu 16.04, use el siguiente comando

mvn --version
El resultado debe ser similar a

Apache Maven 3.3.9 Maven home: / usr / share / maven Versión de Java: 1.8.0_151, proveedor: Oracle Corporation Java home: / usr / lib / jvm / java-8-openjdk-amd64 / jre Locale predeterminado: en_US, codificación de plataforma: ANSI_XXXNUM. Nombre del SO 3.4: "linux", versión: "1968-2.6.32stab042", arch: "amd127.2", familia: "unix"
[Maven copia.md](https://github.com/RobertGiantSteps/DawApps/files/7375385/Maven.copia.md)
![Maven](https://user-images.githubusercontent.com/91851811/137958177-45f09408-6ea3-4d11-98e9-0a8984645193.png)

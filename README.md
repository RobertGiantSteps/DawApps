# DawAppspara Roberto Martínez Pereira grupo B IDE's:
Istalacion del jdk-jre:
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

Los paquetes Snap son paquetes de software universales prediseñados que se envían con las bibliotecas y dependencias requeridas por el paquete de software. Son independientes de la distribución y se pueden instalar en cualquier distribución principal de Linux. Los snaps son populares ya que no requieren ninguna dependencia durante la instalación, lo que hace que el proceso de instalación sea fluido y sin errores.

Para Ubuntu 18.04 y 20.04, Snap ya viene habilitado. Otras distribuciones que vienen con snap habilitado también incluyen KDE Neon y Solus 3 y versiones posteriores.
Para instalar la edición Community, ejecute el siguiente comando:

$ sudo snap install intellij-idea-community --classic
Para la Ultimate Edition, ejecute:

$ sudo snap install intellij-idea-ultimate --classic
Y finalmente, para la versión educativa, invoque el comando:

$ sudo snap install intellij-idea-educational --classic
Esto debería llevar unos minutos y debería continuar sin problemas.

![ IntelliJ](https://user-images.githubusercontent.com/91851811/137960573-a205e431-bbea-4003-9fd1-d49c217eee0b.png)
Instalación de Netbeans:
Instalar la última versión estable de NetBeans IDE 12Primero necesitas instalar Java JDK de los repositorios estándar como se muestra.

$ sudo apt update
$ sudo apt install default-jdk
A continuación, verifique el Java JDK Ejecución.

$ java -version
3ro Ahora abra un navegador, navegue a la página de descarga de NetBeans IDE y descargue la última NetBeans IDE Script de instalación (Apache-NetBeans-12.0-bin-linux-x64.sh) para su distribución de Linux instalada.

Alternativamente, también puedes descargar NetBeans IDE Instale el script en su sistema utilizando la utilidad wget ingresando el siguiente comando.

$ wget -c https://downloads.apache.org/netbeans/netbeans/12.0/Apache-NetBeans-12.0-bin-linux-x64.sh
4to Una vez completada la descarga, navegue al directorio en el que se encuentra el directorio NetBeans IDE El instalador se ha descargado y está emitiendo el siguiente comando para hacer que el script de instalación sea ejecutable y comenzar la instalación.

$ chmod +x Apache-NetBeans-12.0-bin-linux-x64.sh 
$ ./Apache-NetBeans-12.0-bin-linux-x64.sh
5) Después de ejecutar el script de instalación anterior, el instaladorPágina de inicio«Se muestra de la siguiente manera, haga clic en El proximo para continuar (o personalizar su instalación haciendo clic en Ajustar) para seguir el asistente de instalación.![ IntelliJ](https://user-images.githubusercontent.com/91851811/137961257-3b5ec9be-e3a9-4813-bb22-1a5d891d219e.png)
VSCODE:
Los paquetes Snap son seguros y fáciles de actualizar. A diferencia de los paquetes deb estándar, las instantáneas de snap tienen una huella de disco más grande y un tiempo de inicio de la aplicación más largo.

Los paquetes Snap se pueden instalar desde la línea de comandos o mediante la aplicación de software de Ubuntu. Para instalar el complemento VS Code, abra su terminal (Ctrl+Alt+T) y ejecute el siguiente comando:

sudo snap install --classic code
Siempre que se lanza una nueva versión, el paquete de Visual Studio Code se actualizará automáticamente en segundo plano.
![vscode](https://user-images.githubusercontent.com/91851811/137961958-799bb96d-6d4f-4a1f-a4b6-cd3bb5c86cd4.png)

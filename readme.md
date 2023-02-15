# Intro a la web

## Table of Contents

1. [Redes e Internet](#redes-e-internet)
2. [Desarrollo web](#desarrollo-web)
3. [VS Code](#vs-code)
4. [Terminal](#terminal)
5. [Git](#git)
6. [Github](#github)
7. [Navegador](#navegador)
8. [Html](#html)
9. [Css](#css)
10. [Flexbox](#flexbox)
11. [CSS Grid](#css-grid)
12. [Responsive design](#responsive-design)
13. [Best practices](#best-practices)
14. [Glosario](#glosario)
15. [Recursos](#recursos)

* devf
  * kata-1
    * intro-web-gen24c
    * juanito-intro-web-gen24c
  * kata-2
    * intro-js
    * juanito-intro-js

### Redes e internet

**¿Qué es una red?**

Es un conjunto de dispositivos informaticos y software conectados entre sí por medio de dispositivos físicos que envían y reciben datos. Una red permite compartir información, recursos y ofrecer servicios.

**¿Qué es Internet y qué es la web?**

Es una  **red de computadoras interconectadas a nivel mundial en forma de tela de araña** . Consiste de servidores (o "nodos") que proveen información a aproximadamente 100 millones de personas que están conectadas entre ellas a través de las redes de telefonía y cable.

**Arquitectura Cliente-Servidor**

Es una arquitectura que representa una forma de abstraccion para la comunicacion entre dispositvos informaticos o software.

En una arquitectura Cliente-Servidor existe un **servidor** y **múltiples clientes** que se conectan al servidor para recuperar todos los recursos necesarios para funcionar, en este sentido, el cliente solo es una capa para representar los datos y se detonan acciones para modificar el estado del servidor, mientras que el servidor es el que hace todo el trabajo pesado.

**Navegadores web**

Es un programa que permite ver la información que contiene una página web. El navegador interpreta el código, HTML generalmente, en el que está escrita la página web y lo presenta en pantalla permitiendo al usuario interactuar con su contenido y navegar.

Para un desarrollador front end es importante comprender que un navegador interpreta 3 lenguajes para renderizar una pagina:

* **Html:** Para definir la estructura.
* **CSS:** Para estilizar el sitio.
* **JS:** Para volver funcional e interactiva la pagina web.

**Cómo funcionan los sitios web**

El navegador como cliente solicita al servidor una url desde la que se descargan recursos (html, css, js, img, mp3, etc) y que interpreta para mostrarlos como una pagina web.


**Proveedores de Internet**

Un ISP (Internet Service Provider) generalmente es una empresa dedicada a ofrecer servicios de conexciona internet.


**Dominios**

Un **dominio web** es el nombre único que recibe un sitio web en internet. Este nombre identifica a una página web concreta sin que puedan existir dos o más sitios web que compartan el mismo nombre de dominio.

A continuacion se muestran las partes de una url, donde se observa que parte corresponde al dominio.

![1676424790021](image/readme/1676424790021.png)

**Protocolo:** Un protocolo es el conjunto de reglas que se establecen para el uso de una determinada tecnologia. El protocolo http/https son protocolos para la comunicacion en internet (transferencia de hypertexto).

**Path:** Es una ruta donde se ubican archivos en un servidor.


**Hosting**

Es el alojamiento que tiene un sitio web para poder ser accesible a traves de internet (desde cualquier parte del mundo).



**Direcciones IP**

Una direccion IP (Internet Protocol) es la representacion de un dominio mediante 4 octetos de bytes. Sirve para identificar un dispositvo en la red.

**Tipos de IP**

* **Privadas:** Direccion IP que identifica a un dispositivo en una red local.
* **Publicas:** Direccion IP que nos identifica en internet.


**Dynamic Host Configuration Protocol (DHCP)**

DHCP  asigna automáticamente direcciones de protocolo de Internet (IP) a los equipos de la red, si la red lo admite .



**Domain Name Server (DNS)**

Su función más importante es «traducir» nombres inteligibles para las personas (nombres de dominio) en identificadores binarios (direcciones IP) asociados con los equipos conectados a la red, esto con el propósito de poder localizar y direccionar estos equipos mundialmente.

![](https://d1.awsstatic.com/Route53/how-route-53-routes-traffic.8d313c7da075c3c7303aaef32e89b5d0b7885e7c.png)





### Desarrollo web

Tecnologías y herramientas para el desarrollo web

**Front end**

* Lenguajes
  * HTML (De marcado de hypertexto).
  * CSS (De estilos en cascada).
  * JavaScript (Lenguaje de programacion).
* Frameworks
  * React.
  * Angular.
  * Vuejs.

**Back end**

* Lenguajes de programacion
  * Node.
  * Java.
  * Php.
  * Python.
  * C#.
  * Go.
* Frameworks
  * Express.
  * Spring.
  * Laravel.
  * Django.
  * .NET.
  * Gin.

**Gestores de base de datos**

* SQL
  * PostgresSQL.
  * MySQL.
  * SQLServer.
  * Oracle.
  * MariaDB.
* NO SQL
  * MongoDB.
  * DynamoDB.
  * Cassandra.


## **¿Qué es frontend?**

Es el area de desarrollo enfocada en la construccion de un sitio web. Tanto del diseño y estructura, estilos (colores, fondos, tamaños, animaciones y efectos) e interactividad de los elementos con el usuario.

Es todo el código que se ejecuta en el navegador de un usuario, al que se le denomina una aplicación cliente, es decir, todo lo que el visitante ve y experimenta de forma directa.

## **¿Qué es backend?**

El backend procesa la información que alimentará el frontend de datos. Es la capa de acceso a los datos, ya sea de un software o de un dispositivo en general, es la lógica tecnológica que hace que una página web funcione, lo que queda oculto a ojos del visitante.

Trabajar en este apartado supone algo totalmente diferente al frontend, ya que exige conocimientos de logica, optimizacion de recursos, seguridad de un sitio, entre otros.


### VS Code

Es un editor de código fuente desarrollado por Microsoft. Es software libre y multiplataforma, está disponible para Windows, GNU/Linux y macOS. VS Code tiene una buena integración con Git, cuenta con soporte para depuración de código, y dispone de un sinnúmero de extensiones, que básicamente te da la posibilidad de escribir y ejecutar código en cualquier lenguaje de programación.

**Editor de texto**

Es un [programa informático](https://es.wikipedia.org/wiki/Programa_inform%C3%A1tico "Programa informático") que permite crear y modificar [archivos digitales](https://es.wikipedia.org/wiki/Archivo_(inform%C3%A1tica)) compuestos únicamente por textos sin formato, conocidos comúnmente como [archivos de texto](https://es.wikipedia.org/wiki/Archivo_de_texto "Archivo de texto") o “texto plano”. En ocasiones tienen algunas herramientas para codificar.

**Integrated Development Enviroment (IDE)**

Un entorno de desarrollo integrado (IDE) es un software para el diseño de aplicaciones que combina herramientas del desarrollador comunes en una sola interfaz gráfica de usuario (GUI). Generalmente, un IDE cuenta con las siguientes características:

* **Editor de código fuente** : editor de texto que ayuda a escribir el código de software con funciones como el resaltado de la sintaxis con indicaciones visuales, el relleno automático específico para el lenguaje y la comprobación de errores a medida que se escribe el código.
* **Automatización de las compilaciones locales** : herramientas que automatizan las tareas sencillas y repetitivas como parte de la creación de una compilación local del software para que use el desarrollador, como la compilación del código fuente de la computadora en código binario, el empaquetado de ese código y la ejecución de pruebas automatizadas.
* **Depurador** : programa que sirve para probar otros programas y mostrar la ubicación de un error en el código original de forma gráfica

**Instalación VSC**
Manejo de directorios y archivos VSC
Emmet
**Extensiones recomendadas**

* Auto Rename Tag.
* Color info.
* Diff.
* Es lint.
* Live share.
* Office viewer (markdown)
* Peacock.
* Vscode/pdf

### Terminal

La terminal o consola es una forma generalizada de llamar a la interfaz de línea de comandos: una pantalla (generalmente, de color de fondo negro con letras blancas). Sirve para escribir comandos  con los que ordenamos al sistema realizar acciones concretas.



**Path**

Una ruta o path indica una ubicación a nivel de carpeta de algun fichero dentro del
sistema de archivos.
**Ejemplos de rutas**

```
/# Raiz
/

/# Significa ahi mismo
./

/# Regresar un nivel de carpetas../
../../
```



Uso de comandos básicos

Listado de comandos

```
# imprime el path en el que se encuentra
pwd

# moverse entre carpetas
cd

# listar carpetas y archivos que hay en el directorio actual
ls

# crear carpetas
mkdir newFolder

# crear archivos
touch nameFile.txt

# eliminar carpetas
rmdir folderName

# eliminar archivos
rm fileName.txt

# comprobar conexión a internet
ping www.google.com

# limpiar la pantalla
clear

```




ejemplo de combinacion de comandos
cd ..
cd ..
cd ..
cd desktop

cd ../../../desktop

cd ~/desktop

ctrl + c : detiene procesos en la terminal

Cuando un comando lleva -x y letras son PARAMETROS de como se debe ejecutar.

### Git

Instalación

#### Commits Atómicos

Consiste en realizar un commit por un solo objetivo. Es decir, no mezclar muchas soluciones en el mismo commit.

#### Conventional Commits

Es una especificación sobre como escribir mensajes de confirmación (commits).

**Estructura**

```
[optional scope]: [optional body][optional footer(s)]
```

**Tipos principales**

* feat: Nuevas caracteristicas.
* chore: Cosas que no aportan un req funcional pero posiblemente si un req no funcional.
* fix: Correccion de errores.
* docs: Commits con documentacion o comentarios.
* style: Estructura de carpetas y nombrado.

#### Información del repo

```
# ver estado del working directory y staging area
git status

# ver historial de commits
git log --oneline
```

#### Generar llave ssh

```
# generar ssh key
ssh-keygen

# ver llave p[ublica
cat ~/.ssh/id_rsa.pub
```

#### Hacer un commit

```
# agregar al staging area
git add .

# quitar del staging area
git restore --staged namefile.txt

# hacer un commit al repo local
git commit -m "conventionalCommitScope: mi mensaje"

```

#### Semantica de mensajes "commit"

Un pequeño cambio en nuestros mensajes commit  puede convertirnos en mejores programadores.

Formato: `<tipo>(<alcance>): <asunto>`

`<alcance>` es opcional

## Ejemplo

```
feat: add hat wobble
^--^  ^------------^
|     |
|     +-> Resumen en tiempo presente.
|
+-------> Tipo: chore(tarea), docs(documentos), feat(logro), fix(corrección), refactor(refactorización), style(estilo), or test(prueba).
```

Mas ejemplos:

- `feat`: (nueva función para el usuario, no una nueva función para el script de compilación)
- `fix`: (corrección de errores para el usuario, no una corrección para un script de compilación)
- `docs`: (cambios en la documentación)
- `style`: (formato, falta de punto y coma, etc.; no hay cambio de código de producción)
- `refactor`: (refactorización de código de producción, por ejemplo, cambio de nombre de una variable)
- `test`: (agregando pruebas faltantes, refactorizando pruebas; sin cambio de código de producción)
- `chore`: (actualización de tareas grunt, etc.; sin cambio de código de producción)

Referencias:

- https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716
- https://www.conventionalcommits.org/
- https://seesparkbox.com/foundry/semantic_commit_messages
- http://karma-runner.github.io/1.0/dev/git-commit-msg.html

Esta es una traduccion al español de [Josh Buchea] (https://gist.github.com/joshbuchea) por [Daniel Gloria](https://gist.github.com/dannielgloria).

#### Remoto

```
# ver los repos remotos a los que esta conectado el repo local
git remote -v

# bajar cambios
git pull origin branchName

# subir cambios
git push origin branchName

# subir cambios de una rama nueva para el remoto
git push -u origin branchName

# obtener los cambios de una rama remota y cambiarse a esa rama
git fetch && git checkout develop

#  bajar cambios de una rama remota a una local (cuando ya existe)
git pull origin branchName

# agregar una direccion remoto (origin)
git remote add origin myUrl

# modificar una direccion remoto (origin)
git remote set-url origin myUrl

```

#### Administración de ramas

```
# ver rama en la que se encuentra el head
git branch 

# crea una rama nueva
git branch newBranchName 

# cambiarse a una rama con el nombre nombreRama
git checkout branchName

# crear y cambiarse a una nueva rama
git checkout -b newBranchName

# crear y cambiarse a una nueva rama
git switch -c newBranchName 

# eliminar una rama
git branch -D branchName

```

#### Otros comandos útiles

```
# Descarta los cambios del stagin y working directory
git reset --hard

# actualiza la cache de git para que tome ciertos cambios (.gitignore)
git rm --cached . r

# actualiza el mensaje del ultimo commit realizado (no debe estar pusheado)
git commit --amend -m "an updated commit message"

# stash: el codigo de working directory y staging area es eliminado temporalmente
git stash

# stash: el codigo de working directory y staging area que fue eliminado se recuperar
git stash pop

```

[Más info](https://www.conventionalcommits.org/en/v1.0.0/)

#### **VSCode como editor de git**

```
git config --global core.editor"visual studio --wait"
git commit
// ir a vscode a escribir el mensaje, una vez escrito guardar y cerrar.
// regresar a la consola a comprobar el commit

```


Configuraciones iniciales
Crear un repositorio
Comandos básicos de Git

Extensiones para vscode
    git graphgit blame
    commits en vscode

### Github

Crear cuenta en Github
Clonar repositorios

Llave ssh y porq es mejor q http
Subir tus archivos y actualizar tus repositorios

Casos para conectartse a un repo remoto

### Navegador

Uso del inspector de elementos

Herramientas de desarrollador

### Html

Documentos HTML

Etiquetas y partes de una etiqueta
Sintaxis y creación de documentos HTML
Visualización de HTML en el navegador
Consulta y uso de la documentación oficial
Elementos de estructura
Elementos básicos
Elementos div
Elementos semánticos

Formularios
Figma

### Css

Intro a CSS

Estado del arte
Box model

Display: inline vs block
Diseño y disposición de elementos en un sitio web
Manejo de estilos de un documento HTML con CSS
Consulta y uso de la documentación oficial
Cómo vincular CSS con HTML
Selectores

Displays

Float
Position

### Flexbox

### CSS Grid

### Responsive design

Media Queries
Vista de dispositivos desde inspector de elementos

### Best practices

XHTML
SEO basico
Accesibilidad
¿qué son las convenciones y mejores practicas?

### Glosario

**Red de computadoras:**

**Internet:** Red conformada por todas las redes del mundo para comunicarse y compartir informacion.
**Web:** Conjunto de información que se encuentra en una dirección determinada de internet.
**World Wide Wibe:** Es un sistema que funciona a través de internet, por el cual se pueden transmitir contenido basado en estandares web.
**Plugin:** Software pequeño que sirve como complemento de otro para un fin en especifico.
**Proceso:** Cualquier tarea que ocurre en nuestro informatico

**Proceso en segundo plano:** Es un proceso que el usuario no tiene que hacer algo para que suceda.
**Carpeta home:** carpeta de su usuario /Users/montoyitag (~/)
**Carpeta raiz:** Es la base de nuestro disco duro. Por ejemplo: disco C:\ o en linux /

**Hosting:** Un hosting  **es un servicio de alojamiento para páginas web bajo un servidor** .


**Sistema operativo:** Es el software que coordina y dirige todos los servicios y aplicaciones que utiliza el usuario en una computadora.

**Kernel:** El kernel es el núcleo de un sistema operativo y, por tanto, la interfaz (middleware) entre el software y el hardware.

**Ip:** La dirección IP es una etiqueta numérica, por ejemplo "192.0.10.1" que identifica, de manera lógica y jerárquica, a una interfaz en la red. Existen IP públicas y IP privadas.

**Dominio:**  Es una dirección web compuesta por un nombre de sitio web y una extensión de dominio. Ejemplo: google.com

**URL:** Es una dirección web compuesta por al menos el protocolo, dominio y ruta.

**DNS:** Es un tipo de servidor de redes de computadora que en encarga de convertir direcciones web en dominios IP y viceversa. Ejemplo: 8.8.8.8 => www.google.com

**Cliente:** Es quien solicita información dentro de un sistema informatico.

**Servidor:** Es una instancia fisica o lógica que responde peticiones (request).


### Recursos

SoloLearn/Absolute => Rapidin
Fazt/W3Schools => Mas completo y estructurado

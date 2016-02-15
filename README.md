# __Práctica 1 - Tareas iniciales__

En este tutorial se describirá los pasos necesarios  para configurar:

+  Github
+ Nodejs
  - Express
+ Campus virtual
 - Foto de perfil
+ Atom
+ Cloud9
+ Markdown
+ Traductores Markdown -> HTML
 - Pandoc
 - Kramdown


# 1. Github

### 1.1. Introducción a los conceptos
Para empezar necesita tener cuenta en [Github](https://github.com/), así que si no la tiene, créela.

En este apartado se definirán varias funcionalidades y conceptos de Github, como:
+ Github Classrom
+ Repository
+ Fork
+ Commit
+ Push/Sync
+ Pull request
+ Github Pages
+ Issues

__Si usted conoce estas funcionalidades puede saltarse la introducción (1.1).__

###### 1.1.1. [Github Classroom](https://education.github.com/guide)

Una clase (classroom) en Github es una [organización](https://help.github.com/articles/what-s-the-difference-between-user-and-organization-accounts/) en la cual se pueden asignar programas de estudio  a los alumnos y éstos pueden crear __Issues__ para clarificar cuestiones. Además, si el respositorio es público, otros profesores podrán colaborar con usted para mejorar la calidad de sus materias. En el apartado __1.2__ se explica el caso concreto de esta primera práctica.


###### 1.1.2. Repository

Un repositorio es el elemento más básico de GitHub. Es prácticamente un directorio de un proyecto. Un repositorio contiene todos los ficheros de un proyecto (incluyendo la documentación), y almacena todo el historial de cambios de cada uno. Los repositorios pueden tener varios colaboradores y pueden ser públicos o privados.

###### 1.1.3. [Fork](https://guides.github.com/activities/forking/)

Crear una bifurcación (fork) es producir una copia personal del proyecto de otro. Forks actúa como una especie de puente entre el repositorio original y su copia personal. Puedes además enviar un __Pull Requests__ para ayudar a otras personas a realizar mejores proyectos aportando tus mejoras al proyecto original. __Forking es la base de la codificación social en GitHub.__

###### 1.1.4. [Commit](https://git-scm.com/docs/git-commit)

`git commit` es el comando que permite guardar los cambios de un repositorio local para posteriormente mandarlos a un repositorio remoto con un __Push__.

###### 1.1.5. Push

Cuando tu proyecto está en un punto en el que deseas compartirlo, tienes que pushearlo con el comando `git push`. Este comando solo funciona si el proyecto ha sido clonado desde un servidor en el que tienes acceso y si nadie ha pusheado mientras tanto.

###### 1.1.6. Pull Requests

Un pull request es una petición que el propietario de un fork de un repositorio hace al propietario del repositorio original para que este último incorpore los commits que están en el fork.

###### 1.1.7. Github Pages

Una Github Page es una página web pública hosteada y publicada a través de Github. De modo que nuestro perfil de usuario o un respositorio puede tener asociada una.

###### 1.1.8. Issues

Las Issues son buenas para tener un seguimiento de las tareas, mejoras y bugs de nuestros proyectos. Son como una especie de email excepto que son compartidas por todo el equipo del proyecto.



### 1.2. Crear nuestro repositorio perteneciente a la Classroom ULL-ESIT-GRADOII-PL

Como hemos visto anteriormente una clase es una organización con asignaciones, por lo tanto vamos a solicitar la creación de nuestro resitorio el la clase.

###### 1.2.1 Creación de repositorio

Para ello debemos entrar en el link que se muestra a continuación:


![](./images/PL-1.2-1.jpg)

Entramos y se nos mostrará una propuesta para aceptar el acceso a un repositorio que se creará llamado *tareas-iniciales-nombreUsuario* que justamente es el nombre usuario con el que estamos logeados que en mi caso es alu0100824780:

![logo](./images/PL-1.2-2.jpg)

Le damos a __Accept this assignment__ y esperamos a que nos manden una confirmación al email.

Cuando nos manden el email se habrá creado un repositorio en la cuenta del profesor como se muestra a continuación:

![repository](./images/PL-1.2-3.jpg)


###### 1.2.2. Fork del repositorio

Muy bien, ahora ya tenemos nuestro "espacio" en la clase por lo tanto ahora tenemos que hacer un __fork__ para tener una copia del respositorio en nuestra cuenta. Para ello simplemente clickeamos en el botón *Fork*:

![fork](./images/PL-1.2-4.jpg)


Ahora simplemente esperamos y nos redirigirá a la copia creada en nuestra cuenta:


![our_repository](./images/PL-1.2-5.jpg)

Además, podemos fijarnos que nos indica dónde se encuentra el repositorio original:

![original_repository](./images/PL-1.2-6.jpg)


###### 1.2.3. Clonación del repositorio

Ahora es hora de clonar el respositorio en nuestro ordenador para poder trabajar en él. Para ello simplemente cogemos el link SSH o HTTPS, vamos a nuestra terminal y,  colocados en el directorio en donde queremos crear el repositorio ejecutamos el comando:

`git clone git@github.com:usuario/tareas-iniciales-usuario.git`

Donde claramente usuario es vuestro nombre de usuario.

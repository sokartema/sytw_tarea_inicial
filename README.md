### Sistemas y Tecnologías Web: Tarea inicial

**Autor:** Jazer Abreu Chinea -> alu0100595727

## Instalación de rvm o rbenv 

En primer lugar instalamos rvm o rbenv los cuales te permiten instalar, administrar y utilizar en cualquier momento diferentes versiones de ruby.

En mi caso, he elegido seguir utilizando rvm ya que lo he utilizado anteriormente y estoy familiarizado con el.

A continuacion una imagen de mi version actual de rvm:

![Alt text](https://raw.githubusercontent.com/alu0100595727/sytw_tarea_inicial/master/imagenes/rvm1.png)


En el caso de que no lo tengamos instalado podemos seguir el siguiente enlace para la instalacion de rvm [aquí](http://rvm.io/rvm/install).

Cuando lo tengamos instalado y en el caso de que nos de un error al intentar cambiar la version de ruby como el siguiente: 

> rvm is not a function
 
Se debe ir a las preferencias de perfil en la consola y seleccionar la opcion de utilizar los comandos como si fuese una consola remota. En el siguiente enlace se explica como hacerlo perfectamente: [enlace](https://rvm.io/integration/gnome-terminal)

**Comandos mas importantes**

`rvm install "version"` -> instalar una version de ruby

`rvm list` -> para ver las versiones de ruby instaladas

`rvm use "version"` -> para utilizar una version de ruby en concreto

`rvm --default use "version"` -> para utilizar una version de ruby por defecto

## Ruby

En mi caso tengo la version 1.9.3p194 como se muestra en la siguiente imagen, aunque tambien tengo instalada la 2.1.1.

![Alt text](https://raw.githubusercontent.com/alu0100595727/sytw_tarea_inicial/master/imagenes/ruby1.png)

El comando apropiado a utilizar para instalar las diferentes versiones de ruby ya que tenemos rvm seria: `rvm install "version"`

## Bundler

Bundler nos permite instalar las diferentes gemas requeridas para un proyecto ruby, las cuales las especificamos dentro de un fichero Gemfile que nosotros crearemos.

En primer lugar debemos instalar la gema bundler con el siguiente comando:
`sudo gem install bundler`

![Alt text](https://raw.githubusercontent.com/alu0100595727/sytw_tarea_inicial/master/imagenes/bundler1.png)

Y a continuacion comprobamos que bundler funciona, para ello ejecutamos `bundle install` dentro de un proyecto que tenga un fichero Gemfile.

En mi caso he utilizado uno que ya tenia:


![Alt text](https://raw.githubusercontent.com/alu0100595727/sytw_tarea_inicial/master/imagenes/bundler2.png)


Para mas informacion de como crear los ficheros Gemfile les dejo el siguiente enlace: [Aquí](http://bundler.io/gemfile.html)



## Sinatra

Para instalar la gema sinatra simplemente ejecutamos:

`sudo gem install sinatra`

![Alt text](https://raw.githubusercontent.com/alu0100595727/sytw_tarea_inicial/master/imagenes/sinatra.png)

## Twitter

Para instalar la gema twitter ejecutamos:

`sudo gem install twitter`

![Alt text](https://raw.githubusercontent.com/alu0100595727/sytw_tarea_inicial/master/imagenes/twitter.png)

## Problema que puede surgir al instalar las gemas anteriores

Al instalar una gema puede dar el siguiente error:

> Failed to build gem native extension (mkmf (LoadError))

Para solucionar dicho error, podemos probar el siguiente comando:

`sudo apt-get install ruby-dev`



## Git

Git es un controlador de versiones de nuestros directorios de trabajo, el cual se complementa de forma remota con paginas como github o bitbucket

Tengo la version 1.8.3.2 instalada:

![Alt text](https://raw.githubusercontent.com/alu0100595727/sytw_tarea_inicial/master/imagenes/git.png)

En el caso de que no lo tengamos ejecutamos el siguiente comando:

`apt-get install git`

##   

*Jazer Abreu Chinea SYTW 2014-2015*







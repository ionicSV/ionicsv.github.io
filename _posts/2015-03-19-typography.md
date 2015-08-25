---
title: Instalando Ionic y mi primera app.
---
![Test](/img/onico.png "Test")
En este post veremos como instalar ionic y lo sencillo que es, para iniciar debemos vereficar que tengamos
previamente instalado [NodeJs](https://nodejs.org/) para verificar basta con solo teclear en la terminal el comando: 

>node -v

automaticamente la  consola nos dira la version de nodejs que tengamos si en caso no lo tienes puedes instalarlo desde aqui : [NodeJs](https://nodejs.org/).

##Instalemos Ionic
Para instalar ionic lo hacemos con el siguiente comando:

 >$ npm install -g cordova ionic

Y listo tenemos instalado ionic! recuerda que el signo $ solo hace referencia al direcctorio donde estamos no es un comando, manos a la hobra! creemos nuestra primera app:



### Para crear una app lo hacemos con lo siguientes comandos:

>$ ionic start firstApp blank


Este comando nos crea un proyecto raiz de lo que sera nuestra aplicación, es bueno aclarar que de este comando se derivan los siguientes:

>$ ionic start firstApp tabs

Este nos crea una app ya con un diseño predifinido que es en base a tabs como la siguiente imagen:

![Test](/img/tabs.png "Tabs") 



>$ ionic start firstApp sidemenu

Tambien nos crea un diseño predeterminado al inicio de proyecto, con un sidemenu:

![Test](/img/side.jpg "sidemenu")

Vamos a aclarar que  el comando ionic start blank crea un proyecto si un estilo, el cual podemos darle el estilo que nosotros queramos, recapitualando "ionic start" es un comando para iniciar un proyecto si a estos le agregamos "blank" , "tabs" o "sidemenu" seria la forma en como queremos que inicie el proyecto, en este ejemplo usamos "firstApp" que hace referencia al nombre que tendra nuestra app tu puedes cambiarlo por el que mas te guste.



### Agregando plataformas:

Ionic es un framework con el que puedes crear app hibridas que se adapten a diferentes plataformas como: android, Ios y windowsPhone, para agregar una plataforma hacemos lo siguiente:
hace referencia al directorio de nuesto proyecto:

> $ cd firstApp 

 
  plataforma que agregaremos a nuestro proyecto:


> $ ionic platform add android      


Para este ejemplo vemos una aplicacion android, puedes hacerlo para ios y WindowsPhone solo sustituyendo la palabra al final del comando "ionic platform add", es importante saber que para el caso de ios si puedes crear el proyecto mas no compilarlo ya que necesitarias tener xcode de apple, puedes trabajar el proyecto pero para compilar o subir una app al applestore es necesario que tengas una mac o utilize otra alternativa como ionic view (en un siguiente tutorial veremos mas a fondo este tema), para una app en windowsPhone es debes hacerlo en una maquina con sistema operativo windows ya que este sino, te permitira agregar la plataforma si estas en una maquina con GNU/LINUX o MAC.


### Preparando un proyecto:

Cuando hemos programado un poco y hemos hecho cambios en el diseño y queremos ver los resultados de como se ve nuestra app podemos hacerlo de dos formas:

1- podemos hacer un debug  de nuestra app en el navegador web basta con utlizar el comando

> ionic serve

lo que hace es abrir nuestra aplicacion en nuestro navegador, ahi podemos usar la consola del mismo para ver si tenemos algun problema, en fin podemos hacer uso de las herramientas de desarrollo de nuestro navegador para hacer un test a nuestra app.

2- En el caso de queramos probar nuestra app en en un emulador como los que proporciona android con su SDK o en un dispositivo real podemos hacer lo siguiente:

>  $ ionic build android


Este comando nos sirve para compilar y agregar los archivos que hemos modificado en nuestra aplicación a la vez prepara para lo que seria emularla.


>  $ ionic emulate android

De esta forma ya podemos emular nuestra app, en una maquina virtual (proporcionada por SDK de android) o en nuestro dispostivo real


##Aclaraciones:

Debes tomar en cuenta que para que puedas realizar los ejemplos que iremos haciendo en este blog antes debes tener configurado tu entorno de desarrollo con esto nos referimos por ejemplo en el caso de android tener instaldo el SDK o android developers tools para que puedas hacer funcionar cada ejemplo.

###Hasta la proxima:
En la proxima entrada veremos con es la estructura de un proyecto en ionic, haremos uso de angular y rutas para ir generando las vistas de nuestra aplicación,iniciaremos desde lo mas basico pero cada vez iremos avanzando hasta ejemplos mas complejos al igual que no solo nos centraremos en android sino tambien veremos como hacer los mismos ejemplos en ios. saludos!


### Por:

[Eduardo Valencia](http://enriquev.github.io/)











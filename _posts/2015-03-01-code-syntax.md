---
title: Estructura de un App
---
En este tutorial crearemos el clasico "hola mundo", algo de costumbre siempre que vamos a iniciar a programar o conocer un nuevo leguaje pero esto nos servira para orientarnos un poco sobre la estructura de unproyecto en Ionic, asi que vamos! 

Estructura basica de HTML:
{% highlight html linenos %}

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="initial-scale=1, maximum-scale=1, user-scalable=no, width=device-width">
    <link href="http://code.ionicframework.com/1.0.0/css/ionic.min.css" rel="stylesheet">
    <script src="http://code.ionicframework.com/1.0.0/js/ionic.bundle.js"></script>
  </head>
  <body>
	Hello World!
  </body>
</html>

{% endhighlight %}

Hasta esta estapa solo tendriamos una simple web con un "hello word" veamos lo que en si crea la magia para una app en ionic:
{% highlight html linenos %}

<body ng-app="ionicApp">

{% endhighlight %}

Last, a Ruby example:
{% highlight ruby linenos %}

def hello
  puts "Hello World!"
end

{% endhighlight %}

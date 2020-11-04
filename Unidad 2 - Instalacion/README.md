# Instalacion 🎉️

Si tenemos Mac o Linux ya tendremos una version de Python instalada, en cambio en Windows es si o si desde cero.

### ¿Qué version instalo?

Esta la version 2 y 3, no son compatibles entre sí pero pueden coexistir.

#### Version 2

* Es la mas avanzada pero el mas antiguo
* Es la que posee la mayor cantidad de paquetes, todos deben migrarse a 3 en el futuro.
* `print "hola mundo"`
* `4/3 -> 1` Redondea numeros
* `type("hola") -> <type 'str'>` y si deseo unicode `type(u"hola") -> <type 'unicode'>`
* Ingreso de teclado `raw_input("Dame un numero")` si quiero recibir un int en vez de un String `input("Dame un numero")`
* Se podian comparar dos tipos de datos completamente distintos (un array con un numero)

#### Version 3

* Es la mejor para usar si recien empezás
* En **Python 3 Wall of Superpowers** podemos ver que paquetes son compatibles ya con Phyton 3.
* `print("hola mundo")`
* `4/3 -> 1.33333333` y si quiero redondear `4//3 -> 1`
* Todos los strings son unicode por defecto.
* Ingreso de teclado `input("Dame un numero")` si quiero recibir un int en vez de un String `int("Dame un numero")`
* No puedo comparar dos tipos de datos distintos, se da un error.

### Instalar Python en Windows

1. Ir a www.python.org
2. Ir a Downloads y descargar la ultima version (3.9.0)
3. Instalarlo marcando la opcion para agregar Python al PATH.
4. Luego nos deberia aparecer la consola de Python disponible para su uso

### Comandos para testear Python

Sumamos un numero

> 5+3

Imprimimos en consola

> print('Hola')

Declaramos variables

> a = 3
> b= 12
> a+b

Declaramos Strings

> a='Denu'
> print(a)

### Interpretes Python

Hay varios interpretes que se desarrollaron de distintas formas, en distintos lenguajes y con diferentes propositos.

* Anaconda
  Anaconda es de distribución libre y abierta de los lenguajes Python y R, que se utiliza en ciencia de datos, y machine learning. Anaconda se utiliza principalmente para procesamiento de grandes volúmenes de información, análisis predictivo y cómputos científicos.
  
  Las diferentes versiones de los paquetes se administran mediante el sistema de administración del paquete conda, el cual lo hace bastante sencillo de instalar, correr, y actualizar software de ciencia de datos y machine learning tales como Scikit-team, TensorFlow y SciPy.3
  
  La distribución Anaconda es utilizada por 6 millones de usuarios e incluye más de 250 paquetes de ciencia de datos válidos para Windows, Linux y MacOS.
* Pypy
  Es una implementación de Python escrita en el propio lenguaje Python, esto permite realizar ciertas modificaciones sobre el propio lenguaje y da lugar a los desarrolladores a realizar mejoras y cambios sustanciales sobre el lenguaje. Al estar implementado en un lenguaje de alto nivel PyPy es más flexible y permite mayor experimentación que CPython.
  
  PyPy tiene por objeto proporcionar una traducción común y un framework conceptual para la producción de implementaciones de lenguajes dinámicos, haciendo hincapié en una separación limpia entre la especificación del lenguaje y los aspectos de implementación. Intenta además proporcionar una implementación compatible, flexible y rápida del Lenguaje Python utilizando el mencionado framework para desarrollar nuevas características avanzadas sin tener que codificar detalles a bajo nivel
* Python
  Es la implementación oficial y más ampliamente utilizada del lenguaje de programación Python. Cuando instalamos python, estamos también instalando esta implementación del intérprete. Es decir que tanto desde windows como linux y Mac, cuando testeamos desde la consola las diferentes pruebas de código que realizamos hasta el momento, sin saberlo hemos utilizado Cpython
  
  Está escrita en C, como podemos suponer por su nombre.
  
  Además de CPython, hay otras implementaciones con calidad para producción: Jython, escrita en Java; IronPython, escrita para el Common Language Runtime y PyPy, escrita en un subconjunto del propio lenguaje Python.
  


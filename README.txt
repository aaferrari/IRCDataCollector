IRCDataCollector
================
Script para KVirc que permite recolectar y/o analizar cualquier tipo de informacion dentro de un chat mediante expresiones regulares u otras tecnicas que se requieran (de momento solo sirve para encontrar emails mediante expresiones regulares).

Posibles preguntas frecuentes
=============================
¿Por que usar KVirc como marco de desarrollo para este script?
En principio este programa se lo eligio como "anfitrion" para la ejecucion de este script por los siguientes motivos:
1. Es mas sencillo escribir un script que funcione dentro de un programa de IRC antes que armar el script junto con todo lo demas que se necesita para conectar e interactuar con el protocolo IRC (aunque cualquiera que este interesado puede hacerlo si gusta).
2. El caracter multiplataforma de KVirc lo hace idoneo para desarrollar el script y que este pueda funcionar en cualquier sistema con este cliente de IRC instalado.
3. KVS resulta un lenguaje de scripting sencillo de aprender, parecido a otros lenguajes interpretados (como Python, Javascript o PHP), tambien permite llamar codigo Perl o Python (teniendo previamente instalado el interprete de alguno de estos lenguajes), soporta programacion orientada a objetos, contiene clases Qt que se pueden usar para contruir partes adicionales de la GUI y permite llamar funciones de librerias externas mediante EasyPlugin (mas informacion en http://www.kvirc.net/doc/doc_easyplugins.html ).

¿Donde puedo aprender el KVS (KVirc Scripting)?
Documentacion oficial: http://www.kvirc.net/doc/index.html
Algunos script que se pueden revisar: 
http://bots.wmflabs.org/~richs/kvirc/addons/old/
http://kvirc.cluenet.org/kvirc/addons/old/

¿Como ejecuto el script?
Por el momento la unica forma es escribiendo lo siguiente en el prompt de KVirc: /parse ruta/del/script/main.kvs (para Windows seria /parse X:\\ruta\\del\\script\\main.kvs)
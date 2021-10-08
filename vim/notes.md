# Notas clase Vim

## ¿Qué es Vim?
Vim es un editor de texto ligero con una tésis principal:  

> **Las flechitas del teclado son malas. El mouse es peor.**

Por eso, cuando trabajas con Vim, no despegas tus manos del teclado.  

Ésto tiene varias ventajas:

+ Más ergonómico
	- No tienes que mover mucho tu muñeca, causante de malestar/tubo carpiano
+ Más eficiente
+ Más rápido

Aparte, es universal: muchos programas funcionan con keybindings tipo Vim (ej. Blender, Firefox, Atom/Visual Studio con plugins específicos).

## Aprendiendo Vim 

Vamos a repasar Vim con el Vim Tutor.

~~~bash
wget http://www2.geog.ucl.ac.uk/~plewis/teaching/unix/vimtutor
~~~

+ Modo de operar: verbo, adverbio, sustantivo.
+ 3 modos
	- Normal
	- Insertar
	- Visual
	- Comandos

## Configurando Vim - _.vimrc_

### Número

~~~vim
:set number
~~~

### Números relativos
~~~vim
:set relativenumber
~~~
### Números híbridos
~~~vim
:set number relativenumber
~~~
## Vimium
¿Ver en Chrome?


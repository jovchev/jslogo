jslogo - Logo in JavaScript
===========================

Този проект е клониран от https://github.com/inexorabletash/jslogo

Целта е да се преведе възможно най-много на български езика Лого.
This is hosted at http://jovchev.github.io/jslogo/ for playing with live.

[Language Reference](http://htmlpreview.github.com/?https://github.com/inexorabletash/jslogo/blob/master/language.htm) -
this attempts to implement a subset of [UCBLogo](http://www.cs.berkeley.edu/~bh/v2ch14/manual.html)
defined in in *Brian Harvey's Computer Science Logo Style*

Use `git clone --recursive` to get [polyfill](https://github.com/inexorabletash/polyfill) for older browsers.

Примери
-------------
	за звезда повтори 5 [ нп 100 нд 144 ] край
    звезда
    
    за квадрат :размер повтори 4 [ нп :размер нд 90 ] край
    повтори 36 [ квадрат 50 нд 10 ]
    
	За превеждане
	to randomcolor setcolor pick [ red orange yellow green blue violet ] end
    repeat 36 [ randomcolor square random 200 rt 10 ]
    window pu repeat 72 [ setlabelheight repcount fd repcount * 2.5 label "Logo bk repcount * 2.5 rt 10 ]

Logo Links
----------
* [Logo](http://en.wikipedia.org/wiki/Logo_%28programming_language%29) on Wikipedia
* Other Logo implementations that run in a Web browser:
  * [papert - logo in your browser](http://logo.twentygototen.org/) ([source code](https://code.google.com/p/papert/))
  * [Curly Logo](https://github.com/drj11/curlylogo)
* [The Logo Foundation](http://el.media.mit.edu/logo-foundation/)
* [Berkeley Logo (UCBLogo)](http://www.cs.berkeley.edu/~bh/logo.html)
* [The Logo Tree Project](http://elica.net/download/papers/LogoTreeProject.pdf)
* [Ian Bicking on Logo](http://blog.ianbicking.org/2007/10/19/logo/)
* [PyLogo](http://pylogo.sourceforge.net/)
* [Introduction to Computer Programming](http://www.bfoit.org/itp/itp.html)
* [LogoForum](http://groups.yahoo.com/group/LogoForum/)

To Do
-----
* Document deviations from UCB Logo standard
* Make these examples all work: [Logo 15-word challenge](http://www.mathcats.com/gallery/15wordcontest.html)
* Tail-call optimization
* Make execution async so you can watch the turtle move

title: The UNIX philosophy
output: index.html
theme: theme
controls: false

-- title

# The UNIX Philosophy

-- title

# Brought to you by

-- presenter

![Olivier Wietrich](https://avatars3.githubusercontent.com/u/1443806?v=3&s=460)

## Olivier Wietrich

* [<i class="fa fa-github"></i> bredele](https://github.com/bredele)
* [<i class="fa fa-twitter"></i> @bredeleca](http://twitter.com/bredeleca)


--

# Introduction

<br>
<div class="center">The unix philosophy is some kind of early meditation about how to design system with clean interfaces. </div>

-- image

This is your new Bible. Be a hater and say FUCK to:

![polymer](img/polymer-logo.jpg)
![angularjs](img/angularjs-logo.png)

they will drive you into a wall!

--

# Rule of simplicity

<br>
<div class="center">
	Programmers are proud of their ability to handle complexity and juggle abstractions.
</div>
<div class="bold center red">Everybody loses at the end.</div>
<br>
<br>
<br>
<br>
<div class="center">
	Encourage simple and beautiful programs.
</div> 
<div class="green center bold">Stupid is as stupid does.</div>

--

# Examples


```javascript

/**
 * I am an idiot and I don't
 * know JavaScript.
 *
 * @param  {Boolean} idiot
 * @return {Boolean}
 */

function iaman(idiot) {
	if(idiot === true) {
	  return true;
	} else if(idiot === false) {
	  return false;
	}
}


/**
 * I am a JAVA developer and I
 * don't know some JS basics such as
 * truthy or falsy values.
 *
 * @param  {Any} basics
 */

function idonotknow(basics) {
	if(typeof basics !== 'undefined' && basics !== false && basics !== 0) {
	  // I do not know JAVA either
  }
}

```

--

# Rule of clarity

<div class="center">Maintenance is expensive!</div>
<br>
<br>
<br>
<div class="center">
	Code that is graceful and clear is less likely to be break.
</div>


--

# My own rule : be stupid!

<br>
<br>
<br>
* 15 lines of code max / function
* Do not make assumptions


--

# Rule of least surprises
<div class="center">Always do the least surprising</div>
<br>
<br>
<br>
<div class="center">
	The easiest programs are those that demand the least new learning from the user.
</div>

--

# Rule of representation

<div class="center">Fold knowledge into data, so program logic can be stupid and robust</div>
<div class="bold center red">Model should be at the heart of your applications.</div>
<br>
<br>
<br>
<div class="center">
	Choose the right data structures and organizes things well, the code will almost be self-evident.
</div>
<div class="bold center green">[Datastore](http://github.com/bredele/feathers) and [feathers](https://github.com/feathersjs).</div>

--

# MVC sucks

* spaghetti code
* tight coupled views
* no separation of concerns
* complicated models and collections of complicated models


<div class="red bold">I withdraw what I just said, developers suck!</div>

* don't build your application around this pattern only
* flatten your achitecture
* use transitive data

* [brick](http://github.com/bredele/brickjs)
* [wall](https://github.com/bredele/walls)

--

# Rule of composition
<div class="center">To make programs composable, make them independant.</div>
<br>
<br>
<br>
<div class="center">Composable programs are independent programs with well-defined interfaces.</div>
<div class="bold center green">JavaScript is not just about objects</div>
--


# Rule of modularity
<div class="center">Controlling complexity is the essence of computer programming.</div>
<br>
<br>
<br>
<div class="center">
	Write complex software by holding the complexity down.
</div>
<div class="bold center green">Do one thing and do it well.</div>
--


# Other rules


[brick](http://github.com/bredele/brickjs)
--

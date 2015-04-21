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
The unix philosophy is some kind of early meditation about how to design system with clean interfaces. 

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


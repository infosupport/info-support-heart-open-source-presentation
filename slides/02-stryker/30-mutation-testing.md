## Mutation testing

---

### Example

Let's start with an example

* [Code coverage report](http://localhost:4901/coverage/src/index.html) <!-- .element target="report"-->
* [Mutation testing report](http://localhost:4901/mutation/html/index.html) <!-- .element target="report"-->

---

### How it works

![](/img/source-code.jpg)<!--.element class="logo" --><span class="logo-arrow">🡲</span> <!-- .element class="fragment" data-fragment-index="1" --> 
![](/img/mutant.png) <!--.element class="logo fragment" data-fragment-index="1"--><span class="logo-arrow">🡲</span> <!-- .element class="fragment" data-fragment-index="2" -->
![](/img/checkmark.svg) <!--.element class="logo fragment" data-fragment-index="2"-->
![](/img/cross.svg) <!--.element class="logo fragment" data-fragment-index="2"-->
<span class="logo-arrow">🡲</span> <!-- .element class="fragment" data-fragment-index="3" -->
<span class="logo-percentage fragment" data-fragment-index="3">%</span>

1. <!-- .element class="fragment" data-fragment-index="1" --> Mutant
1. <!-- .element class="fragment" data-fragment-index="2" -->Killed / survived
1. <!-- .element class="fragment" data-fragment-index="3" -->Mutation score
# luceroIO.github.io
FEND website optimization project 

Optimizations made to index.html



Optimizations made to views/js/main.js

-replaced querySelector tags by getElementById or getElementsByClassName.
now returns a live Nodelist instead of a static Nodelist ,  more detail 
on this around line 408.

- fixed function determineDX,  var dx and return dx was in another function ,
I placed these lines of code in the function their variables was referencing.

-didn't need functions determineDX and sizeSwitcher after recreating  the function
ChangePizzaSizes , layout now doesn't get calculated at every step of the loop, more detail 
on this around line 448. 

-moved PizzaDiv out of the loop, more detail on this around line 530. 

-modified updatePositons function moved part of calculation outside of loop and
created an array for phase , no need for it to be created each time . more detail 
on this around line 567.

-background pizza could be reduced without losing effect but you gained speed , 
more detail on this around line 609
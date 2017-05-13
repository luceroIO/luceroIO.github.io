# luceroIO.github.io
FEND website optimization project 


Optimizations made to views/js/main.js

-replaced querySelector tags by getElementById or getElementsByClassName.
now returns a live Nodelist instead of a static Nodelist , alittle bit more detail 
on this around line 408.

- fixed function determineDX,  var dx and return dx was in another function ,
I placed these lines of code in the function their variables was referencing.
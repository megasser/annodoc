---
layout: entry
title: obj:poss
---

<h2><code>obj:poss</code>: possessor object</h2>

The usual verb of possession in the two languages consists of the existential verb, አለ/አሎ,
with a subject suffix that agrees with the theme (the possessed thing) and an obligatory object suffix that agrees with the possessor.
In such cases we annotate the possessor argument, which usually has no case marker, with `obj:poss`.

am-ref-7: አስቴር መኪና አላት ።  'Aster has a car.'

~~~ sdparse
አስቴር መኪና አላት ፡፡ \n Aster car it(he)-exists-her .
nsubj(አላት, መኪና)
obj:poss(አላት, አስቴር)
~~~

ti-ref-7a: ኣስቴር መኪና ኣላታ ።  'Aster has a car.'

~~~ sdparse
ኣስቴር መኪና ኣላታ ። \n Aster car it(she)-exists-her .
nsubj(ኣላታ, መኪና)
obj:poss(ኣላታ, ኣስቴር)
~~~

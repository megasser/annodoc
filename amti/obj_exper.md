---
layout: entry
title: obj:exper
---

<h2><code>obj:exper</code>object of experience verb</h2>

Experience verbs in both languages are characterized by a number of different syntactic frames.
For one of these, the experiencer argument agrees with the verb's obligatory object suffix and usually
appears with no case marker, even when it is definite. We annotate the experiencer argument for such verbs with `obj:exper`.

am-ref-46: አስቴር ደከማት ። 'Aster is tired.'

~~~ sdparse
አስቴር ደከማት ። \n Aster it-tired-her .
obj:exper(ደከማት, አስቴር)
~~~

ti-ref-46b: ኣስቴር ደኺሙዋ ። 'Aster is tired.'

~~~ sdparse
ኣስቴር ደኺሙዋ ። \n Aster it-tired-her .
obj:exper(ደኺሙዋ, ኣስቴር)
~~~

Less frequently, the experiencer takes the usual object case marker.

am-S-763: አልማዝን አመማት ። 'Almaz is sick.'

~~~ sdparse
አልማዝን አመማት ። \n Almaz-OBJ it-sickened-her .
obj:exper(አመማት, አልማዝን)
~~~

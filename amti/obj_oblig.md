---
layout: entry
title: obj:oblig
---

<h2><code>obj:oblig</code>: obligation object</h2>

The existential verb, አለ/አሎ, with an applicative suffix may express obligation.
The obliged argument, which usually has not case marker, is co-referential with the verb's applicative suffix.
We annotate it with `obj:oblig`.

In Amharic the subject of the verb is normally an infinitive.

am: አስቴር መሄድ አለባት ። 'Aster has to go.'

~~~ sdparse
አስቴር መሄድ አለባት ። \n Aster going exists-on-her .
csubj(አለባት, መሄድ)
obl:oblig(አለባት, አስቴር)
~~~

In Tigrinya the obliged act more often takes the form of a finite subordinate verb with the conjunctive prefix ክ-.

ti: ኣስቴር ክትኸይድ ኣለዋ ። 'Aster has to go.'

~~~ sdparse
ኣስቴር ክትኸይድ ኣለዋ ። \n Aster that-she-goes exist-on-her .
advcl(ኣለዋ, ክትኸይድ)
obl:oblig(ኣለዋ, ኣስቴር)
~~~


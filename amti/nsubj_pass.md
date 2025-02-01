---
layout: entry
title: nsubj:pass
---

<h2> <code>nsubj:pass</code>: passive nominal subjects</h2>

We use the subrelation `:pass` with `nsubj` when the nominal is the subject of a passivized clause, that is, a clause that is related by passivization to a corresponding active clause.

- am-ref-15: ብርጭቆው ተሰበረ ። (passivized form of ብርጭቆውን ሰበረ ።)

~~~ sdparse
ብርጭቆው ተሰበረ ። \n glass was-broken .
nsubj:pass(ተሰበረ, ብርጭቆው)
~~~

- ti-ref-15: እቲ ቢኬሪ ተሰቢሩ ። (passivized form of ነቲ ቢኬሪ ሰቢሩ ።)

~~~ sdparse
እቲ ቢኬሪ ተሰቢሩ ። 
\n the glas was-broken .
nsubj:pass(ተሰቢሩ, ቢኬሪ)
~~~

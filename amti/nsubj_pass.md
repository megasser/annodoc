---
layout: entry
title: nsubj:pass
---

<h2> <code>nsubj:pass</code>: passive nominal subjects</h2>

We use the subrelation `:pass` with `nsubj` when the nominal is the subject of a passivized clause, that is, a clause that is related by passivization to a corresponding active clause.

- am-ref-15: ብርጭቆው ተሰበረ ። (passivized form of ብርጭቆውን ሰበረ ።) 'The glass was broken.'

~~~ sdparse
ብርጭቆው ተሰበረ ። \n glass was-broken .
nsubj:pass(ተሰበረ, ብርጭቆው)
~~~

- ti-ref-15: እቲ ቢኬሪ ተሰቢሩ ። (passivized form of ነቲ ቢኬሪ ሰቢሩ ።) 'The glass was broken.'

~~~ sdparse
እቲ ቢኬሪ ተሰቢሩ ። \n the glass was-broken .
nsubj:pass(ተሰቢሩ, ቢኬሪ)
~~~

A clause may have a head verb with passive-reflexive morphology and not be treated as passive if it cannot be viewed as the passivized form of a corresponding active clause. In both 3 and 4, the verbs are formally passive-reflexive, but the clauses are not treated as passive, so the subject takes the simple `nsubj` relation.

~~~ sdparse
አልማዝ ተደሰተች ። \n Almaz is-happy .
nsubj(ተደሰተች, አልማዝ)
~~~

~~~ sdparse
ኣልማዝ ተሓጒሳ ። \n Almaz is-happy .
nsubj(ተሓጒሳ, ኣልማዝ)
~~~

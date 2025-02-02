---
layout: entry
title: nsubj:aff
---

<h2><code>nsubj:aff</code>: nominal subject morphology</h2>

The subrelation `:aff` is used for subject agreement prefixes and suffixes within verbs. Note that a single verb stem may have two `nsubj:aff` daughters because some verbs have both prefix and suffix subject agreement markers.

- am-ref-4: ውሻው ይ-ጮህ-ኣል ።

~~~ sdparse
ውሻው ይ- -ጮህ- -ኣል ። \n the-dog 3SM- -bark- -AUX .
nsubj:aff(-ጮህ-, ይ-)
~~~

- ti-ref-4: ከልቢ ይ-ነብሕ ።

~~~ sdparse
ከልቢ ይ- -ነብሕ ። \n dog 3SM- -bark .
nsubj:aff(-ነብሕ, ይ-)
~~~

- am-ref-2: አልጋው ላይ ተኛ-አች ።

~~~ sdparse
አልጋው ላይ ተኛ- -አች ። \n the-bed on sleep- -3SF .
nsubj:aff(ተኛ-, -አች)
~~~

- ti-ref-2: ኣብ ዓራት ደቂስ-ኣ ።

~~~ sdparse
ኣብ ዓራት ደቂስ- -ኣ ። \n on bed sleep- -3SF .
nsubj:aff(ደቂስ-, -ኣ)
~~~

We consider possessive suffixes on infinitives, though they are co-referential with the "subject" of the infinitive, to be `det` rather than `nsubj`.

- am-S-135: መሄድ-ዋ የባሏን ልብ ሰበረው ።

~~~ sdparse
መሄድ- -ዋ የባሏን ልብ ሰበረው ። \n going- -her her-husband's-OBJ heart it-broke-it .
det:aff(መሄድ-, -ዋ)
~~~

- ti-S-135: ምኻድ-ኣ ንልቢ ሰብኣያ ሰቢሩዎ ።

~~~ sdparse
ምኻድ- -ኣ ንልቢ ሰብኣያ ሰቢሩዎ ። \n going- -her heart-OBJ husband it-broke-it .
det:aff(ምኻድ-, -ኣ)
~~~

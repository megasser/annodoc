---
layout: entry
title: nsubj
---

<h2><code>nsubj</code>: nominal subject</h2>

We use `nsubj` for the nominal subject of a finite verb. The subject is always the argument that agrees with (is co-referential with) the morphological subject of the verb, though this may not correspond to the subject in other languages (5, 6). A clause can have at most one `nsubj`.

- am-ref-4: ውሻው ይጮሃል

~~~ sdparse
ውሻው ይጮሃል \n the-dog barks
nsubj(ይጮሃል, ውሻው)
~~~

- ti-ref-4: ከልቢ ይነብሕ

~~~ sdparse
ከልቢ ይነብሕ \n dog barks
nsubj(ይነብሕ, ከልቢ)
~~~

- am-ref-3: እንጀራ የለም ።

~~~ sdparse
እንጀራ የለም \n injera there-is-not
nsubj(የለም, እንጀራ)
~~~

- ti-ref-3: ​​እንጀራ የለን ።

~~~ sdparse
እንጀራ የለን \n injera there-is-not
nsubj(የለን, እንጀራ)
~~~

- am-ref-7: አስቴር መኪና አላት ።

~~~ sdparse
አስቴር መኪና አላት \n Aster car has(exists-to-her)
nsubj(አላት, መኪና)
~~~

- ti-ref-7a: ኣስቴር መኪና ኣላታ ።

~~~ sdparse
ኣስቴር መኪና ኣላታ \n Aster car has(exists-to-her)
nsubj(ኣላታ, መኪና)
~~~

- am-S-50: ወንድሜ ከአገር ቤት ስለመጣ ላየው ሄድኩ ።

~~~ sdparse
ወንድሜ ከአገር ቤት ስለመጣ ላየው ሄድኩ \n my-brother from-country house because-he-came to-see-him I-went
nsubj(ስለመጣ, ወንድሜ)
~~~

- ti-S-50: ሓወይ ካብ ዓዲ ስለዝመጸ ፡ ክርእዮ ከይደ ።

~~~ sdparse
ሓወይ ካብ ዓዲ ስለዝመጸ ፡ ክርእዮ ከይደ \n  \n my-brother from country because-he-came , to-see-him I-went
nsubj(ስለዝመጸ, ሓወይ)
~~~

We also use `nsubj` for the subject of an infinitive if it is does not have the nominal genitive clitic, የ-/ናይ. The subject of the infinitive is the argument that would be the subject of the verb if it were finite. When the "subject" of the infinitive is marked with the nominal genitive clitic, we use `nmod` rather than `nsubj`.

- am-S-67: ካሳ አስቴር ወደ ጎንደር መሄድዋን ሰምቶአል ። (አስቴር ወደ ጎንደር ሄደች)
~~~ sdparse
ካሳ አስቴር ወደ ጎንደር መሄድዋን ሰምቶአል \n Kassa Aster to Gondar her-going he-has-heard
nsubj(መሄድዋን, አስቴር)
~~~

- am-S-442: ልጃቸው በጦርነት ላይ መሞቱን ተረዱ ። (ልጃቸው በጦርነት ላይ ሞተ)
~~~ sdparse
ልጃቸው በጦርነት ላይ መሞቱን ተረዱ \n their-child in-war in his-dying-OBJ they-learned
nsubj(መሞቱን, ልጃቸው)
~~~

In nonverbal (copula) clauses, where the root is not a verb, we use `nsubj` for the subject of the copula, though its governor is the root of the clause, not the copula.

- am-ref-20: ካሳ አስተማሪ ነው ።
~~~ sdparse
ካሳ አስተማሪ ነው \n Kassa teacher is
nsubj(አስተማሪ, ካሳ)
~~~

- ti-ref-20: ካሕሳይ መምህር እዩ ።
~~~ sdparse
ካሕሳይ መምህር እዩ \n Kahsay teacher is
nsubj(መምህር, ካሕሳይ)
~~~

Following the UD guidelines, we do not use `nsubj` for clausal subjects, including infinitives and headless relative clauses (relative clauses with no head noun), instead using `csubj`.


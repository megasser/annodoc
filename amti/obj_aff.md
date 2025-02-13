---
layout: entry
title: obj:aff
---

<h2><code>obj:aff</code>, <code>obl:aff</code>, <code>obj1:aff</code>, <code>obj2:aff</code>: object morphology</h2>

The subrelation :aff is used for object suffixes within finite verbs.

Amharic has three possible object suffixes, a "plain" one, often cross-referencing the obj argument, and two prepositional ones, often cross-referencing obl arguments. We call these obj:aff and obl:aff respectively.

Tigrinya has two possible object suffixes, one cross-referencing a more central, the other a less central participant. Following terminology used by Kifle (2011), we refer to these as obj1:aff and obj2:aff respectively.

- am-S-23: ወንድሜን ያውቀዋል ። 'He knows my brother.'

~~~ sdparse
ወንድሜን ይ- -ኣውቅ- -አው- -ኣል ። \n my-brother-OBJ 3SM know 3SM.OBJ AUX .
nsubj:aff(-ኣውቅ-, ይ-)
obj:aff(-ኣውቅ-, -አው-)
~~~

- ti-S-23: ንሓወይ ይፈልጦ እዩ ። 'He knows my brother.'

~~~ sdparse
ንሓወይ ይ- -ፈልጥ- -ኦ እዩ ። \n my-brother-OBJ 3SM know 3SM.OBJ AUX .
nsubj:aff(-ፈልጥ-, ይ-)
obj1:aff(-ፈልጥ-, -ኦ)
~~~

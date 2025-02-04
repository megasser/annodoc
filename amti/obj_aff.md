---
layout: entry
title: obj:aff
---

<h2><code>obj:aff</code>: object morphology</h2>

The subrelation :aff is used for the plain object suffixes within finite verbs. Note that these do not necessarily agree with a syntactic obj argument.

- am-S-23: ወንድሜን ያቀዋል ። 'He knows my brother.'

~~~ sdparse
ወንድሜን ይ- -ኣውቅ- -አው- -ኣል ። \n my-brother-OBJ 3SM know 3SM.OBJ AUX .
nsubj:aff(-ኣውቅ-, ይ)
obj:aff(-ኣውቅ-, -አው)
~~~

- ti-S-23: ንሓወይ ይፈልጦ እዩ ። 'He knows my brother.'

~~~ sdparse
ንሓወይ ይ- -ፈልጥ- -ኦ እዩ ። \n my-brother-OBJ 3SM know 3SM.OBJ AUX .
nsubj:aff(-ፈልጥ-, ይ-)
obj:aff(-ፈልጥ-, -ኦ)
~~~

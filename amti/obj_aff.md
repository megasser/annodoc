---
layout: entry
title: obj:aff
---

<h2><code>obj:aff</code>, <code>obl:aff</code>, <code>obj1:aff</code>, <code>obj2:aff</code>: object morphology</h2>

The subrelation :aff is used for object suffixes within finite verbs.

Amharic has three possible object suffixes, a "plain" one, often cross-referencing the `obj` argument, and two prepositional ones, often cross-referencing `obl` arguments. We call these `obj:aff` and `obl:aff` respectively.

Tigrinya has two possible object suffixes, one cross-referencing a more central, the other a less central participant. Following terminology used by Kifle (2011), we refer to these as `obj1:aff` and `obj2:aff` respectively.

- am-S-23: ወንድሜን ያውቀዋል ። 'He knows my brother.'

~~~ sdparse
ወንድሜን ይ- -ኣውቅ- -አው- -ኣል ። \n my-brother-OBJ 3SM know.IPFV 3SM.OBJ AUX .
nsubj:aff(-ኣውቅ-, ይ-)
obj:aff(-ኣውቅ-, -አው-)
~~~

- ti-S-23: ንሓወይ ይፈልጦ እዩ ። 'He knows my brother.'

~~~ sdparse
ንሓወይ ይ- -ፈልጥ- -ኦ እዩ ። \n my-brother-OBJ 3SM know.IPFV 3SM.OBJ1 AUX .
nsubj:aff(-ፈልጥ-, ይ-)
obj1:aff(-ፈልጥ-, -ኦ)
~~~

- am-S-79: ገንዘብ ይስጠኝ እንጂ የፈለገውን እገዛለታለሁ ።

~~~ sdparse
ገንዘብ ይ- -ስጥ- -አኝ እንጂ የፈለገውን እ- -ገዛ- -ለት- -ኣለሁ ። \n money 3SM give.JUS 1S.OBJ though what-he-wanted 1S buy.IPFV 3SM.OBL AUX .
nsubj:aff(-ስጥ-, ይ-)
nsubj:aff(-ገዛ-, እ-)
obj:aff(-ስጥ-, -አኝ)
obl:aff(-ገዛ-, -ለት)
~~~

- ti-S-79: ገንዘብ ደኣ ይሃበኒ እምበር ፡ ዝደለዮ ክገዝኣሉ እየ ። 'Let him give me money; I'll still buy him what he wants.

~~~ sdparse
ገንዘብ ደኣ ይ- -ሃብ- -አኒ እምበር ፡ ዝደለዮ ክ- እ- -ገዝኣ- -ሉ እየ ። \n money FOCUS 3SM give.JUS 1S.OBJ1 though , what-he-wanted that 1S buy.IPFV 3SM.OBJ2 AUX .
nsubj:aff(-ሃብ-, ይ-)
nsubj:aff(-ገዝኣ-, እ-)
obj1:aff(-ሃብ-, -አኒ)
obj2:aff(-ገዝኣ-, -ሉ)
~~~

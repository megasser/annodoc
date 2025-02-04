---
layout: entry
title: obj
---

<h2><code>obj</code>: object</h2>

We assume a basic distinction in both languages between intransitive verbs, such as ሄደ/ከደ, and transitive verbs, such as ሰበረ.
Intransitive verbs have no obj argument; transitive verbs have at most one obj.
An `obj` argument is often co-referential with the object suffix on the verb and,
if it is definite or generic, is marked with the suffix -ን in Amharic and the prefix ን- in Tigrinya
(though this suffix is not obligatory in Tigrinya).
However, when an `obj` noun has modifiers, the case affix normally appears on one of these instead of on the head noun.
In the examples below, we indicate the object suffix with "OBJ".

am-S-125: ልጁ ኳሱን መታው ። 'The boy hit the ball.'

~~~ sdparse
ልጁ ኳሱን መታው ። \n the-boy the-ball-OBJ he-hit-it .
obj(መታው, ኳሱን)
~~~

ti-S-125: እቲ ወዲ ነታ ኵዕሶ ቀሊዑዋ ። 'The boy hit the ball.'

~~~ sdparse
እቲ ወዲ ነታ ኵዕሶ ቀሊዑዋ ። \n  the boy the-OBJ ball he-hit-it .
obj(ቀሊዑዋ, ኵዕሶ)
~~~

am-ref-59: ከኋላ የተሰለፈውን ልጅ ጥራው ። 'Call the boy who is standing in the back.'

~~~ sdparse
ከኋላ የተሰለፈውን ልጅ ጥራው ። \n behind who-stands-DEF-OBJ boy call-him .
obj(ጥራው, ልጅ)
~~~

ti-ref-59: ነቲ ብድሕሪት ተሰሪዑ ዘሎ ወዲ ጸውዓዮ ። 'Call the boy who is standing in the back.'

~~~ sdparse
ነቲ ብድሕሪት ተሰሪዑ ዘሎ ወዲ ጸውዓዮ ። \n the-OBJ behind who-stands AUX boy call-him .
obj(ጸውዓዮ, ወዲ)
~~~

In both languages the case suffix associated with `obj` arguments may also appear on arguments that do not represent core objects.
In the following examples, the case-marked argument, 'the glass', is co-referential with an applicative suffix on the verb and
represents an `obl` argument, while the `obj`, 'milk', has no case marking or corresponding agreement affix on the verb.

am-ref-398: ብርጭቆውን ወተት ጠጣበት ። 'He drank milk from the glass.'

~~~ sdparse
ብርጭቆውን ወተት ጠጣበት ። \n the-glass-OBJ milk he-drank-APP.it .
obj(ጠጣበት, ወተት)
obl(ጠጣበት, ብርጭቆውን)
~~~

ti-ref-398: ነቲ ቢኬሪ ጸባ ሰትዩሉ ። 'He drank milk from the glass.'

~~~ sdparse
ነቲ ቢኬሪ ጸባ ሰትዩሉ ። \n the-OBJ glass milk he-drank-APP.it .
obj(ሰትዩሉ, ጸባ)
obl(ሰትዩሉ, ቢኬሪ)
~~~

Infinitives may also take arguments that behave like the objects of finite verbs, including, where expected, the object case affixes.

am-S-4: ውድድሩን ማሸነፉ አስደሰተው ። 'Winning the competition made him happy.'

~~~ sdparse
ውድድሩን ማሸነፉ አስደሰተው ። \n competition-the-OBJ his-winning it-made-him-happy .
obj(ማሸነፉ, ውድድሩን)
~~~

ti-S-4: ነቲ ውድድር ምዕዋቱ ኣሕጒሱዎ ። 'Winning the competition made him happy.'

~~~ sdparse
ነቲ ውድድር ምዕዋቱ ኣሕጒሱዎ ። \n the-OBJ competition his-winning it-make-him-happy
obj(ምዕዋቱ, ውድድር)
~~~

Three categories of verbs in the languages are characterized by a participant that is co-referential with the object or
applicative suffix on the verb but normally appears without a case suffix.
We consider these to be obj arguments, annotating them with the subrelations `:exper`, `:poss`, and `:oblig`.

In line with treebanks for the corresponding verbs in other languages, we use `xcomp` rather than `obj` for the complements of verbs
such as ሆነ/ኮነ (when it means 'become') and መሰለ 'seem'.

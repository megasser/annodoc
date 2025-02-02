---
layout: entry
title: nsubj:outer
---

<h2><code>nsubj:outer</code>: outer clause nominal subject</h2>

As in other UD treebanks, we use `nsubj:outer` for the nominal subject of a copular clause whose predicate is itself a clause,
to signal that it is not the subject of the nested clause.

- am-ref-93: ችግሩ አበበ የሌላ ሰውን ሃሳብ በጭራሽ አለመስማቱ ነው ። 'The problem is that Abebe doesn't listen at all to other people's ideas.'

~~~ sdparse
ችግሩ አበበ የሌላ ሰውን ሃሳብ በጭራሽ አለመስማቱ ነው ። \n the-problem Abebe of-other person-OBJ idea completely his-not-hearing is .
cop(አለመስማቱ, ነው)
nsubj(አለመስማቱ, አበበ)
nsubj:outer(አለመስማቱ, ችግሩ)
~~~

- ti-ref-93: እቲ ጸገም ኣበበ ናይ ካልእ ሰብ ሓሳብ ብፍጹም ዘይምስምዑ እዩ ። 'The problem is that Abebe doesn't listen at all to other people's ideas.'

~~~ sdparse
እቲ ጸገም ኣበበ ናይ ካልእ ሰብ ሓሳብ ብፍጹም ዘይምስምዑ እዩ ። \n the problem Abebe of other person idea completely his-not-hearing is .
cop(ዘይምስምዑ, እዩ)
nsubj(ዘይምስምዑ, አበበ)
nsubj:outer(ዘይምስምዑ, ጸገም)
~~~

The clausal relation corresponding to `nsubj:outer` is `csubj:outer`. In fact a sentence may contain two levels of nesting, with both types of outer complements.

- am-ref-103: ያስተዋልኩት ፣ ችግሩ አስቴር ልጇን መደበቋ እንደሆነ ነው ። 'What I realized is that the problem is that Aster hid her child.'

~~~ sdparse
ያስተዋልኩት ፣ ችግሩ አስቴር ልጇን መደበቋ እንደሆነ ነው ። \n what-I-realized , the-problem Aster her-son-OBJ her-hiding that-it-is is .
cop(መደበቋ, ነው)
cop(መደበቋ, እንደሆነ)
csubj:outer(መደበቋ, ያስተዋልኩት)
nsubj:outer(መደበቋ, ችግሩ)
nsubj(መደበቋ, አስቴር)b
~~~

- ti-ref-103: ዘስተውዓልኩዎ ፣ ጸገም ኣስቴር ውላዳ ምሕብኣ ምዃኑ እዩ ። 'What I realized is that the problem is that Aster hid her child.'

~~~ sdparse
ዘስተውዓልኩዎ ፣ ጸገም ኣስቴር ውላዳ ምሕብኣ ምዃኑ እዩ ። \n what-I-realized , problem Aster her-child her-hiding its-being is .
cop(ምሕብኣ, እዩ)
cop(ምሕብኣ, ምዃኑ)
csubj:outer(ምሕብኣ, ዘስተውዓልኩዎ)
nsubj:outer(ምሕብኣ, ጸገም)
nsubj(ምሕብኣ, ኣስቴር)
~~~

---
layout: entry
title: nsubj:outer
---

<h2><code>nsubj:outer</code>: outer clause nominal subject</h2>

As in other UD treebanks, we use `nsubj:outer` for the nominal subject of a copular clause whose predicate is itself a clause,
to signal that it is not the subject of the nested clause.

- am-ref-93: ችግሩ አበበ የሌላ ሰውን ሃሳብ በጭራሽ አለመስማቱ ነው ። 'The problem is that Abebe doesn't listen at all to other people's ideas.'

~~~ sdparse
ችግሩ አበበ የሌላ ሰውን ሃሳብ በጭራሽ አለመስማቱ ነው ። \n the-problem Abebe of-other person-OBJ idea completely not-listening-his is .
cop(አለመስማቱ, ነው)
nsubj(አለመስማቱ, አበበ)
nsubj:outer(አለመስማቱ, ችግሩ)
~~~

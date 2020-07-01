# References

A place to dump useful links, paper refs etc.

* (Yan: Following a post about polytomies to R-sig-phylo, I was sent this email from Martin Smith at Durham):

	> Regarding the enumeration of tree topologies, John Tromp proposed a method
for representing binary trees as a mixed-base number, used in Li et al.
(1996, "Some notes on the nearest neighbour interchange distance"), which
underpins the 'TreeTools' function `as.TreeNumber()`. Applying this
approach to trees with > 42 leaves is complicated by the need for >64 bit
integers to represent all possible topologies.
	>
	> [https://ms609.github.io/TreeTools/reference/TreeNumber.html](https://ms609.github.io/TreeTools/reference/TreeNumber.html)
The 'TreeTools' function `RootedTreeShape()` is the equivalent for
unlabelled trees:

	> [https://ms609.github.io/TreeTools/reference/TreeShape.html
](https://ms609.github.io/TreeTools/reference/TreeNumber.html) I'd be interested to hear if you come across an effective way to enumerate
unrooted tree shapes, which is a less straightforward affair...

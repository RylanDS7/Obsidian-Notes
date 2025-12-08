A set $K$ in a [[Hausdorff Topological Spaces]] is compact if for every collection of open sets $\mathcal{G}$ such that
$$
K \subseteq \bigcup \mathcal{G},
$$
there exists $N \in \mathbb{N}$ and sets $G_1, \dots, G_N$ in $\mathcal{G}$ such that
$$
K \subseteq G_1 \cup\dots \cup G_N.
$$
That is to say, "for every open cover of $K$, there exists a finite subcover."

We know that every compact set in an HTS must be closed, and additionally, every compact set in a [[Metric Spaces]] must be bounded which gives rise to the [[Heine-Borel Theorem]]. There is also a sequential characterization for compact sets in metric spaces that says the following are equivalent:

(a) $K$ is a compact set.

(b) Every sequence $(x_n)$ in $K$ has convergent subsequence, whose limit lies in $K$.


There is a complementary perspective on this involving [[Closed Sets]] which utilizes the [[Finite Intersection Property]] and says the following are equivalent for closed $K$:

(a) $K$ is a compact set.

(b) Every collection of closed subsets of K with the finite intersection property has nonempty intersection.

This essentially says that compactness extends the finite intersection to the entire infinite collection.
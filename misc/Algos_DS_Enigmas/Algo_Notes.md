Quicksort: stable, constant space usage, worst case O(n^2) if pivot is smallest/largest element, not good if data on disk
Merge sort : stable, O(n) space on arrays / constant space on linked lists, worst case O(n*log(n)), ok if data on disk
TimSort: used by Python, mix of merge sort & insertion sort, perform well on real-word data
Radix / Counting sort: the best for ints
-> Algorithmic complexity attack, e.g. McIlroy sort killer, which build an input to make any sorting quadratic in time

Trie / directed acyclic graph can be + efficient than binary search trees / hash tables

Test set membership:
- Bloom filters : http://crystal.uta.edu/~mcguigan/cse6350/papers/Bloom.pdf - http://corte.si/%2Fposts/code/bloom-filter-rules-of-thumb/index.html - Invertible: http://arxiv.org/pdf/1101.2245v2.pdf (cf. Python implementations)
- Use prime numbers to represent set elements : http://www.stdlib.net/~colmmacc/2010/09/02/prime-and-proper/
- with time decay: [Flower Filter](http://eng.kifi.com/flower-filter-an-update/)

Hashing:
- 'fuzzy' hashing that gaves same result for inputs that have homologies : http://www.forensicswiki.org/wiki/Context_Triggered_Piecewise_Hashing

Compression:
- Google Snappy (10x faster, 50% worse compression than LZ)
- Google Zöpfli (5% more compression, 100x slower than LZ)

PID controller: control loop feedback mechanism, using the proportional, integral and derivative values,
    that attempts to minimize the error in outputs by adjusting the process control inputs.

Minimum spanning tree for a connected weighted graph ("arbre recouvrant de poids minimum") : Algorithme de Kruskal

HMAC > a hash with a salt, in term of security

VCDIFF : format & algorithm for delta encoding

Fisher-Yates shuffle : O(n) complexity, guaranteed uniformity, optimal asymptotic time & space complexity

[Exponential Backoff algorithm](http://en.wikipedia.org/wiki/Exponential_backoff#Binary_exponential_backoff_.2F_truncated_exponential_backoff)
## Project: sorting strings

It is required to conduct an experimental investigation on the behavior of different
sorting algorithms. 
In particular, it asks to compare at least three different sorting algorithms of which
at least one chosen from InsertionSort, SelectionSort and BubbleSort and at least one
chosen from QuickSort, HeapSort and MergeSort. 
It asks to sort arrays of strings of increasing size (arrays, not strings!). 
It asks to study the performance of the algorithms as the input size varies. 
The results of the experimentation must be presented both in tabular form and by means of
graphs having on the abscissas the dimension of the arrays and on the ordinates the times of
execution.

The strings are taken from the .txt files.

We have chosen these sorting algorithms: BubbleSort, InsertionSort, HeapSort and QuickSort. 
By definition we know that BubbleSort and InsertionSort sort n elements in loco in time T(n) = Θ(n^2),
Heapsort has time cost O(nlogn) and QuickSort, randomly choosing the pivot ad
each call, sorts n elements in time T(n) = O(nlogn). 
We have decided to apply these algorithms on the scripts of some of the most famous film sagas: Jurassic Park (I, II, III); Indiana Jones
(The Last Crusade, The Cursed Temple and Raiders of the Lost Ark); Star Wars (IV, V, VI).
After defining the various functions, we have established a range of sizes for the array
(number of words to order) and with it we have created charts and tables for each saga and algorithm taken into account

The result obtained on the maximum number of words (75000) perfectly reflects the definitions given
previously: highlighting in particular the BubbleSort as the least efficient algorithm, followed by
the InsertionSort, the HeapSort and finally the QuickSort. 
In this case we did not notice any differences between the times execution on the various scripts. 
The analysis on the 50 and 200 words of the Jurassic Park and Indiana Jones sagas
are identical: the order of efficiency of the algorithms remains unchanged with respect to the analysis
taking into account the maximum number of words. A tiny difference can be seen
choosing to analyze time for the first 10 words; looking back at the time of the Jurassic Park saga,
the least efficient algorithm is Heapsort, followed by BubbleSort, InsertionSort and QuickSort; the 
ranking of the algorithms trends of the Indiana Jones saga varies only by the resulting InsertionSort
slightly more efficient than QuickSort. As for the analysis of the scripts of the Star Wars saga,
there is no difference between the trend up to 200 and up to 75000 words, it remains unchanged; while
out of 50 words, HeapSort is the least efficient, followed by BubbleSort, QuickSort and InsertionSort. In
conclusion we have shown that, on a small number of words there are differences, even if 
minimal, among the algorithms; while on the large dimensions the trend remains unchanged even depending on
the saga, confirming the definitions presented at the beginning and foreseen by the theory.

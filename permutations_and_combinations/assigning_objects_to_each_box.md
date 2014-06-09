## Assigning Objects to each Box

> **Goal:** We are trying to assign \\(n\\) objects to every one of the \\(n\\) numbered boxes. Assume that all objects are distinguishable from each other.

We take the first box, and we try to find an object for it. There are \\(n\\) choices for this object, and we pick one, leaving \\(n-1\\) objects left unchosen.

We take the second box, and we assign an object for it. There are \\(n-1\\) choices, and we leave \\(n-2\\) boxes left.

You can see that this is going the same way as the other methods!

We continue this until we reach the last box, where there is only one object left unchosen.

All number of possible choices are unaffected by the previous choice, so we can multiply each of them at every step to get the total number of arrangements equal to
\\[n \\times (n-1) \\times (n-2) \\times \\dotsb \\times 3 \\times 2 \\times 1.\\]

## Take one, pass it along...

> **Goal:** We are trying to place \\(n\\) objects onto a table, and we take note of the order the objects are in. Assume that all objects are distinguishable from each other.

We can start with one object. We put it on a table.

Now, we get another object. We put this on also on the table, next to the first object. We have two choices: we either put it to the left or to the right.

We then get our third object. We try to put this somewhere along the line of two objects. We have three choices: left end, right end, or in between.

We continue, and for the \\(k\\)th object we have \\(k\\) choices: the \\(k\\) spaces to put the \\(k\\)th object.

We continue this until the end, the \\(n\\)th object, which will ultimately have \\(n\\) choices at which to fit the object in.

We know that the number of choices we have at each object placing will be the same no matter what the previous choice was. Therefore we know that the number of possible outcomes at each step will be independent of the previous outcome (outcome as in the choice of the object's location).

We can now see that for every possible placement of the second object, there are 3 choices for the third object, and for every possible arrangement of the first \\(k\\) objects, there are \\(k+1\\) choices for the \\((k+1)\\)th object.

Therefore, the number of possible arrangements is equal to the product of each number of possible choices at each step, which gives us
\\[1 \\times 2 \\times 3 \\times \dotsb \\times n,\\]
which is the sum of all numbers from one to \\(n\\). This is the number of possible arrangements of \\(n\\) distinct objects.

## Putting Objects into Boxes

> **Goal:** We are trying to fit \\(n\\) objects into \\(n\\) boxes and we take note of the order the objects are in. Assume that all objects are distinguishable from each other.

At the start, there are \\(n\\) objects waiting to be placed, and there are \\(n\\) boxes waiting for objects to be placed inside. Each box can only hold one object.

We take one object, and we choose one box for it. There are \\(n\\) boxes to choose from. We put the object in, and now \\(n-1\\) objects are left to be placed in the remaining \\(n-1\\) boxes.

We take a second object, and we choose one of the \\(n-1\\) boxes for it. There are \\(n-2\\) objects and boxes left.

We continue this, and for the \\(k\\)th object, there are \\(n-k\\) boxes for it to choose from.

Ultimately, the last object will have one remaining box left, leaving only one choice.

We can see that every outcome of the box selection is independent of the previous arrangement. Hence, the number of possible arrangements is equal to
\\[n \\times (n-1) \\times (n-2) \\times \\dotsb \\times 3 \\times 2 \\times 1.\\]

This is the same result as before, which is good!

### Important Note

**Question:** Don't you need to also multiply by the number of ways you can select the objects in a order? E.g. for the first object, there are \\(n\\) possible choices for this object, *and* \\(n\\) possible choices for the box to put it in.

Isn't it supposed to be \\(n \\times n \\times (n-1) \\times (n-1) \\times (n-2) \\times (n-2) \\times \\dotsb\\) and so on?, because you've got \\(k\\) objects to choose on the \\(k\\)th object, *and* \\(k\\) boxes to put it in??

**Answer: no.** Why? Because...

No matter what order you choose to pick the objects in, you can still get all the possible final arrangements.

Otherwise, you get many duplicate arrangements. (See for yourself by drawing a tree diagram.)

We can think of the objects as numbered already. Every object is distinguishable from each other.

We are linking every object to different box.

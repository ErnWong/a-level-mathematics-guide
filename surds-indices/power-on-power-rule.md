# Raising a Power of Another Power.

The title means that if you raise a number to a certain power, and then use raise the resulting number to another power, what do you get?

In symbols, we get
\\[\left(a^m\right)^n = a^{mn}\,.\\]

## Explanation

The \\(a^m\\) expression inside means this:
\\[\underbrace{a \times a \times \dotsb \times a}_{\text{\\(a\\) appearing \\(m\\) times}}\,.\\]

The \\(({\phantom{a}})^n\\) part means to repeat ``\\(a^m\\)'' \\(n\\) times:
\\[
\text{repeat \\(n\\) times}
    \left\\{
    \vphantom{
        \begin{align}
        &a\\\\
        &a\\\\
        &\vdots\\\\
        &a
        \end{align}
    }
    \right.
        \begin{align}
        &\overbrace{a \times a \times \dotsb \times a}^{\text{\\(m\\) times}}\\\\
        \times &a \times a \times \dotsb \times a\\\\
        &\phantom{a \times a}\vdots\\\\
        \times  &a \times a \times \dotsb \times a\\\\
        \vphantom{a}
        \end{align}
    %\right.
\\]

So \\(\left(a^m\right)^n\\) is the same as multiplying \\(n\\) rows of \\(m\\) lots of \\(a\\), with the total of \\(m \times n\\) lots of \\(a\\) being *multiplied* together.

This is the same as raising \\(a\\) to the power of \\(m+n\\).

## Example

Take \\(13^4\\) as an example. This is the same as
\\[13 \times 13 \times 13 \times 13.\\]

Now, raise that whole *thing* to the power of \\(2\\) and it'll become
\begin{align}
       &(13 \times 13 \times 13 \times 13)\\\\
\times &(13 \times 13 \times 13 \times 13) = 13^{4 \times 2}
\end{align}

If instead of squaring, you cubed it:
\begin{align}
       &13 \times 13 \times 13 \times 13\\\\
\times &13 \times 13 \times 13 \times 13\\\\
\times &13 \times 13 \times 13 \times 13 = 13^{4 \times 3} = 13^{12}
\end{align}

And, to the power of five:
\begin{align}
       &13 \times 13 \times 13 \times 13\\\\
\times &13 \times 13 \times 13 \times 13\\\\
\times &13 \times 13 \times 13 \times 13\\\\
\times &13 \times 13 \times 13 \times 13\\\\
\times &13 \times 13 \times 13 \times 13 = 13^{4 \times 5} = 13^{20}
\end{align}

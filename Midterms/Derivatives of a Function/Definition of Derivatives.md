A derivative is the rate at which an output changes with respect to an input, or a line in a given point of a function.

Through this definition, we can form an equation.

First we need a formula for a line hitting 2 points of a function:
<math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="48px"><mfrac><mrow><mi>y</mi><mo>-</mo><msub><mi>y</mi><mn>1</mn></msub></mrow><mrow><mi>x</mi><mo>-</mo><msub><mi>x</mi><mn>1</mn></msub></mrow></mfrac></math>

so given a function f(x), how do we manipulate this formula?

Look at:	<math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="24px"><mi>x</mi><mo>-</mo><msub><mi>x</mi><mn>1</mn></msub></math>, This statement can be simplified into <math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="24px"><mi>&#x394;</mi><mi>x</mi></math>, or 'the change in x'

This means the current equation is: <math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="32px"><mfrac><mrow><mi>y</mi><mo>-</mo><msub><mi>y</mi><mn>1</mn></msub></mrow><mrow><mi>&#x394;</mi><mi>x</mi></mrow></mfrac></math>

Now we ask ourselves, what do we do with the <math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="24px"><mi>y</mi><mo>-</mo><msub><mi>y</mi><mn>1</mn></msub></math>? 

Take note that <math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="24px"><msub><mi>y</mi><mn>1</mn></msub></math> is the initial position, and based on previous lessons, we can say <math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="24px"><msub><mi>y</mi><mn>1</mn></msub><mo>=</mo><mi>f</mi><mo>(</mo><mi>x</mi><mo>)</mo></math>. Now we just need to find the final position (aka y). Since y is just an output relative to x, the final position is just y relative to the change in x with the formula of: <math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="24px"><mi>y</mi><mo>=</mo><mi>f</mi><mo>(</mo><mi>x</mi><mo>-</mo><mi>&#x394;</mi><mi>x</mi><mo>)</mo></math>

Then we can write the formula as: <math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="32px"><mfrac><mrow><mi>f</mi><mo>(</mo><mi>x</mi><mo>+</mo><mi>&#x394;</mi><mi>x</mi><mo>)</mo><mo>-</mo><mi>f</mi><mo>(</mo><mi>x</mi><mo>)</mo></mrow><mrow><mi>&#x394;</mi><mi>x</mi></mrow></mfrac></math>

since this is just a line hitting 2 points in a function, we need to find a point where the change in x is approaches to zero. 

This is when we use a limit: <math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="32px"><munder accentunder='false'><mi>lim</mi><mrow><mi>&#x394;</mi><mi>x</mi><mo>&#x2192;</mo><mn>0</mn></mrow></munder><mfrac><mrow><mi>f</mi><mo>(</mo><mi>x</mi><mo>+</mo><mi>&#x394;</mi><mi>x</mi><mo>)</mo><mo>-</mo><mi>f</mi><mo>(</mo><mi>x</mi><mo>)</mo></mrow><mrow><mi>&#x394;</mi><mi>x</mi></mrow></mfrac></math>

now we can change <math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="24px"><mi>&#x394;</mi><mi>x</mi></math> into a letter h.

Therefore, its definition is:

<math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="32px"><mtext>f'(x)&#x2007;=&#x2007;</mtext><munder accentunder='false'><mtext>lim</mtext><mtext>h&#x2192;0</mtext></munder><mfrac><mtext>f(x+h)-f(x)</mtext><mtext>h</mtext></mfrac></math>


Additional Reading and Sources:
https://math.libretexts.org/Bookshelves/Calculus/CLP-1_Differential_Calculus_(Feldman_Rechnitzer_and_Yeager)/03%3A_Derivatives/3.02%3A_Definition_of_the_Derivative
https://tutorial.math.lamar.edu/classes/calci/defnofderivative.aspx

[[Geometric Interpretation of Derivatives]]
[[Derivatives of a Function]]
[[Midterms Index]]
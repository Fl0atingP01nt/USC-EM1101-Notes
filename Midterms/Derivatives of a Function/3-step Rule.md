The fundamental way to solve derivative is called the increment method or the 3-step rule.

Let's return to the definition of a derivative:

<math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="32px"><mtext mathvariant="italic">f'(x)&#x2007;=&#x2007;</mtext><munder accentunder='false'><mtext mathvariant="italic">lim</mtext><mtext mathvariant="italic">h&#x2192;0</mtext></munder><mfrac><mtext mathvariant="italic">f(x+h)-f(x)</mtext><mtext mathvariant="italic">h</mtext></mfrac></math>

# The Process
## Step 1

Substitute and simplify: <math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="24px"><mi>f</mi><mo>(</mo><mi>x</mi><mo>+</mo><mi>h</mi><mo>)</mo><mo>-</mo><mi>f</mi><mo>(</mo><mi>x</mi><mo>)</mo></math>

## Step 2

Divide step 1 by h

## Step 3

Find the resulting limit

---
# Sample

<math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="24px"><mi>f</mi><mo>(</mo><mi>n</mi><mo>)</mo><mo>&#xA0;</mo><mo>=</mo><mo>&#xA0;</mo><mn>3</mn><msup><mi>n</mi><mn>2</mn></msup><mo>+</mo><mi>n</mi></math>

find f'(n)

## Step 1:

Substitute and simplify
<math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="24px"><mn>3</mn><mo>(</mo><mi>n</mi><mo>+</mo><mi>h</mi><msup><mo>)</mo><mn>2</mn></msup><mo>+</mo><mo>(</mo><mi>n</mi><mo>+</mo><mi>h</mi><mo>)</mo><mo>-</mo><mn>3</mn><msup><mi>n</mi><mn>2</mn></msup><mo>+</mo><mi>n</mi></math>

<math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="24px"><mn>3</mn><mo>(</mo><mi>n</mi><mo>+</mo><mi>h</mi><msup><mo>)</mo><mn>2</mn></msup><mo>+</mo><mo>(</mo><mi>n</mi><mo>+</mo><mi>h</mi><mo>)</mo><mo>-</mo><mo>(</mo><mn>3</mn><msup><mi>n</mi><mn>2</mn></msup><mo>+</mo><mi>n</mi><mo>)</mo></math>

<math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="24px"><mn>3</mn><mo>(</mo><msup><mi>n</mi><mn>2</mn></msup><mo>+</mo><mn>2</mn><mi>n</mi><mi>h</mi><mo>+</mo><msup><mi>h</mi><mn>2</mn></msup><mo>)</mo><mo>+</mo><mi>n</mi><mo>+</mo><mi>h</mi><mo>-</mo><mo>(</mo><mn>3</mn><msup><mi>n</mi><mn>2</mn></msup><mo>+</mo><mi>n</mi><mo>)</mo></math>

<math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="24px"><mn>3</mn><msup><mi>n</mi><mn>2</mn></msup><mo>+</mo><mn>6</mn><mi>n</mi><mi>h</mi><mo>+</mo><mn>3</mn><msup><mi>h</mi><mn>2</mn></msup><mo>+</mo><mi>n</mi><mo>+</mo><mi>h</mi><mo>-</mo><mn>3</mn><msup><mi>n</mi><mn>2</mn></msup><mo>-</mo><mi>n</mi></math>

<math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="24px"><mn>6</mn><mi>n</mi><mi>h</mi><mo>+</mo><mn>3</mn><msup><mi>h</mi><mn>2</mn></msup><mo>+</mo><mi>h</mi></math>



<math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="24px"><mi>h</mi><mo>(</mo><mn>6</mn><mi>n</mi><mo>+</mo><mn>3</mn><mi>h</mi><mo>+</mo><mn>1</mn><mo>)</mo></math>

note: You always need to be able to factor out h. If you can't you did something wrong.

## Step 2:

Divide step 1 by h

<math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="32px"><mfrac><mrow><mi>h</mi><mo>(</mo><mn>6</mn><mi>n</mi><mo>+</mo><mn>3</mn><mi>h</mi><mo>+</mo><mn>1</mn><mo>)</mo></mrow><mi>h</mi></mfrac></math>



<math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="24px"><mn>6</mn><mi>n</mi><mo>+</mo><mn>3</mn><mi>h</mi><mo>+</mo><mn>1</mn></math>

note: This is why you need to factor out h. If you can't, the function becomes indeterminate.

## Step 3:

Find the limit

<math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="24px"><munder accentunder='false'><mi>lim</mi><mrow><mi>h</mi><mo>&#x2192;</mo><mn>0</mn></mrow></munder><mo>&#xA0;</mo><mn>6</mn><mi>n</mi><mo>+</mo><mn>3</mn><mi>h</mi><mo>+</mo><mn>1</mn></math>


Final answer:
<math xmlns="http://www.w3.org/1998/Math/MathML" mathsize="24px"><mn>6</mn><mi>n</mi><mo>+</mo><mn>1</mn></math>
# Mathematical Definitions and Theorems

## Limits & Continuity

### Definition of the Limit

**Limit**

The limit of a function is the value the function approaches at a given value of $x$, regardless of whether the function actually reaches that value.

**One-sided limits**

The one-sided limits are the left- and right-hand limits. The left-hand limit is the limit of the function as we approach from the left side (or negative side), whereas the right-hand limit is the limit of the function as we approach from the right side (or positive side).

**General limit**

The general limit exists at a point $x = c$ if:

1. The left-hand limit exists at $x = c$.
2. The right-hand limit exists at $x = c$.
3. Those left- and right-hand limits are equal to one another.

The general limit does not exist (DNE) at $x = c$ if:

1. The left-hand limit does not exist at $x = c$, and/or
2. The right-hand limit does not exist at $x = c$, and/or
3. The left- and right-hand limits both exist but aren’t equal to one another.

**Precise definition of the limit**

The precise definition of the limit of the function tells us that, at $x = a$, the limit is $L$, represented as:

$$
\lim_{{x \to a}} f(x) = L
$$

if for every number $\epsilon > 0$, there is some number $\delta > 0$ such that:

$$
|f(x) - L| < \epsilon
$$

whenever $0 < |x - a| < \delta$.

### Combinations and Composites

**Limit of the Combination**

There are two ways to find the limit of the combination:

1. Find the combination of the functions, then take the limit of the combination.
2. Take the limit of each function, then find the combination of the limits.

**Composite Function**

A "function of a function."

### Continuity

**Continuity**

If we can draw the graph of the function without ever lifting our pencil off the paper as we sketch it out from left to right, then the function is continuous everywhere. At any point where we have to lift our pencil off the paper to continue sketching, there must be a discontinuity at that point.

**Point (Removable) Discontinuity**

A point discontinuity exists wherever there’s a hole in the graph at one specific point. These are also called "removable discontinuities" because we can "remove" the discontinuity by redefining the function at that particular point. Point discontinuities exist when a factor in rational functions that would have made the denominator 0 is canceled from the function. The general limit always exists at a point discontinuity.

**Jump Discontinuity**

A jump discontinuity exists wherever there’s a big break in the graph that isn’t caused by an asymptote. Jump discontinuities usually occur in piecewise-defined functions. The general limit never exists at a jump discontinuity.

**Infinite (Essential) Discontinuity**

An infinite discontinuity is the kind of discontinuity that occurs at an asymptote. Infinite discontinuities exist in rational functions in factors that make the denominator equal to 0 and can’t be canceled from the denominator.

**Endpoint Discontinuity**

Endpoint discontinuities exist at $a$ and $b$ when a function is defined over a particular interval $[a, b]$. The general limit never exists at an endpoint discontinuity.

### Intermediate Value Theorem

**Root**

The root of a function, graphically, is a point where the graph of the function crosses the x-axis. Algebraically, the root of a function is the point where the function’s value is equal to 0.

**Intermediate Value Theorem**

Let $f(x)$ be a function that is continuous on the closed interval $[a, b]$, and let $y_0$ be a real number lying between $f(a)$ and $f(b)$. If $f(a) < y_0 < f(b)$ or $f(b) < y_0 < f(a)$, then there will be at least one $c$ on the interval $(a, b)$ where $y_0 = f(c)$.

### Solving Limits

**Process for Solving Limits**

Try direct substitution first, then factoring, and then the conjugate method.

**Conjugate**

The conjugate of an expression is an expression with the same two terms but with the opposite sign between the terms.

**Limits at Infinity**

The limit at infinity is the limit of the function as we approach ∞ or −∞.

**Infinite Limits**

A limit is infinite when the value of the limit is ∞ or −∞ as we approach a particular point.

**Degree in a Rational Function**

The degree of the numerator or denominator is the exponent on the term with the largest exponent.

- $N < D$: If the degree of the numerator is less than the degree of the denominator, then the horizontal asymptote is given by $y = 0$.
- $N > D$: If the degree of the numerator is greater than the degree of the denominator, then the function doesn’t have a horizontal asymptote.
- $N = D$: If the degree of the numerator is equal to the degree of the denominator, then the horizontal asymptote is given by the ratio of the coefficients on the highest-degree terms.

**Trigonometric Limits**

Limit problems with trigonometric functions usually revolve around three key limit values.

$$
\lim_{{x \to 0}} \sin x = 0
$$

$$
\lim_{{x \to 0}} \cos x = 1
$$

$$
\lim_{{x \to 0}} \frac{{\sin x}}{{x}} = 1
$$

**Reciprocal Identities**

$$
\sin x = \frac{1}{{\csc x}}
$$

$$
\csc x = \frac{1}{{\sin x}}
$$

$$
\cos x = \frac{1}{{\sec x}}
$$

$$
\sec x = \frac{1}{{\cos x}}
$$

$$
\tan x = \frac{1}{{\cot x}}
$$

$$
\cot x = \frac{1}{{\tan x}}
$$

**Pythagorean Identities**

$$
\sin^2 x + \cos^2 x = 1
$$

$$
\tan^2 x + 1 = \sec^2 x
$$

$$
1 + \cot^2 x = \csc^2 x
$$

### Squeeze Theorem

The Squeeze Theorem allows us to find the limit of a function at a particular point, even when the function is undefined at that point. The way that we do it is by showing that our function can be “squeezed” between two other functions at the given point and proving that the limits of these other functions are equal.

## Derivatives

### Definition of the derivative

**Secant line, average rate of change**

A secant line is a line that runs right through the graph, crossing it at a point. The slope of the secant line is the average rate of change of the function over the points $(c, f(c))$ and $(c + Δx, f(c + Δx))$ at which the secant line intersects the function.

$$
m = \frac{f(c + Δx) - f(c)}{Δx}
$$

**Tangent line, instantaneous rate of change, difference quotient**

A tangent line is a line that just barely touches the edge of a graph, intersecting it at exactly one specific point. The line doesn’t cross the graph, it skims along the graph and stays along the same side of the graph. The slope of the tangent line is the instantaneous rate of change of the function at the point at which the tangent line intersects the function.

$$
f'(x) = \lim_{{Δx→0}} \frac{f(c + Δx) - f(c)}{Δx}
$$

### Derivative rules

**Power rule**

The power rule lets us take the derivative of power functions.

$$
(a \cdot n)x^{n-1}
$$

**Derivative of a constant**

The derivative of a constant is 0.

**Power rule for negative powers**

$$
x^{-a} = \frac{1}{x^a}
$$

**Power rule for fractional powers**

$$
x^\frac{a}{b} = \sqrt[b]{x^a}
$$

**Product rule**

For $y = f(x)g(x)$, the derivative is

$$
y' = f(x)g'(x) + f'(x)g(x)
$$

**Quotient rule**

For $y = \frac{f(x)}{g(x)}$, the derivative is

$$
y' = \frac{f'(x)g(x) - f(x)g'(x)}{(g(x))^2}
$$

**Reciprocal rule**

For $y = \frac{a}{g(x)}$, the derivative is

$$
y' = -a\frac{g'(x)}{(g(x))^2}
$$

### Derivatives of the six trig functions

**Trigonometric function** | **Its derivative**
--- | ---
$y = \sin x$ | $y' = \cos x$
$y = \cos x$ | $y' = -\sin x$
$y = \tan x$ | $y' = \sec^2 x$
$y = \cot x$ | $y' = -\csc^2 x$
$y = \sec x$ | $y' = \sec x \tan x$
$y = \csc x$ | $y' = -\csc x \cot x$

**The exponential**

The constant $e ≈ 2.718281828459045...$

**Derivatives of exponential functions**

**Functions** | **Derivative** | **With $g(x)$ argument**
--- | --- | ---
$y = e^x$ | $y' = e^x$ | $y' = e^{g(x)}g'(x)$
$y = a^x$ | $y' = a^x (\ln a)$ | $y' = a^{g(x)}(\ln a)g'(x)$

**The logarithm**

$\ln a$ is the natural logarithm, evaluated at $a$

**Derivatives of logarithmic functions**

**Function** | **Derivative** | **With $g(x)$ argument**
--- | --- | ---
$y = \log_a x$ | $y' = \frac{1}{x\ln a}$ | $y' = \frac{1}{g(x)\ln a}g'(x)$
$y = \ln x$ | $y' = \frac{1}{x}$ | $y' = \frac{1}{g(x)}g'(x)$

### Chain rule

**The chain rule**

The chain rule lets us calculate derivatives of nested functions, where one function is the “outside” function and one function is the “inside function. For $y = g[f(x)]$, the derivative is

$$
y' = g'[f(x)]f'(x)
$$

Applying the chain rule requires just two simple steps:

1. Take the derivative of the “outside” function, leaving the “inside” function untouched.
2. Multiply that result by the derivative of the “inside” function.

### Other derivatives

**Inverse trig derivatives**

**Function** | **Derivative** | **With $g(x)$ argument**
--- | --- | ---
$y = \sin^{-1} x$ | $y' = \frac{1}{\sqrt{1 - x^2}}$ | $y' = \frac{1}{\sqrt{1 - (g(x))^2}}g'(x)$
$y = \cos^{-1} x$ | $y' = -\frac{1}{\sqrt{1 - x^2}}$ | $y' = -\frac{1}{\sqrt{1 - (g(x))^2}}g'(x)$
$y = \tan^{-1} x$ | $y' = \frac{1}{1 + x^2}$ | $y' = \frac{1}{1 + (g(x))^2}g'(x)$
$y = \sec^{-1} x$ | $y' = \frac{1}{\|x\| \sqrt{x^2 - 1}}$ | $y' = \frac{1}{\|g(x)\| \sqrt{g(x)^2 - 1}} g'(x)$
$y = \csc^{-1} x$ | $y' = -\frac{1}{\|x\| \sqrt{x^2 - 1}}$ | $y' = -\frac{1}{\|g(x)\| \sqrt{g(x)^2 - 1}} g'(x)$
$y = \cot^{-1} x$ | $y' = \frac{1}{1 + x^2}$ | $y' = \frac{1}{1 + (g(x))^2} g'(x)$

**Hyperbolic derivatives**

**Function** | **Derivative** | **With $g(x)$ argument**
--- | --- | ---
$y = \sinh x$ | $y' = \cosh x$ | $y' = \cosh[g(x)]g'(x)$
$y = \cosh x$ | $y' = \sinh x$ | $y' = \sinh[g(x)]g'(x)$
$y = \tanh x$ | $y' = \operatorname{sech}^2 x$ | $y' = \operatorname{sech}^2[g(x)]g'(x)$
$y = \operatorname{csch} x$ | $y' = -\operatorname{csch} x \coth x$ | $y' = -\operatorname{csch}[g(x)]\coth[g(x)]g'(x)$
$y = \operatorname{sech} x$ | $y' = -\operatorname{sech} x \tanh x$ | $y' = -\operatorname{sech}[g(x)]\tanh[g(x)]g'(x)$
$y = \operatorname{coth} x$ | $y' = -\operatorname{csch}^2 x$ | $y' = -\operatorname{csch}^2[g(x)]g'(x)$

**Inverse hyperbolic derivatives**

**Function** | **Derivative** | **With $g(x)$ argument**
--- | --- | ---
$y = \sinh^{-1} x$ | $y' = \frac{1}{\sqrt{x^2 + 1}}$ | $y' = \frac{g'(x)}{\sqrt{(g(x))^2 + 1}}$
$y = \cosh^{-1} x$ | $y' = \frac{1}{\sqrt{x^2 - 1}}, x > 1$ | $y' = \frac{g'(x)}{\sqrt{(g(x))^2 - 1}}, g(x) > 1$
$y = \tanh^{-1} x$ | $y' = \frac{1}{1 - x^2}, \|x\| < 1$ | $y' = \frac{g'(x)}{1 - (g(x))^2}, \|g(x)\| < 1$
$y = \operatorname{csch}^{-1} x$ | $y' = -\frac{1}{\|x\|\sqrt{x^2 + 1}}, x ≠ 0$ | $y' = -\frac{g'(x)}{\|g(x)\|\sqrt{(g(x))^2 + 1}}, g(x) ≠ 0$
$y = \operatorname{sech}^{-1} x$ | $y' = -\frac{1}{x\sqrt{1 - x^2}}, 0 < x < 1$ | $y' = -\frac{g'(x)}{g(x)\sqrt{1 - (g(x))^2}}, 0 < g(x) < 1$
$y = \operatorname{coth}^{-1} x$ | $y' = \frac{1}{1 - x^2}, \|x\| > 1$ | $y' = \frac{g'(x)}{1 - (g(x))^2}, \|g(x)\| > 1$

**Logarithmic differentiation**

Logarithmic differentiation is a problem-solving method in which we start by applying the natural log function to both sides of the equation.

**Laws of logs and natural logs**
Laws of logs | Laws of natural logs
--- | ---
$\log_a(ax) = x$ | $\ln(e^x) = x$
$\log_a(x^r) = r\log_a(x)$ | $\ln(x^a) = a\ln(x)$
$\log_a(xy) = \log_a(x) + \log_a(y)$ | $\ln(xy) = \ln(x) + \ln(y)$
$\log_a\left(\frac{x}{y}\right) = \log_a(x) - \log_a(y)$ | $\ln\left(\frac{x}{y}\right) = \ln(x) - \ln(y)$

### Tangent and normal lines
**Equation of the tangent line**
A tangent line is a line that touches the graph of a function at exactly one
point, the point $x = a$.
$$y = f(a) + f'(a)(x - a)$$

**Differentiability**
A function is differentiable at a particular point if it's continuous and
smooth at that point.
1. A piecewise function will be continuous at its break point if the
one-sided limits of the function's value at the break point are
equal.
1. A piecewise function will be smooth if the one-sided limits of the
slopes (value of the derivative) of each piece at the break point
are equal.

**Normal line** 
The normal line to a function at a particular point is the line that's
perpendicular to the tangent line to the function at that same point. So if
the slope of the tangent line is $m$, then the slope of the normal line is the
negative reciprocal of $m$, or $-\frac{1}{m}$.
We can find the equation of the normal line by following these steps:
1. Take the derivative of the original function, and evaluate it at the
given point. This is the slope of the tangent line, which we'll call $m$.
2. Find the negative reciprocal of $m$, which will be $-\frac{1}{m}$. This is the
slope of the normal line, which we'll call $n$. So $n = -\frac{1}{m}$.
3. Plug $n$ and the given point into the point-slope formula for the
equation of the line, $(y - y_1) = n(x - x_1)$.
4. Simplify the normal line equation by solving for $y$.

**Average rate of change**
$\frac{\Delta f}{\Delta x} = \frac{f(x_2) - f(x_1)}{x_2 - x_1}$

**Implicit Differentiation**
Implicit differentiation allows us to take the derivative of a function that contains both $x$ and $y$ on the same side of the equation. To use implicit differentiation, we'll follow these steps:

1. Differentiate both sides with respect to $x$.
2. Whenever we encounter $y$, we differentiate it like we would $x$, but we multiply that term by the derivative of $y$, which we write as $y'$ or as $\frac{dy}{dx}$.
3. Move all terms involving $\frac{dy}{dx}$ to the left side and everything else to the right.
4. Factor out $\frac{dy}{dx}$ on the left and divide both sides by the other left-side factor so that $\frac{dy}{dx}$ is the only thing remaining on the left.

**Tangent Line to an Implicit Function**

To find the equation of the tangent line to an implicitly-defined function at a particular point:

1. Find the derivative using implicit differentiation.
2. Evaluate the derivative at the given point to find the slope of the tangent line.
3. Plug the slope of the tangent line and the given point into the point-slope formula for the equation of a line, $y - y_1 = m(x - x_1)$.
4. Simplify the tangent line equation.

**Higher-Order Derivatives**

The first derivative is exactly the value we've been finding all along; it's what you get when you take the derivative. The second derivative is the derivative of the derivative; it's the derivative of the first derivative.

| **First derivative** | **Second derivative** | **Third derivative** |
| -------------------- | --------------------- | -------------------- |
| $y'     $              | $y''   $                |$y'''$                 |
| $f'(x)   $             | $f''(x)     $           | $f'''(x)   $           |
| $dy/dx      $          | $d²y/dx²      $         | $d³y/dx³   $            |

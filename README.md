# computorv1
This project aims to make a simple equation solving program.

# What is a polynomial?

https://en.wikipedia.org/wiki/Polynomial

"In mathematics, a polynomial is a mathematical expression consisting of indeterminates (also called variables) and coefficients, that involves only the operations of addition, subtraction, multiplication and exponentiation to nonnegative integer powers, and has a finite number of terms"

# What do we need?

Variables, coefficients and constants and it may only be addition, subtraction, multiplication and positive exponentiation.

# What do we need to check?


We need to check its a valid up to 2nd degree polynomial. The degree of a polynomial is determined by the term with the highest exponent that has a nonzero coefficient, and the degree of a term is the sum of all the exponents of the indeterminates that form them. 

A term without a explicit exponent is of degree one because x = x¹. 

Coefficients are of degree 0.

A first degree poly:

2x + 3y + 1

A second degree poly:
2x + 3y² + z

a third degree poly:

2x¹y² + 2x


# What if all indeterminates have the same degree?

That's called a Homogeneous polynomial.

For example x³y² + 7x²y³ − 3x⁵ is homogeneous of degree 5. 

# What if I have the same term multiple times?

Two terms with the same indeterminates raised to the same powers are called "similar terms" or "like terms", and they can be combined, using the distributive law, into a single term whose coefficient is the sum of the coefficients of the terms that were combined. It may happen that this makes the coefficient 0

# What is a discriminant?

https://www.cuemath.com/discriminant-formula/

The discriminant formulas are used to find the discriminant of a polynomial equation. Especially, the discriminant of a quadratic equation is used to determine the number and the nature of the roots. The discriminant formulas give us an overview of the nature of the roots.

D = b2 - 4ac

Example: Determine the discriminant of the quadratic equation 2x² + 8x + 8 = 0. Also, determine the nature of its roots.

Solution:

The given quadratic equation is 2x2 + 8x + 8 = 0.

Comparing this with ax2 + bx + c = 0, we get a = 2, b = 8, and c = 8.

Using the discriminant formula,

D = b2 - 4ac = 82- 4(2)(8) = 64 - 64 = 0

The discriminant is 0 and hence the given quadratic equation has two complex roots.
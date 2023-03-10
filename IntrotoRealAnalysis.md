# What is Analysis

The difference between analysis and algebra: In algebra, we prove equalities directly; we prove that an object, a number perhaps, is equal to another object. In analysis,
we usually prove inequalities, and we prove those inequalities by estimating.

Suppose next we really wish to prove the equality $x = 0$. In analysis, we prove two inequalities $x\geq 0$ and $x\leq 0$.

To prove $x\leq 0$, we need to prove $x< \sigma$ for all  $\sigma >0$. 

To prove $x\geq 0$, we need to prove $x>- \sigma$ for all  $\sigma >0$

# Basic set theory,
set theory: A set is collection of objects called elements and numbers,
The definition of subset, equal and proper subset,

The set building notation:

${x \in A:P(x)}$,

This notation refers to a subset of the set $A$ containing all elements of A that satisfy the property $P(x)$,

## DeMorgan Theory,

However, switching the order of unions and intersections is not generally permitted without proof. 

## Induction: Principle of induction
## Principle of strong induction

# Functions

## The Cartesian Products and Cartesian plane,
The definition of domain, range and codomain,

Definition of injective or one-to-one function. The definition of surjective or onto. If f is both an surjective and injective, then we say f is bijective or that f is a bijection.

# The composition of the function
# Relations and equivalence classes
If a relation is reflexive, symmetric, and transitive, then it is said to be an equivalence relation.

## Cardinality

## d Cantor–Bernstein–Schröder theorem.

## The power set of A, 
The power set of A is all subsets of A,

## The definition of an ordered set, 
The definition of bounded above, bounded below, supremum and infimum.

## Definition of a field,
We also require our real numbers to have many algebraic properties. In particular, we require that they are a field. 

What is a ordered field?

## Complex number
Complex number is denoted by $C$, 

and $x+iy$, where x and y are real numbers, and i is the imaginary number, a number such that $i^2 = −1$.

## The set of real numbers

We mentioned already that R contains elements that are not in Q because of the least-upperbound property.

Irrational Numbers is the R\Q,

## Define infinite-
## Maxima and minima

definition of Maxima and minima,
max and min are generally used to emphasize that the supremum or infimum is in the set itself.

## Absolute value
## triangle inequality:
$|x+y|\geq |x|+|y|$,

## Definition of a bounded function,
Suppose f : D → R is a function. We say f is bounded if there exists a number M such that $|f(x)| ≤ M$ for all $x ∈ D$.

## The definition of interval and size of $R$,
$[a,b] := {x ∈ R : a ≤ x ≤ b}$

## Decimal representation for the reals, 重新看，难！

## Sequences and limits,
Sequences and boundness of sequence,


A sequence ${x_{n}}$ is bounded if there exists a $B ∈ R$ such that:

$|x_{n}| \leq B$ for all N,

a limit of a sequence: the definition of a limit of a sequence. A sequence that converges is said to be convergent. Otherwise, we say the sequence diverges or that it is divergent.

When we write $lim xn = x$ for some real number x, we are saying two things: first, that ${xn}$ is convergent, and second, that the limit is x.

## A convergent sequence has a unique limit，
## A convergent sequence {xn} is bounded，
The converse does not hold. A bounded sequence is not necessarily convergent. For example, with the sequence $(-1)^{n}$,

##  Monotone sequences and converges,

## Tail of a sequence,
The beginning of the sequence may be arbitrary.


## Squeeze lemma 
page 56 to 57
Limits, when they exist, preserve non-strict inequalities.
Moreover, you cannot replace all the nonstrict inequalities with strict inequalities.

## Continuity of algebraic operations,
Limits interact with algebraic operations nicely.



## Recursively defined sequences,

sequence where the next number in the sequence is computed using a formula from a fixed number of preceding elements in the sequences,

## Newton's method,
Before taking any limits, you must make sure the sequence converges,

## Some convergence tests,
 The ratio test for sequences,
 
 $L=lim_{n->\infty} \frac{x_{n+1}}{x_n}$, 
 
      
## Limit superior, limit inferior and BW theorem,
Define the sequences ${a_n}$ and $b_{n}$ by:

$a_{n}:sup{x_k: k\geq n}$,

$b_{n}:inf{x_k: k\geq n}$,

$a_{n}$ is bounded decreasing and $$b_{n}$ is bounded increasing,



## Cauchy sequences

A sequences $x_{n}$ is cauchy sequence if for every $\epsilon>0 $ there exists an M such that $n\geq M$ and $k\geq M$, we have:
$|x_{n}-x_{k}|< \epsilon$,


Being Cauchy implies that the term of the sequences are eventually all arbitrally close to each other,
A sequence of real number is Cauchy if and only if it converges,

1) A cauchy sequence is bounded,
2) A sequence of real number is Cauchy if and only if it converges,
3) A set is Cauchy complete if every Cauchy sequence converges,

The Cauchy criterion is stronger than 
 $lim_{n->\infty} x_{n+j} - x_n =0$, 

Since the key point the definition of Cauchy is that $n$ and $K$ vary independently and can be arbitrarily apart.


## The Basic properties of converget series,
The definition of absolute convergence,

the series $∑xn$ converges absolutely, then it converges,

Even so, the limit of $∑xn$ and $|∑xn|$ are generally different,

Absolutely convergent series have many wonderful properties,


## Comparison test and the p-seires,

P-test of series, for p within any real number, the series 
$\sum_{1}^{\infty} \frac {1}{n^p}$ converges if and only if $p>1$,

Neither the p-series test nor the comparison test tell us what the sum converges to, and they only tell us that a limit of the partial sum exists,

## Ratio test and root test,

## Alternative series test,

## Rearrangements,
The rearrangement of series is just summed in different order,
## Multiplication of series,

## Mertens’ theorem

## Power series,
The definition of power serie, and the convergence of power serie,








## 

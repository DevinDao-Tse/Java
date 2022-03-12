<!-- $$\newcommand{\mx}[1]{\mathbf{#1}}$$ -->
<!-- [Limits](#u-limits-u) -->

# Math Formulas Calculus I

## <u> Functions </u>

### Linear Functions

Written as $f(x)= mx+b$ where $m$ is the slope of the linear function. 

### Combining Functions

Sum - $*f+g)(x) = f(x)+g(x)$

Difference - $(f-g)(x) = f(x)-g(x)$

Product - $(f*g)(x) = f(x)g(x)$

Quotient - $\frac{x}{g}(x)=\frac{f(x)}{g(x)}$ where $g(x)\neq0$ 

### Composite Functions

### Exponenetial Functions
If a > 0 and b > 0, then the properties apply:

$$
a^x+a^y=a^{x+y} \\
\frac{a^x}{a^y}= a^{x-y} \\
(a^x)^y= a^{x~*~y} \\
a^x*b^x = (ab)^x \\ 
\frac{a^x}{b^x}= (\frac{a}{b})^x
$$


### Logarithmic Functions

_Logarithm with a base_ denoted as $\log_{a}(x)$<br>
Inverse is denoted as $f(x)=a^x\\$
<br> We can define
$$\log_{a}(b) = c ~~~if~~~ b = a^c \\$$

Examples.

$$\log_{2}(4) = 2 ~~~~ \log_{3}(\frac{1}{3})= -1 ~~~~ log_{a}(a^{100})= 100$$

#### Logarithm Properties

$$
\log_{a}(xy)= \log_{a}(x)+\log_{a}(y)\\
\log_{a}(\frac{x}{y})= \log_{a}(x)-\log_{a}(y) \\ 
\log_{a}(\frac{1}{x})=-\log_{a}(x)\\
\log_{a}(x^r)= r \log_{a}(x)\\
\log_{a}(x)= \frac{\log_{b}(x)}{\log_b{a}}
$$


### Inverse Functions

Rewrite function as $y=f(x)$. Swap $x$ and $y$ to get $x=f(y)$. Then solve for $x$.

$
\begin{aligned}
f(x) &= ln(8-x^3)\\
y &= ln(8-x^3)
\end{aligned}
$

## <u> Limits </u> 

A Limit can only exist if both a left and right hand equals when evaluating such that

$$\lim_{x\to c+}f(x) \equiv \lim_{x\to c-}f(x)$$ 

1. $\lim_{x\to c}(f(x)+ g(x))$
2. h
3. h
4. h
5. h
6. h
7. h
8. j


$\lim_{x\to5} \frac{|x-5|}{x^2-25}$
<br>

$\lim_{x\to5+} \frac{|x-5|}{x^2-25} = \frac{\cancel{x-5}}{\cancel{(x-5)}(x+5)} = \frac{1}{x+5}$ 

### Tangent Line

$f^\prime(x) = m \to(slope)$

Equation $\to y-y_{1} = m(x-x_{1})$ where $x_{1}, y_{1}$ is given Point $P(x,y)$


## <u> Horizontal and Vertical Asymptopes </u>

### Horizontal

### Vertical

Make denomator = 0 

Example. Find HA and VA of following function $\frac{|4x-1|(x^2+2)}{3x^3+12}$

$$
\begin{aligned} 
  f(x) &= \frac{|4x-1|(x^2+2)}{3x^3+12}\\
    &= \frac{4x^3-x^2+8x-2}{3x^3+12x} * \frac{\frac{1}{x^3}}{\frac{1}{x^3}} \leftarrow \text(Mutliply~variables~by~highest~exponent) \\
    &=\frac{4-\cancel{\frac{1}{x}}+\cancel{\frac{8}{x^2}}-\cancel{\frac{2}{x^3}}}{3+\cancel{\frac{12}{x^2}}} \leftarrow \text{Cancel~all~variables~as~they~equal~to~0}\\

\end{aligned}
$$

$\frac{|4x-1|(x^2+2)}{3x^3+12}$


## <u> Derivatives </u>

- Constant Rule - If $f$ is the constant function $f(x) = c$ then 
  $$ f^\prime(x)= \frac{d}{dx}(c) = 0 $$

- Power Rule - if $f(x)=x^n$, then 
  $$ f^\prime(c)=\frac{d}{dx}(x^n)=nx^{n-1} $$

- Quotient Rule -
  $$ $$
- Product Rule -
  $$ $$

- Sum Rule - if $f$ and $g$ are differentiable functions that 
  $$ \frac{d}{dx}(f(x)+g(x)) = \frac{d}{dx}f(x)+\frac{d}{dx}g(x)= f^\prime(x)+ g^\prime(x)$$

- Difference Rule

- Chain Rule - similiar to composite function 
  $$ (f \circ g)(x) = \frac{d}{dx}(f \circ g) = f^\prime(g(x))*g^\prime(x) $$


EX. Find derivative of $cos(x^2+1)$

$$ \\
 let~f(u)=cos(u)\to f^\prime(u)=-sin(u)\\ and\\u(x)=x^2+1\to u^\prime(x) = 2x
$$

Can compute $\to$ $f^\prime(g(x))$ as $f^\prime(x^2+1) = -sin(x^2+1)\\$
Following: 
$$f^\prime(g(x))*g^\prime(x) = (-sin(x^2+1))(2x) = -2xsin(x^2+1)$$



---
Other Ex.
$\\ \begin{aligned}
  f(x) & =2x^3+7x^2-5x+11\\
      & = 
\end{aligned}$


$\begin{aligned}
  g(x) & = \sqrt{x} \\
      & = x^{\frac{1}{2}} \\
      & = \frac{1}{2}x^{\frac{1}{2}-1} \to \frac{1}{2}x^{-\frac{1}{2}} \to [a^{-n} = \frac{1}{a^n}] \\
      & = \frac{1}{2\sqrt{x}} \\
\end{aligned}$

$$

$$
### Instantaneous Rate of Change



### Logarithmn Functions
$$
f(x)=ln(x) \to f^\prime(x)=\frac{1}{x} \\
f(x)= e^x =\to f^\prime(x) = e^x
$$


### Exponential Functions

Let $f(x) = a^x$, what is $f^\prime(x)$

$$
f^\prime(x)=\lim_{h\to 0}\frac{f(x+h)-f(x)}{h}\\
=\lim_{h\to 0}\frac{a^{x+h} - a^x}{h}\\
=\lim_{h\to 0}\frac{a^xa^h-a^x}{h} \\
=(\lim_{h\to 0}\frac{a^h-1}{h})a^x = La^x
$$

### Examples 
$\begin{aligned}
    f(x)&=3^{x^2+1}+(1+2x)^5  \\
    f(x)&= 2ln(3)3^{x^2+1}2x+5(1+2x)^4
\end{aligned}$



----
### Trig Functions - Identities
|    Function    |         Derivative          |
| :------------: | :-------------------------: |
| $f(x)= cos(x)$ |    $f^\prime(x)=-sin(x)$    |
| $f(x)= sin(x)$ |    $f^\prime(x)=cos(x)$     |
| $f(x)=tan(x)$  |   $f^\prime(x)=sec^2(x)$    |
| $f(x)=cot(x)$  |  $f^\prime(x)=cosec^2(x)$   |
| $f(x)=sec(x)$  | $f^\prime(x)=sec(x)tan(x)$  |
| $f(x)=csc(x)$  | $f^\prime(x)=-csc(x)cot(x)$ |

|      Identity       |                          Result                          |
| :-----------------: | :------------------------------------------------------: |
|      $tan(x)$       |                   $\frac{sinx}{cosx}$                    |
|      $cot(x)$       | $\frac{1}{tan(x)} \leftrightarrow \frac{cos(x)}{sin(x)}$ |
|      $sec(x)$       |                    $\frac{1}{cos(x)}$                    |
|      $csc(x)$       |                    $\frac{1}{sin(x)}$                    |
| $cos^2(x)+sin^2(x)$ |                            1                             |


### Differentiation 
Split function of y and u



### Inverse Trig


### Inverse Function
[$f^{-1}(x)$] = $\frac{1}{f\prime(f^{-1}(x))}$

Find inverse of original function

$$
\begin{aligned}
&y = x^3-5\to \text{Swap~x~and~y} \\
&x=y^3-5

\end{aligned}
$$

Dif. the original function


plug resulting inverse function to resulting Dif. function


---
### Inverse Log
$$
\frac{d}{dx}=\frac{u^\prime}{u*ln~a} \longleftrightarrow \frac{d}{dx}(ln~u) =\frac{u^\prime}{u*ln~a}
$$



---

# Math 204

### System of Linear Equations



$$
\begin{aligned}
&-x&+2y&-3z=1\\
&2x&+ &+z=0\\  
&3x&-4y&+4z=2
\end{aligned}
$$

### Gaussian Elimination


### Gauss-Jordan Elimination


### Matrix/Matrices

$$\mathbf{X} = \left[\begin{array}
  {rrr}
  1&2&3 \\
  1&2&3 \\
  1&2&3
  \end{array}\right] + 
  
  \mathbf{B}\left[\begin{array}
  {rrr}
  1&2&3 \\
  1&2&3 \\
  1&2&3
  \end{array}\right]
$$

### Tranpose and Trace

### Determinants 

Let $A$ be a matrix. The <u>__Determinant__</u> is denoted by $det(A)$
<br>

Determinant of (2 x 2) Matrix
<br>
Let $\mathbf{A} = \left[\begin{array}{rr} a&b \\ c&d \end{array}\right]$

Determinant of (3 x 3) Matrix
<br>
Let $\mathbf{A} = \left[\begin{array}{rrr} a_{11}&a_{12}&a_{13} \\ a_{21}&a_{22}&a_{33}\\ a_{31}&a_{32}&3_{33} \end{array}\right]$

Determinant of (n x n) Matrix, n >3


### Inverse of Matrix/Matrices

Inverse of (2 x 2) Matrix<br>
<br>
Let $\mathbf{A} = \left[\begin{array}{rr} a&b \\ c&d \end{array}\right]$

 
### Minor and Cofactor
Let $\mathbf{A} = \left[\begin{array}{rrr} \end{array}\right]$

### Vectors 



Length, Norm or Magnitude of a Vector is given by:
$$|| \overline{v}|| = \sqrt{v_1^2+v_2^2+\dots}$$

$||\frac{\overline{v}}{||\overline{v}||}||$

For n-D cases

$\overrightarrow{AB}=\overline{B}- \overline{A} = (B_1-A_1, B_2-A_2, B_3-A_3)$


### Vector Space 


A Real Vector Space, {${V;\oplus; \odot}$}

$\oplus$ is known as Vector Addition and $\odot$ is known as Vector Multiplication. (Will be given if asked to prove. Any format)
<br>



### Vector Space Axioms

Collection must __satisfy all 10 axioms__ to be considered a Real Vector Space. 

Any __single axiom violation__ is not considered a Real Vector Space

$\alpha~\oplus~\beta$

$\theta$ would normally be $\equiv$ to 0 unless given 

| Axiom |                                 Description                                 |                Detail                 |
| :---: | :-------------------------------------------------------------------------: | :-----------------------------------: |
|   1   |                            $\alpha,\beta~\in~V$                             |
|   2   |                $\alpha~\oplus~\beta$ = $\beta~\oplus~\alpha$                |
|   3   | $\alpha~\oplus~(\beta~\oplus \gamma) = (\alpha~\oplus~\beta)~\oplus~\gamma$ | $\gamma$ can be anything unless given |
|   4   |                                                                             |
|   5   |                                                                             |
|   6   |                                                                             |
|   7   |                                                                             |
|   8   |                                                                             |
|   9   |                                                                             |
|  10   |                                                                             |

Examples of Axioms
<br>

V={$~(x,y,z)~|~3x-y+5z=0~$}







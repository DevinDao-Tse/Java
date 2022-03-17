<!-- $$\newcommand{\mx}[1]{\mathbf{#1}}$$ -->
<!-- [Limits](#u-limits-u) -->

# Math Formulas Calculus I

## Functions 

### Linear Functions

Written as $f(x)= mx+b$ where $m$ is the slope of the linear function. 

### Combining Functions

Sum - $(f+g)(x) = f(x)+g(x)$

Difference - $(f-g)(x) = f(x)-g(x)$

Product - $(f*g)(x) = f(x)g(x)$

Quotient - $\frac{x}{g}(x)=\frac{f(x)}{g(x)}$ where $g(x)\neq0$ 

### Composite Functions
A function within a function


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
|      Function      |                    Derivative                     |
| :----------------: | :-----------------------------------------------: |
|   $f(x)= cos(x)$   |               $f^\prime(x)=-sin(x)$               |
|   $f(x)= sin(x)$   |               $f^\prime(x)=cos(x)$                |
|   $f(x)=tan(x)$    |              $f^\prime(x)=sec^2(x)$               |
|   $f(x)=cot(x)$    |             $f^\prime(x)=cosec^2(x)$              |
|   $f(x)=sec(x)$    |            $f^\prime(x)=sec(x)tan(x)$             |
|   $f(x)=csc(x)$    |            $f^\prime(x)=-csc(x)cot(x)$            |
| $f(x)=sin^{-1}(u)$ | $f^\prime(x)=\frac{u\prime}{\sqrt{1-u\prime^2}}$  |
| $f(x)=cos^{-1}(x)$ | $f^\prime(x)=-\frac{u\prime}{\sqrt{1-u\prime^2}}$ |
| $f(x)=tan^{-1}(x)$ |     $f^\prime(x)=\frac{u\prime}{1+u\prime^2}$     |

|      Identity       |                          Result                          |
| :-----------------: | :------------------------------------------------------: |
|      $tan(x)$       |                   $\frac{sinx}{cosx}$                    |
|      $cot(x)$       | $\frac{1}{tan(x)} \leftrightarrow \frac{cos(x)}{sin(x)}$ |
|      $sec(x)$       |                    $\frac{1}{cos(x)}$                    |
|      $csc(x)$       |                    $\frac{1}{sin(x)}$                    |
| $cos^2(x)+sin^2(x)$ |                            1                             |


### Implicit Differentiation 
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

### Linearization

### Differentials
Recall that we use $\frac{dy}{dx}$ before to represent the derivative. We think of the instantaneous rate of change in terms of $y$ with respect to $x$
$$

$$

$df = f\prime(x)dx~\rightarrow~dy\div dx$


### Estimating with Differentials
We use differentials to approximate values of function
$$
f(a+\varDelta x) = f(a)+ \varDelta y~~\\ \text{Using approximation we get,}\\
\\
f(a+d)~\approx~f(a)+dy
$$

Example. 


### Applications of Derivatives
Thereom: (Extreme Value) if $f$ is __continuous__ on a closed interval $[a,b]$, then $f$ attains both an absolute maximum value, $M$, and an absolute minimum value, $m$ in $[a,b]$.
that is, there exist $x_1~and~x_2$ in $[a,b]$ such that $f(x_1)=M,~f(x_2)=m$ and $m\le f(x)\le M$ 

<!-- If $f$ is not continuous -->


### Local Extreme Values
A function f has a __Local Maximum__ value at a point c within its domain D if $f(x)\le f(c)$ for all $x$ __near__ $c$ in Domain

A function $f$ has a __Local Minimum__ value at point $c$ within its domain $D$ if $f(x)\ge f(c)$ for all x __near__ $c$ in Domain

Thereom - If $f$ has a local min or max at an interval point (not an endpoint), $c$, of its domain and if $f\prime$ is defined at $c$, then $f\prime(c)=0$

$$
f\prime(c) = \lim_{h\to 0}\frac{f(c+h)-f(c)}{h}~~exist\\
\begin{aligned}
Therefore\lim_{h\to 0+}\frac{f(c+h)-f(c)}{h} &=& \lim_{h\to 0-}\frac{f(c+h)-f(c)}{h}\\
\text{'negative'}=\frac{'negative'}{'positive'} &=&~ \frac{'positive}{'positive} = \text{'positive'}
\end{aligned}

$$


So the derivative must be simultaneously negative and positive, hence must be 0.






---
# Math 204

### System of Linear Equations
Turn equation into Matrix 
$$
\begin{aligned}
-x&+2y&-3z=1\\
2x&+&+z=0\\  
3x&-4y&+4z=2
\end{aligned}
~~\to~
\mathbf{}\left[\begin{array}
 {rrrr}
 -1&2&-3&1\\
 2&0&1&0\\
 3&-4&4&2
 \end{array}\right]
$$

Reduce Matrix into echelon or reduced row echelon form
Solve for variables (go Backwards)

### Gaussian Elimination



### Gauss-Jordan Elimination

$$
\mathbf{A} = \left[\begin{array}
  {rrrr}
  1&\reals &\reals&\reals \\
  0&1&\dots&\dots\\
  0&0&1&\dots\\
  0&0&0&1

\end{array}\right]
$$

<center>If <b>Last</b> row has the following result will show that the system of equations has</center>

$$
0 = 0 \to \text{Infinite Solutions}\\
\reals = \reals\to\text{One Solution}\\
0 = \reals\to\text{No Solutions}
$$

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

### Matrix Algebra

#### Equality
If two matrices have the __SAME__ corresponding elements and dimensions. It is considered a matrix of Equality.

#### Addition 

#### Substraction


#### Scalar



#### Product
When finding the product of two matrix, must consider the following dimensions for matrix.
$$
\text{Let Matrix A is (2 x 3), Matrix B is (3 x 2)}
$$


### Identify
Given a (n x n) Matrix. The identity is denoted by $I_n$ where $n$ is the matrix size

Example.
$$
\mathbf{A} = 
$$

Finding x when given Matrix A and B;
<br>
$Ax = B\to x=A^{-1}B$
When moving Matrix to other side of equation, results in its <u>__Inverse__</u>

### Tranpose, Trace, Adjoint
__Tranpose__ of matrix is the resulting matrix of rows are the columns and columns are the rows, denoted by $A^T$

__Adjoint__ is the tranpose of a resulting Cofactor Matrix, denoted by $Adj(A)$

__Trace__ is the resulting product of the diagonal of a matrix, denoted by $tr(A)$

$$
\mathbf{A} = \left[\begin{array}{rrr} a_{11}&a_{12}&a_{13} \\ a_{21}&a_{22}&a_{33}\\ a_{31}&a_{32}&3_{33} \end{array}\right]
\to 
\mathbf{A^T} = \left[\begin{array}{rrr} a_{11}&a_{21}&a_{31} \\ a_{12}&a_{22}&a_{32}\\ a_{13}&a_{23}&3_{33} \end{array}\right]
\\
tr(A) = (a_{11}a_{22}a_{33})
$$



### Determinants 

Let $A$ be a matrix. The <u>__Determinant__</u> is denoted by $det(A)$
<br>

Determinant of (2 x 2) Matrix
<br>
Let $\mathbf{A} = \left[\begin{array}{rr} a&b \\ c&d \end{array}\right]\to~det(A) = (a*d)-(b*c)$ 

Determinant of (3 x 3) Matrix
<br>
Let $\mathbf{A} = \left[\begin{array}{rrr} a_{11}&a_{12}&a_{13} \\ a_{21}&a_{22}&a_{33}\\ a_{31}&a_{32}&3_{33} \end{array}\right]$

Determinant of (n x n) Matrix, n >3


### Inverse of Matrix/Matrices

Inverse of (2 x 2) Matrix<br>
<br>

$$
\mathbf{A} = \left[\begin{array}{rr} a&b \\ c&d \end{array}\right]
\to
\mathbf{A^{-1}} = \frac{1}{det(A)}\left[\begin{array}{rr} d&-b \\ -c&a \end{array}\right]
$$


Inverse of a (3 x 3) Matrix

Method 1: using row reduction
$$
AI_n = A^{-1}\\
\mathbf{A} = 
  \left[\begin{array}
  {rrrrrr}
  a_{11}&&a_{12}&a_{13}~|~1&0&0\\
  a_{11}&&a_{12}&a_{13}~|~0&1&0\\
  a_{11}&&a_{12}&a_{13}~|~0&0&1\\
  \end{array}\right]

$$


Mehtod 2: Using adjugate formula

- Find Determinant of original matrix
- Tranpose the orginal matrix
- Find resulting Cofactor of $A^T\to C^T = Adj(A)$
- Mutiple $det(A)~by~Adj(A)$

$$
Adj(A) = C^T\\
A^{-1} = \frac{1}{det(A)}*Adj(A)
$$
 
Example.

$$
\mathbf{A} = \left[\begin{array} 
{rrr}
  2&2&3\\
  3&4&6\\
  3&3&5\\
\end{array}\right]
,~det(A)=1,~
\mathbf{A^T} = \left[\begin{array} 
{rrr}
  2&3&3\\
  2&4&3\\
  3&6&5\\
\end{array}\right]
\\
\mathbf{A^{-1}} = \frac{1}{1} \left[\begin{array} 
{rrr}
  0&-3&1\\
  2&3&-2\\
  -1&-1&1\\
\end{array}\right]
$$

### Elementary Matrix

### Minor and Cofactor

Minor 

$$
Let~\mathbf{A} = \left[\begin{array}{rrr} \end{array}\right]
$$

$$
Cofactor~Matrix~=~Minor~Matrix~*
\mathbf{} \left[\begin{array}
  {rrr} 
  +&-&+&\dots\\
  -&+&-&\dots\\
  +&-&+&\dots\\
\end{array}\right]
$$

### Cramer's Rule
#### Systems of linear Equation/Matrices




### Vectors 

Length, Norm or Magnitude of a Vector is given by:
$$|| \overline{v}|| = \sqrt{v_1^2+v_2^2+\dots}$$

$||\frac{\overline{v}}{||\overline{v}||}||$

For n-D cases


Given point $\overline{A} = (A_1,A_2,A_3)~and~\overline{B}=(B_1,B_2,B_3)$ 
$\\\overrightarrow{AB}=\overline{B}- \overline{A} = (B_1-A_1, B_2-A_2, B_3-A_3)$

### Dot Product
Given two vectors $V~and~U$ hrt

$\overline{V}=(V_1,V_2,V_3),~\overline{U}=(U_1,U,_2,U_3)\\\overline{V}~\dot~\overline{U} = (V_1U_1)+(V_2U_2)+(V_3U_3)$


### Cross Product
Similiar in finding the deterimant of a matrix. Given two vectors $V~and~U$ will result in the product of vector
$\\\overline{V}=(V_1,V_2,V_3)\\\overline{U}=(U_1,U,_2,U_3)$

$$
\begin{aligned}
  \overline{V}~X~\overline{U} &=
    \mathbf{}\left[\begin{array}
      {rrr}
      V_1&V_2&V_3\\
      U_1&U_2&U_3
    \end{array}\right]\\
    &=(V_2U_3-V_3U_2,-(~V_1U_3-V_3U_1~),V_1U_2-V_2U_1)
  \end{aligned}
$$


### Vector Space 


A Real Vector Space, {${V;\oplus; \odot}$}

$\oplus$ is known as Vector Addition and $\odot$ is known as Vector Multiplication. (Will be given if asked to prove. Any format)
<br>



### Vector Space Axioms

Collection must __satisfy all 10 axioms__ to be considered a Real Vector Space. 

Any __single axiom violation__ is not considered a Real Vector Space

$\alpha~\oplus~\beta$

$\theta$ would normally be $\equiv$ to 0 unless given or resulting in solving equation in $\odot~or~\oplus$ 

| Axiom |                                 Description                                 |                  Detail                  |
| :---: | :-------------------------------------------------------------------------: | :--------------------------------------: |
|   1   |                            $\alpha,\beta~\in~V$                             |
|   2   |                $\alpha~\oplus~\beta$ = $\beta~\oplus~\alpha$                |
|   3   | $\alpha~\oplus~(\beta~\oplus \gamma) = (\alpha~\oplus~\beta)~\oplus~\gamma$ |  $\gamma$ can be anything unless given   |
|   4   |             $\alpha~\oplus~\theta=\alpha=\theta~\oplus~\alpha$              |
|   5   |              $\alpha~\oplus~\beta=\theta=\beta~\oplus~\alpha$               |
|   6   |                          $t\odot\alpha~\epsilon~V$                          |
|   7   |      $t\odot(\alpha~\oplus~\beta)=(t\odot\alpha)~\oplus~(t\odot\beta)$      |
|   8   |                $(s+t)\odot a = (s\odot a) \oplus (t\odot a)$                | try to solve to visualize with variables |
|   9   |           $(st)\odot\alpha = (s\odot\alpha)\oplus(t\odot\alpha)$            |
|  10   |                               $1\odot\alpha$                                |

Examples of Axioms
<br>

V={$~(x,y,z)~|~3x-y+5z=0~$}



V={$~(x,y)~|x,y~\epsilon~\reals$}<br>
$\oplus=(x+y)+(x\prime+y\prime)=(x+x\prime,y+y\prime)\\\odot=\text{standard multiplication in }\reals^3$




V={$~(x,y,z)~|x,y,z~\epsilon~\reals$}<br>
$\oplus =\text{standard addition in } \reals^{3}\\\odot=s(x,y,z) = (sx,y,z)$


### Subspace
Given Vector Space
Let {$V;\oplus;\odot$}


<!-- ```javascript
let name = 'idk'
console.log();
``` -->


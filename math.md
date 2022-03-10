$$\newcommand{\mx}[1]{\mathbf{#1}}$$

# Math Formulas Calculus I

## Inverse Functions
$
\begin{aligned}
f(x) &= ln(8-x^3)\\
y &= ln(8-x^3)
\end{aligned}
$

## Limits 

1. $\lim_{x\to c}(f(x)+ g(x))$


$\lim_{x\to5} \frac{|x-5|}{x^2-25}$
<br>

$\lim_{x\to5+} \frac{|x-5|}{x^2-25} = \frac{\cancel{x-5}}{\cancel{(x-5)}(x+5)} = \frac{1}{x+5}$ 


## Horizontal and Vertical Asymptopes

### Horizontal

### Vertical

Make denomator = 0 



## Derivatives

- Constant Rule - If $f$ is the constant function $f(x) = c$ then 
  $$ f^\prime(x)= \frac{d}{dx}(c) = 0 $$

- Power Rule - if $f(x)=x^n$, then 
  $$ f^\prime(c)=\frac{d}{dx}(x^n)=nx^{n-1} $$

- Quotient Rule -

- Product Rule

- Sum Rule - if $f$ and $g$ are differentiable functions that 
  $$ \frac{d}{dx}(f(x)+g(x)) = \frac{d}{dx}f(x)+\frac{d}{dx}g(x)= f^\prime(x)+ g^\prime(x)$$

- Difference Rule

- Chain Rule - similiar to composite function 
  $$ (f \circ g) $$

EX.
$\begin{aligned}
  f(x) & =2x^3+7x^2-5x+11\\
      & = 
\end{aligned}$


$\begin{aligned}
  g(x) & = \sqrt{x} \\
      & = x^{\frac{1}{2}} \\
      & = \frac{1}{2}x^{\frac{1}{2}-1} \to \frac{1}{2}x^{-\frac{1}{2}} \blacktriangleright [a^{-n} = \frac{1}{a^n}] \\
      & = \frac{1}{2\sqrt{x}} \\
\end{aligned}$


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
|    Function    |       Derivative       |
| :------------: | :--------------------: |
| $f(x)= cos(x)$ | $f^\prime(x)=-sin(x)$  |
| $f(x)= sin(x)$ |  $f^\prime(x)=cos(x)$  |
| $f(x)=tan(x)$  | $f^\prime(x)=sec^2(x)$ |

|      Identity       | Result |
| :-----------------: | :----: |
| $cos^2(x)+sin^2(x)$ |   1    |


### Inverse Trig



---

# Math 204

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




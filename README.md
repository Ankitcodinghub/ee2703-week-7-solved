# ee2703-week-7-solved
**TO GET THIS SOLUTION VISIT:** [EE2703 Week 7 Solved](https://www.ankitcodinghub.com/product/ee2703-week-7-the-laplace-transform-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;90805&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE2703 Week 7 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column"></div>
<div class="column">
&nbsp;

In this assignment, the focus will be on two powerful capabilities of Python: • Symbolic Algebra

• Analysis of Circuits using Laplace Transforms

Analysis of Circuits using Laplace Transforms

</div>
</div>
<div class="layoutArea">
<div class="column">
Consider the following figure (from page 274 of Horowitz and Hill):

</div>
</div>
<div class="layoutArea">
<div class="column">
C1 iR11R2 p

</div>
</div>
<div class="layoutArea">
<div class="column">
G C2

</div>
<div class="column">
o

(G-1)R

R

</div>
</div>
<div class="layoutArea">
<div class="column">
m

</div>
</div>
<div class="layoutArea">
<div class="column">
whereG=1.586andR1 =R2 =10kΩandC1 =C2 =10pF.Thisgivesa3dBButter- worth filter with cutoff frequency of 1/2πMHz.

</div>
</div>
<div class="layoutArea">
<div class="column">
The circuit equations are

</div>
</div>
<div class="layoutArea">
<div class="column">
Vm = Vo (1) G

V =V 1 (2) p 1 1+ jωR2C2

</div>
</div>
<div class="layoutArea">
<div class="column">
Vo = G(Vp −Vm) (3) Vi−V1 +Vp−V1 +jωC1(Vo−V1)=0 (4)

R1 R2

1

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
− +

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Solving for Vo in 3, we get

</div>
</div>
<div class="layoutArea">
<div class="column">
Vo = GV1 1

2 1+jωR2C2

</div>
</div>
<div class="layoutArea">
<div class="column">
Thus, Eq. 4 becomes an equation for V1 as follows: Vi􏰃1111G1 􏰄

</div>
</div>
<div class="layoutArea">
<div class="column">
R +V1 −R +R 1+jωRC −R +jωC121+jωRC −jωC1 =0 11222222

The term involving G will dominate, and so we obtain V1 ≈ 2Vi 1+ jωR2C2

G jωR1C1 Substituting back into the expression for Vo we finally get

Vo ≈ Vi (5) jωR1C1

We would like to solve this in Python and also get (and plot) the exact result. For this we need the sympy module.

2 Introduction to Sympy

Start isympy

<pre>    $ isympy
    IPython console for SymPy 1.4 (Python 3.7.3-64-bit) (ground types: gmpy)
    These commands were executed:
    &gt;&gt;&gt; from __future__ import division
    &gt;&gt;&gt; from sympy import *
    &gt;&gt;&gt; x, y, z, t = symbols(’x y z t’)
    &gt;&gt;&gt; k, m, n = symbols(’k m n’, integer=True)
    &gt;&gt;&gt; f, g, h = symbols(’f g h’, cls=Function)
    &gt;&gt;&gt; init_printing()
    Documentation can be found at https://docs.sympy.org/1.4/
</pre>
Normally we invoke ipython and import * from pylab. Instead we invoke sympy. It starts up with some pre-defined variables and the Ipython shell and also interactive plotting. Note: when coding these lines have to be included. The string inside the symbols command tells sympy how to print out expressions involving these symbols. For instance

&gt;&gt;&gt; x,y,z = symbols(’x y speed’) &gt;&gt;&gt; x=y+1/z

&gt;&gt;&gt; x

y+ 1

s peed

This is confusing, so just use the variable name for the symbol. One place where this is useful is for greek symbols:

&gt;&gt;&gt; w=symbols(’omega’) &gt;&gt;&gt; x=w*y+z

&gt;&gt;&gt; x

ω *y+z

Note that symbols are not python variables:

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<pre>    &gt;&gt;&gt; expr=x+1
    &gt;&gt;&gt; print(expr)
    x + 1 # a symbolic expression
    &gt;&gt;&gt; x=2  # reassignment of x
    &gt;&gt;&gt; print(expr)
    x + 1 # changing x did not change expr
    &gt;&gt;&gt; print(x)
    2     # did change x though
    &gt;&gt;&gt; expr=x+1
    &gt;&gt;&gt; print(expr)
    3     # now expr used current value of x - no longer a symbol
</pre>
This can lead to confusion, so be careful.

Rational functions of s are straightforward in sympy

<pre>    &gt;&gt;&gt; s,R2,C2=symbols(’s R_2 C_2’)
    &gt;&gt;&gt; h=-1/(1+s*R2*C2)
    &gt;&gt;&gt; print(h)
    -1/(C_2*R_2*s+1)
</pre>
&gt;&gt;&gt; h -1

C2R2s + 1

We will require to create some matrices. For example

&gt;&gt;&gt; M=Matrix([[1,2],[3,4]]) &gt;&gt;&gt; M

|1 2|

||

</div>
</div>
<div class="layoutArea">
<div class="column">
|3 4|

creates a 2 × 2 matrix containing

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰃1 2􏰄 34

</div>
</div>
<div class="layoutArea">
<div class="column">
If you define a matrix and a column vector you can multiply them as in Matlab using “*”

&gt;&gt;&gt; N=Matrix([5,6]) &gt;&gt;&gt; M*N

|17|

||

|39|

Suppose you want to solve Mx = N. Then we need to use the inverse of M

&gt;&gt;&gt; M.inv()*N |-4 |

||

|9/2|

Finally, to link to the Python we already know, we need to be able to generate numbers out of symbols. For that we use evalf.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
<pre>&gt;&gt;&gt; expr=sqrt(8)
&gt;&gt;&gt; expr
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
√

</div>
</div>
<div class="layoutArea">
<div class="column">
22

&gt;&gt;&gt; expr.evalf() 2.82842712474619

This works for single numbers. But what if we want to plot the magnitude response of a laplace transform expression? We use something called lambdify

<pre>    &gt;&gt;&gt; h=1/(s**3+2*s**2+2*s+1)
    &gt;&gt;&gt; import pylab as p
    &gt;&gt;&gt; ww=p.logspace(-1,1,21)
    &gt;&gt;&gt; ss=1j*w
</pre>
<pre>    &gt;&gt;&gt; f=lambdify(s,h,”numpy”)
    &gt;&gt;&gt; p.loglog(ww,abs(f(ss)))
    &gt;&gt;&gt; p.grid(True)
    &gt;&gt;&gt; p.show()
</pre>
What lambdify does is it takes the sympy function “h” and converts it into a python function which is then applied to the array ’ss’. This is much faster than iterating over the elements of ss and using evalf on the elements. Note that the first argument in lambdify, s, is whatever occurs in the definition of h. i.e., it is the symbolic variable inside h. In the loglog line, we actually replace ’s’ by a Numpy array, ’ss’.

3 Using Sympy to solve our circuit problem

We can solve directly for the exact result from Python. Let us define s = jω, and rewrite the equations in a matrix equation

 0 01−G1V10

−1100V0

 1+sRC  p =   22  

 0 −GG1Vm0 −R1 −R1 −sC1 R1 0 sC1 Vo Vi(s)/R1

122

This is the equation that we create and solve for now. The following function both defines the matrices and solves for the solution.

<pre>    from sympy import *
    import pylab as p
    def lowpass(R1,R2,C1,C2,G,Vi):
</pre>
<pre>      s=symbols(’s’)
      A=Matrix([[0,0,1,-1/G],[-1/(1+s*R2*C2),1,0,0], \
</pre>
<pre>        [0,-G,G,1],[-1/R1-1/R2-s*C1,1/R2,0,s*C1]])
      b=Matrix([0,0,0,Vi/R1])
</pre>
That defines the coefficient matrices. Note that I did not include Vi(s) in the vector b. I multiply it in later. However, I could have included it here as well. Now we solve for the solution.

V=A.inv()*b

This solution is in s space.

Now extract the output voltage. Note that it is the fourth element of the vector. The

logic of this line is explained below the code. 4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
<pre>      return (A,b,V)
</pre>
We now use this function to generate the plot for the values mentioned above. Note that the input voltage is a unit step function.

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>A,b,V=lowpass(10000,10000,1e-9,1e-9,1.586,1)
print(’G=%f’ % G)
Vo=V[3]
print(Vo)
</pre>
<pre>ww=p.logspace(0,8,801)
ss=1j*ww
hf=lambdify(s,Vo,’numpy’)
v=hf(ss)
p.loglog(ww,abs(v),lw=2)
p.grid(True)
</pre>
p.show()

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
100

10-1

10-2

10-3

100 101 102 103 104 105 106 107 108

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

1. 2.

</div>
<div class="column">
The Assignment

Obtain the step response of the circuit above. Use the signal toolbox of last week’s assignment.

The input is

vi(t) = 􏰆sin(2000πt)+cos􏰆2×106πt􏰇􏰇u0(t) Volts Determine the output voltage v0(t)

Consider the following circuit (from page 274 of Horowitz and Hill) 5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
Vi

</div>
<div class="column">
C1 C2 R3

</div>
<div class="column">
R1

−

G

+

</div>
</div>
<div class="layoutArea">
<div class="column">
(G-1)R R

</div>
</div>
<div class="layoutArea">
<div class="column">
Vo

</div>
</div>
<div class="layoutArea">
<div class="column">
ThevaluesyoucanuseareR1 =R3 =10kΩ,C1 =C2 =1nF,andG=1.586.

<ol start="3">
<li>Analyse the circuit using Sympy as explained above, i.e., create a function similar to the one defined above. For the same choice of components and gain, this circuit is a highpass filter.</li>
<li>Obtain the response of the circuit to a damped sinusoid (i.e., use suitable Vi). Use signal.lsim to simulate the output.</li>
<li>Obtain the response of the circuit to a unit step function. Do you understand the response? (Just define Vi to be 1/s)</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>

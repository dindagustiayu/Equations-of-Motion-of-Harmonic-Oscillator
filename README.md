[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)]()

# Second Order Differential Equations

In this unit, we move from first-order differential equations to __second-order differential equations__, that is, differential equations involving a second (but no higher) derivative. Examples of such equations are

<p align='center'>
    $$\frac{d^y}{dx^2} - 3\frac{dy}{dx} + 2y = 4e^x \ \mbox{and} \ 3\frac{d^2y}{dx^2} + y = x \ sin \ x$$
</p>

Second-order differential equations play a central role in the physical sciences. They are found, for example, in laws describing,
- mechanical system
- wave motion
- electric currents
- quantum phenomena.

To take a simple case, consider a particle of mass $m$ that moves in one dimension along the $x$-axis. At any given time $t$, the particle's position is $x(t)$, and its velocity and acceleration are given by the derivatives $dx/dt$ and $d^2x/dt$. There are no general laws for the positions or velocity of the particle, but there is a very important law for its acceleration: $\mbox{Newton's second law}$ tells us that

<p align='center'>
    $$ \mbox{mass} \times \mbox{acceleration} = \mbox{force}$$
</p>

which implies that
<p align='center'>
    $$m \frac{d^2x}{dt^2} = F \quad (1)$$
</p>

where $F$ is the force acting on the particle. The force need not be constant, and may vary with the position $x$ or the velocity $dx/dt$ of the particle. So, depending on the precise details, we get a second-order differential equation for $x$ as a function of $t$, and the solution of this equation tells us how the particle can move.

The system known as a _simple harmonic oscillator_ provides a good example. We consider the case where the force is proportional to the displacement from equilibrium, and take

<p align='center'>
    $$F = -kx$$
</p>

where $k$ is a positive constant. The negative sign in this equation ensures that the force always acts in a direction that tends to restore the particle to its equilibrium position. We get the differential equation
<p align='center'>
    $$m \frac{d^2 x}{dt^2} = -k x \quad (2)$$
</p>

Recalling that $k>0$ and $m<0$, we can also express this as 
<p align='center'>
    $$\frac{d^2 x}{dt^2} = -\omega^2 x \quad (3)$$
</p>

where $\omega = \sqrt{k/m}$ is a positive constant. Equation (3) is called the _equation of motion_ of a simple harmonic oscillator. It is a second-order differential equation whose solution tells us how the particle can move.

This equation may be decomposed into two first-order equations as follows:
<p align='center'>
    $$\begin{align} \frac{dx_1}{dt}= x_2, \\ \frac{dx_2}{dt}= \omega^2 x_1 \end{align}$$
</p>

where $x_1$ is identified with $x$ and $x_2$ with $dx/dt$.

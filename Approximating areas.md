#math #calc #ma1022 
We fill the underside of a curve with rectangles

Say we have a curve $f(x)=x^2+2$, to find the approximate area under it with three equally spaced sub intervals with a width of $\Delta x=\frac{b-a}{n}$, where n is three.
See: [[Partition]]

#### Dont fuck up fenceposts when doing left and right approximation
When using a right endpoint approximation, $\sum^{n}_{1} f(x_{i-1})$
When using a left endpoint approximation, $\sum^{n-1}_{0} f(x_{i})$

### In general
$A_{r}=R_{n}=\sum_{1}^nf(x_{i-1})\Delta x$
$A_{l}=R_{n}=\sum_{0}^{n-1}f(x_{i})\Delta x$
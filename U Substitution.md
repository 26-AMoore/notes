#calc  #math 
# Let  $u = g(x)$ and let $F(x)$ be an antiderivative of $f(x)$ then
$$\int f(g(x))g'(x)dx=\int f(u)du$$
$$\int f(u)=F(u)+C = F(g(x))+C$$
# For [[Definite Integral]]s suppose $g(x)$ and $g'(x)$ be continous on $[a,b]$ then
$$\int f(g(x))g'(x)dx=\int_{g(a)}^{g(b)}f(u)du$$

## Ex.1
$$\int x\sin(x^2)dx$$
$$u=x^2$$$$du=2x\ dx$$
$$\frac{du}{dx}=2x $$
$$\int x\sin(u)dx$$
$$\frac{1}{2}\int 2x\sin(u)dx$$
$$\frac{1}{2}\int \sin(u)du$$
$$-\frac{1}{2}*-\cos (u)+c$$
$$-\frac{1}{2}*-\cos(x^2)+c$$

## Ex.2
$$\int \frac{y^5}{(1-y^3)^{3/2}}dy$$
$$u = 1-y^3$$
$$du=3y^2dy$$
$$\frac{1}{3}du=y^2dy$$
$$\frac{1}{3}\int \frac{{1-u}}{u^{3/2}}du$$
## Ex.3
$$\int \frac{x}{\sqrt{ 1+x }}dx$$
$$u=1+x$$
$$du=dx$$
$$\int \frac{{u-1}}{u^{1/2}}du$$
## Ex.4
$$\int_{0}^1x^2(1+2x^3)^5dx$$
$$u = 1+2x^3$$
$$du=6x^2dx$$
$$\int u^5 \frac{1}{6}du$$
Solve for limits of [[Integrable|Integration]] via plugging into u
$$\int_{1}^3 u^5 \frac{1}{6} du$$
Alternatively, compute the [[Anti Derivatives]]
$$\frac{1}{36}u^6+C$$
$$\int_{0}^1 x^2(1+2x^3)^5dx=\frac{1}{36}[(1+2x^3)^6]^1_{0}$$

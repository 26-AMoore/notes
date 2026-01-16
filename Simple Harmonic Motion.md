#shm #physics 
# Springs and stuff
## $f(x)=kx$
k is spring constant, which is based on the spring

## Three distinct points in the movement
[[_resources/Simple Harmonic Motion/78ef2d0b3a99f55d40294b353f0422d7_MD5.jpg|Open: Pasted image 20260105102953.png]]
![[_resources/Simple Harmonic Motion/78ef2d0b3a99f55d40294b353f0422d7_MD5.jpg]]

### For [[Equilibrium Point]]
$$F_{w}=F_{s}$$
Even if there is motion, [[Acceleration]] is zero, but [[Velocity]] is at maximum
### For Above
$$F_{w}>F_{s}$$
$\sum F \ne 0$ is where velocity is zero but at max acceleration

### For Below
$$F_{w}<F_{s}$$
$\sum F \ne 0$ is where velocity is zero but at max acceleration

### Useful Equations
$$\sum F=-k \Delta x$$
$\Delta x$ is distance from [[Equilibrium Point]]
Force is the force on the hanging mass

$$T=2\pi \sqrt{ \frac{m}{k} }$$
T = [[Period]]
m is in kg

#### Position
$$x(t)=x_{m}\cos(\omega t+\phi)$$
$\phi$ phase angle (radians)
$x_{m}$ maximum amplitude
$\omega$ angular frequency (radians / second) NOT [[Angular Velocity]]
t = seconds

how to get omega
$$\omega=\frac{2\pi}{T}=2\pi f$$
T = period
f = frequency

#### Velocity (absolute- pay attention to direction)
$$v(t)=-\omega x_{m} \sin(\omega t+\phi)$$
if $\phi = 0$ then $v_{max} = \omega x_{max}$
#### Acceleration (absolute- pay attention to direction)
$$a(t)=-\omega^2x(t)$$
x(t) is position function

if $\phi = 0$ then $a_{max}=\omega^2x_{max}$

### Newton
$$\omega=\sqrt{ \frac{k}{m} } = \frac{2\pi}{T}$$
k is spring constant
m is mass

### Energy
Generally used for max amplitude
$$PE(t)=\frac{1}{2}kx^2=\frac{1}{2}kx_{m}^2\cos^2(\omega t+\phi)$$

$$KE(t)=\frac{1}{2}kx_{m}^2\sin^2(\omega t+\phi) = \frac{1}{2}mv^2$$

$$E=\frac{1}{2}kx_{m}^2$$

### All variables follow this pattern
[[_resources/Simple Harmonic Motion/ae03eb96148241751c2db2564e2f2d89_MD5.jpg|Open: Pasted image 20260107121613.png]]
![[_resources/Simple Harmonic Motion/ae03eb96148241751c2db2564e2f2d89_MD5.jpg]]
# For Pendulum
### Simple pendulum (rod is massless)
 $$T=2\pi \sqrt{ \frac{l}{g} }$$
l is length of string (m)
g is gravity
### General pendulum
uses special case
$$T=2\pi \sqrt{ \frac{I}{mgh} }$$
I is [[Rotational Inertia]] for the system
m is **total** mass of the system
h is distance to the [[Center Of Mass]] of the system (distance from pivot to COM)

For reasonable distances $s$ let
$$s \approx x \approx \theta R$$
s is arclength
R is from pivot point

# Special cases
### Angular [[Hookes Law Spring]]
Imagine twisting a bar
$$\tau=-\kappa\theta$$
$$T=2\pi\sqrt{ \frac{I}{\kappa} }$$
I is [[Rotational Inertia]] (Moment of Inertia)
$\kappa$ is rotational spring constant

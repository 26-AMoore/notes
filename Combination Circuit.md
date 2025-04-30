#electronics #physics 
# [[Circuits]] that are a mix of a [[Series Circuit]] and a [[Parallel Circuit]]
### To solve
1. Solve $R_{t}$
	1. Start "far away" from the battery in an area that is pure [[Series Circuit]] or [[Parallel Circuit]]
	2. Replace that section with a single [[Resistor]]
	3. Repeat
### Example
![Circuit](https://lh7-rt.googleusercontent.com/docsz/AD_4nXefvl0AMpMJAUc8ue_gY0EHn1Uw9M_0FEnDwR-ftoh4CiW0xwhJ72EhDqql26a8kHH3SUKseB-_mOyLtbF8Th0akfAf8S1UVy8qm2YSucGU6BKbsfk85iNUh9LA-MOX0AYEJUwVTmnupY9DyxLhU6mrjIE?key=So7PeCKFxfm6A8LI0LA_2A)
E = 24 V
R1 = 6 Ω
R2 = 2 Ω
R3 = 4 Ω
R4 = 8 Ω
#### $R_{3,4}$ is [[Series Circuit]]
$$R_{3,4} = R_{3}+R_{4}$$ $$R_{3,4}=12\Omega$$
#### $R_{1,3,4}$ is a [[Parallel Circuit]]
$$\frac{1}{R_{1,3,4}}=\frac{1}{R_{1}}+\frac{1}{R_{3,4}}$$
$$R_{1,3,4}=4\Omega$$
#### $R_{1,2,3,4}$ is a [[Series Circuit]]
$$R_{1,2,3,4} = R_{1,3,4} + R_{2}$$
$$R_{T}=6\Omega$$
#### Solving $I_{T}$
$$I_{T}=\frac{V_{t}}{R_{T}}$$
$$I_{T}=4A$$
#### Just going back now, Solve for [[Volts]] at each step


# Derivative of $e^{ax}$
$$\begin{array}{c}

f(x)=e^{ax}\\
\\
\begin{align}
f'(x)
&=\lim_{h\rightarrow0}{\frac{e^{a(x+h)}-e^{ax}}{h}}\\
&=\lim_{h\rightarrow0}{\frac{e^{ax}e^{ah}-e^{ax}}{h}}\\
&=\lim_{h\rightarrow0}{\frac{e^{ax}(e^{ah}-1)}{h}}\\
&=e^{ax}\cdot\lim_{h\rightarrow0}{\frac{e^{ah}-1}{h}}\\
&=e^{ax}\cdot\lim_{h\rightarrow0}[{\frac{1}{h}}\cdot{\stackrel{\infty}{\sum_{k=1}}\frac{a^kh^k}{k!}}]\\
&=e^{ax}\cdot\lim_{h\rightarrow0}[{\stackrel{\infty}{\sum_{k=1}}\frac{a^kh^k}{k!\cdot{h}}}]\\
&=e^{ax}\cdot\lim_{h\rightarrow0}[{\stackrel{\infty}{\sum_{k=1}}\frac{a^kh^{k-1}}{k!}}]\\
&=
e^{ax}\cdot(
\lim_{h\rightarrow0}[\frac{a^1h^0}{1!}]+
\lim_{h\rightarrow0}[{\stackrel{\infty}{\sum_{k=2}}\frac{a^kh^{k-1}}{k!}}]) \\

&=e^{ax}\cdot(a+0)\\
&=ae^{ax}\\
\end{align}

\end{array}
$$
# Derivative of $e^x$
$$
\begin{array}{c}

f(x)=e^x\\
\\
\begin{align}
f'(x)&=\lim_{h\rightarrow{0}}\frac{e^{x+h}-e^x}{h}\\
&=\lim_{h\rightarrow{0}}\frac{e^xe^h-e^x}{h}\\
&=\lim_{h\rightarrow{0}}\frac{e^x(e^h-1)}{h}\\
&=e^x\cdot\lim_{h\rightarrow{0}}\frac{e^h-1}{h}\\
&=e^x\cdot\lim_{h\rightarrow{0}}\frac{(1 + \stackrel{\infty}{\sum_{k=1}}\frac{h^k}{k!})-1}{h}\\
&=e^x\cdot\lim_{h\rightarrow{0}}\frac{\stackrel{\infty}{\sum_{k=1}}\frac{h^k}{k!}}{h}\\
&=e^x\cdot\lim_{h\rightarrow{0}}({\stackrel{\infty}{\sum_{k=1}}\frac{h^k}{k!\cdot{h}}})\\
&=e^x\cdot\lim_{h\rightarrow{0}}({\stackrel{\infty}{\sum_{k=1}}\frac{h^{k-1}}{k!}})\\
&=e^x\cdot\lim_{h\rightarrow{0}}({\frac{h^0}{1!}+\stackrel{\infty}{\sum_{k=2}}\frac{h^{k-1}}{k!}})\\
&=e^x\cdot(1+0)\\
&=e^x
\end{align}

\end{array}
$$
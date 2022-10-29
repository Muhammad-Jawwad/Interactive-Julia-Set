# Interactive-Julia-Set

<p align="center"><img src="julia-set.png"></p>

This is a simple program that generates a Julia Set. The Julia Set is a fractal that is generated by iterating a function over a complex plane. If we define a function,

$$ f_{c}(z)=z^{2}+c $$

then the Julia set $J(f_c)$ will be defined as,

$$ J(f_c):=\{z\in\mathbb{C}\mid \forall n\in\mathbb{N},\mid f^n_c(z)\mid\le 2\} $$

where, $f^n_c(z)$ is the $n$ th iteration of the function $f_c$.

# Note

This code was written for a submission for a weekly render fair arranged by my professor of CS-440 Computer Graphics.

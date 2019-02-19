---
layout: post
title:  "Notes: The Zeeman and Paschen-Back Effects"
date:   2019-01-28
excerpt: "Just about everything you'll need to style in the theme: headings, paragraphs, blockquotes, tables, code blocks, and more."
tag:
- polarization 
- magnetic field
comments: true
---

# Hamiltonian

The total Hamiltonian \\( H \\) of an atomic system in a magnetic field is given by

\\[ H=H_0+H_B, \\]

where $$ H_0 $$ and $$ H_B $$ are the unperturbed and magnetic Hamiltonians, respectively. The magnetic Hamiltonian $$ H_B $$ is given by 

\\[ H_B=\frac{e_0h}{4\pi mc}(\vec{L}+2\vec{S})\cdot\vec{B}+\frac{e_0^2}{8mc^2}(\vec{B}\times\vec{r})^2.v\\]

The second term is the so called diamagnetic term, and not important except for extremely large fields. If the diamagnetic term is neglected, the magnetic Hailtonian can be written as

\\[ H_B=\frac{e_0h}{4\pi mc}(\vec{L}+2\vec{S})\cdot\vec{B}=\mu_0(\vec{L}+2\vec{S})\cdot\vec{B}. \\]

# Russell–Saunders Coupling

In light atoms, electron spins \\( s_i \\) interact among themselves so they combine to form a total spin angular momentum \\( S \\). The same happens with orbital angular momenta \\( l_i \\), forming a total orbital angular momentum \\( L \\). The interaction between the quantum numbers \\( L \\) and \\( S \\) is called Russell–Saunders coupling or LS coupling. Then \\(S\\) and \\( L \\) couple together and form a total angular momentum \\( J \\).

# Landé Interval Rule

If the interaction between orbit and spin angular momenta of an electron is weak (LS coupling), the interval between successive energy levels is proportional to the total angular momentum values \\( J \\).

\\[ E_{\beta LS}(J)-E_{\beta LS}(J-1)=\zeta(\beta LS)J, \\] 

where \zeta(\beta LS) is a constant for the energy level.


# Zeeman Effect

In the weak external magnetic fields, the interaction between the orbital \\( (\vec{L}) \\) and spin \\( (\vec{S}) \\) angular momenta is desctibed by LS coupling.
The matrix element is given by 
    
\\[ <\alpha JM \| H_B \| \alpha JM'>=\mu_0B<\alpha JM \| (\vec{J}+\vec{B})\cdot\vec{b} \| \alpha JM'>, \\]

where \\( \vec{b} \\) is a unit vector in the magnetic field direction.
In the spherical components, we have

\\[ \begin{split}
<\alpha JM \| H_B \|\alpha JM'>=&\mu_0B\sum\limits_{q}(-1)^{J+M+q+1}\sqrt{2J+1} 
\begin{pmatrix} J& J& 1 \\\ -M& M'& q\end{pmatrix} \\\ 
&\times(\sqrt{J(J+1)}+<\alpha J\|\|\vec{S}\|\|\alpha J>)b_{-q} 
\end{split}. \\]

if one chooses the magnetic field direction as the quantization axis, the only non-zero component of the unit vector \\( \vec{b} \\) is \\( b_0=1 \\). Therefore

\\[ <\alpha JM\|H_B\|\alpha JM'>=\mu_0Bg_{LS}M\delta_{MM'}, \\]

where \\( g_{LS} \\) is the Landé factor. 
While the eigenvalues are given by

\\[ E_{\alpha J}+\mu_0g_{LS}BM. \\]

# Incomplete Paschen-Back Effect

When the external magnetic field is sufficiently strong to disrupt the LS coupling (the splitting of the \\( J \\) level is comparable with the energy separation between different \\( J \\) levels ), the splitting of the atomic levels is called Paschen-Back effect.

\\[ \begin{split}
\lt\alpha JM \| H_B \|\alpha'J'M'\gt=&\mu_0B\sum\limits_{q}(-1)^{J'+M+q+1}\sqrt{2J+1} 
\begin{pmatrix} J& J'& 1 \\\ -M& M'& q\end{pmatrix} \\\ 
&\times\[\sqrt{J(J+1)}\delta_{\alpha\alpha'}\delta_{JJ'}+\lt\alpha J\|\|\vec{S}\|\|\alpha'J'\gt\]b_{-q} 
\end{split}. \\]

When the quantization axis is in the magnetic field direction,

\\[ \begin{split}
\lt\alpha JM \| H_B \|\alpha'J'M'\gt=&\mu_0B\[M\delta_{\alpha\alpha'}\delta_{JJ'}+(-1)^{J'+M+q+1}\sqrt{2J+1} 
\begin{pmatrix} J& J'& 1 \\\ -M& M'& q\end{pmatrix} \\\ 
&\times[\sqrt{J(J+1)}\delta_{\alpha\alpha'}\delta_{JJ'}+\lt\alpha J\|\|\vec{S}\|\|\alpha'J'\gt\]\delta_{MM'}
\end{split} \\]



# Complete Paschen-Back Effect

When the external magnetic field is sufficiently strong to disrupt the LS coupling, the energy eigenvectors gradually evolve from the form \\( \|\beta LSJM> \\) to the form \\( \|\beta LSM_LM_S> \\). The eigenvalues are given by 

\\[ <\beta LSM_LM_S\|H_B\|\beta LSM_LM_S>=\mu_0B(M_L+2M_S). \\]

# Summary

The ratio between the Zeeman splitting and the fine-structure energy is defined by

\\[ \gamma=\frac{\mu_0B}{\zeta}. \\]

Then we have:

\\( \gamma\ll 1 \\), Zeeman effect regime

\\( \gamma\approx 1 \\), Incomplete Paschen-Back effect regime

\\( \gamma\gg 1 \\), Complete Paschen-Back effect regime

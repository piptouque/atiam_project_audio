
### Some thoughts

Our discretised Gaussian $(g_k)_{k \in [|0, n|]}$, $\sim N(\mu_d, \sigma_d)$.

We note $g_0 = \epsilon_n$,
with $\epsilon_n \to_{n \to \infty} 0, \epsilon_n \neq 0$.

$$
\begin{equation}
    \begin{aligned}
        e^{-\frac{(\frac{n}{2} - \mu_d)^2}{2\sigma_d^2}} &= \frac{1}{\sigma_d \sqrt{2 \pi}}
        \\
        \mu_d &= \frac{n}{2} \pm \sigma_d \sqrt{|\ln(\sigma_d^2 2 \pi)|},
    \end{aligned} 
    \\
\end{equation}


\\
\\

\begin{equation}
    \begin{aligned}
        e^{-\frac{(\frac{n}{2} - \mu_d)^2}{2\sigma_d^2}} 
            &= \frac{e^{-\frac{\mu_d^2}{2\sigma_d^2}}}{\sigma_d}
        \\
        \sigma_d^2 &=  \frac{n(n - 4 \mu_d)}{8 |\ln(\epsilon_n)|}.
    \end{aligned} 
    \\
\end{equation}
$$

With a limited development at order $0$ for $\sigma_d \approx 0$ we find:
$$
\sigma_d \sqrt{|\ln(\sigma_d^2 2 \pi)|} = \mathrm{O}(\sigma_d)
$$
So that:
$$
\mu_d \approx \mu_a = \frac{n}{2},
$$

Now let's just assume that $\epsilon_n = \mathrm{O}(n^3)$,
because it makes sense __dubious claim here__.

We then have:
$$
\sigma_d^2 = \frac{n^2}{8 \ln(\frac{1}{\epsilon_n})} = \mathrm{O}(\frac{1}{n})
$$
So yeah, it works.
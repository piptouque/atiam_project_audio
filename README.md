
### Some thoughts

Our discretised Gaussian $(g_k)_{k \in [|0, n|]}$, $\sim N(\mu_d, \sigma_d)$.

With $g_0 = \epsilon$,

$$
\begin{equation}
    \begin{aligned}
        e^{-\frac{(\frac{n}{2} - \mu_d)^2}{2\sigma_d^2}} &= \frac{1}{\sigma_d \sqrt{2 \pi}}
        \\
        e^{-\frac{(\frac{n}{2} - \mu_d)^2}{2\sigma_d^2}} 
            &= \frac{e^{-\frac{\mu_d^2}{2\sigma_d^2}}}{\sigma_d}
    \end{aligned} 
    \\
\end{equation}

\begin{equation}
    \begin{aligned}
        \mu_d &= \frac{n}{2} \pm \sigma_d \sqrt{\ln(\sigma_d^2 2 \pi)}
        \\
        \sigma_d^2 &=  \frac{n(n - 4 \mu_d)}{8 \ln(\epsilon)}
    \end{aligned} 
    \\
\end{equation}
$$

on approxime $\mu_d \approx \mu_a = \frac{n}{2}$ car c'est ce que l'on veut.

    > Au pifomètre.

On a alors $\sigma_d^2 \approx \sigma_a^2 = \frac{n^2}{8 \ln(\frac{1}{\epsilon}}$.
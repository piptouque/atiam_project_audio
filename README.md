
### Normalising a gaussian

> Not actually used, doesn't work.

Our discretised Gaussian $(g_k)_{k \in [|0, n|]}$, $\sim N(\mu_d, \sigma_d^2)$.

We want:
$$
\begin{equation}
    \begin{aligned}
        g_{\frac{n}{2}} &= \frac{1}{\sigma_d \sqrt{2 \pi}},
        \\
        g_0 &= \frac{\epsilon_n}{\sigma_d \sqrt{2 \pi}}.
    \end{aligned}
\end{equation}
$$

With $\epsilon_n \neq 0$ chosen such that $\epsilon_n \to_{n \to \infty} 0$.

$$
\begin{equation}
    \begin{aligned}
        e^{-\frac{(\frac{n}{2} - \mu_d)^2}{2\sigma_d^2}} &= 1,
        \\
        e^{-\frac{\mu_d^2}{2\sigma_d^2}} &= \epsilon_n.
    \end{aligned} 
\end{equation}
$$

We find:
$$
\begin{equation}
    \begin{aligned}
        \mu_d &= \frac{n}{2},
        \\
        \sigma_d^2 &= \frac{n^2}{4 \ln(\epsilon_n)}.
    \end{aligned}
\end{equation}
$$

We can then normalise the gaussian with $(\mu_d, \sigma_d^2)$.
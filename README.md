# The Black&ndash;Scholes Model

Deck 06 of the [Paul Wilmott Introduces Quantitative Finance &mdash; Companion Series](https://github.com/BrendanJamesLynskey/Wilmott_QF_Hub).

**Live presentation:** https://brendanjameslynskey.github.io/Wilmott_QF_06_Black_Scholes_Model/

A guided tour of chapters 6 and 7 of *Paul Wilmott Introduces Quantitative
Finance* (2nd edition, Wiley, 2007) &mdash; from a lognormal underlying and
It&ocirc;'s lemma to the most famous PDE in finance and its closed-form
solution.

## What's inside

- The setup: $V(S,t)$ and geometric Brownian motion $dS = \mu S\,dt + \sigma S\,dW$
- The delta-hedged portfolio $\Pi = V - \Delta S$
- It&ocirc;'s lemma applied to $V$, the choice $\Delta = V_S$, and why $\mu$ disappears
- No-arbitrage forces $d\Pi = r\Pi\,dt$
- The Black&ndash;Scholes PDE: $V_t + \tfrac{1}{2}\sigma^2 S^2 V_{SS} + r S V_S - r V = 0$
- Final and boundary conditions for calls, puts, binaries; put&ndash;call parity from PDE linearity
- The BS assumptions &mdash; what they bought us, where they bite
- Reduction to the heat equation and the closed-form European call $C = S N(d_1) - K e^{-rT} N(d_2)$
- Three independent derivations (PDE, martingale, binomial limit) agreeing on the same price
- **Interactive option value-surface viewer** &mdash; live BS formula heatmap of $V(S,t)$ with a family of curves $V(S,t)$ for several times, sliders for $K, T, \sigma, r$, and a call/put toggle

Companion to chapters 6 and 7 of:

> Wilmott, P. (2007). *Paul Wilmott Introduces Quantitative Finance,
> Second Edition.* John Wiley &amp; Sons. ISBN 978-0-470-31958-1.

Single-page HTML, KaTeX-rendered maths, no build step. Open `index.html` directly.

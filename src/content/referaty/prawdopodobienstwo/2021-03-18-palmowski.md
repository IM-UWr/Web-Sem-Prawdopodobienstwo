---
tytul: "On the renewal theorem for maxima on trees"
prelegent: "Zbigniew Palmowski"
afiliacja: "Politechnika Wrocławska"
termin: "2021-03-18T12:15"
sala: "zoom"
jezyk: "en"
opublikowany: true
---

We consider the distributional fixed-point equation:

$$
R \stackrel{\mathcal{D}}{=} Q \vee \left( \bigvee_{i=1}^N C_i R_i \right),
$$

where the $\{R_i\}$ are i.i.d.~copies of $R$, independent of the vector
$(Q, N, \{C_i\})$, where $N \in \mathbb{N}$, $Q, \{C_i\} \geq 0$ and
$P(Q > 0) >0$. By setting $W = \log R$, $X_i = \log C_i$, $Y = \log Q$
it is equivalent to the high-order Lindley equation

$$
W \stackrel{\mathcal{D}}{=} \max\left\{ Y, \, \max_{1 \leq i \leq N}
(X_i + W_i) \right\}.
$$

It is known that under Kesten assumptions,
$$P(W > t) \sim H e^{-\alpha t}, \qquad t \to \infty,$$
where $\alpha>0$ solves the Cram\'er-Lundberg equation
$E \left[  \sum_{j=1}^N C_i ^\alpha \right] = E\left[ \sum_{i=1}^N
e^{\alpha X_i} \right] = 1$.
The main goal of this paper is to provide an explicit representation for
$P(W > t)$, which can be directly connected to the underlying weighted
branching process where $W$ is constructed and that can be used to
construct unbiased and strongly efficient estimators for all $t$.
Furthermore, we show how this new representation can be directly
analyzed using Alsmeyer's Markov renewal theorem, yielding an
alternative representation for the constant $H$. We provide numerical
examples illustrating the use of this new algorithm.
This is a joint work with Bojan Basrak, Michael Conroy and Mariana
Olvera-Cravioto.

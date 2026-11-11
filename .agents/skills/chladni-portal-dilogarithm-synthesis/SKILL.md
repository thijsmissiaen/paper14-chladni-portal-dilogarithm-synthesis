---
name: chladni-portal-dilogarithm-synthesis
description: Scientific knowledge skill for Paper XIV containing the canonical Wronskian normalization, 50%-50% Green-Dirichlet-Neumann nodal chamber equipartition, Craven-Csordas-Smith / Ki-Kim critical-point index connection, self-dual Davenport-Heilbronn defects, and exact factorized vs. additive Euler dilogarithm Li_2(2*theta) prime-simplex integrals (showing that the true additive semiprime weight collapses to eta_add^(2)(1/6) = 0.150604 < 1/2).
---

# Nodal Chamber Equipartition, Critical-Point Index & Dilogarithm Integrals Skill (Paper XIV)

Activate this skill when working with **Paper XIV** ("Nodal Chamber Equipartition, Critical-Point Index Dichotomy, and Weighted Prime-Simplex Dilogarithm Integrals for Riemann's $\Xi$ Function") so canonical normalizations, corrected polylogarithmic identities, and critical red-team scope boundaries are preserved.

## 1. Canonical Normalization & Coordinate Dictionary

- **Spectral coordinates:** $s = \sigma + \mathrm{i}t = \frac{1}{2} + d + \mathrm{i}t$, rotated coordinate $z = -\mathrm{i}(s - \frac{1}{2}) = t - \mathrm{i}d$ ($d \ge 0$).
- **Canonical completed zeta integral:**

$$\Xi(z) = 8\int _ 0^\infty \Phi(u)\cos(2zu) \mathrm{d}u, \qquad \Phi(u) = \sum _ {n=1}^\infty \bigl(2\pi^2 n^4 \mathrm{e}^{9u} - 3\pi n^2 \mathrm{e}^{5u}\bigr)\exp\bigl(-\pi n^2 \mathrm{e}^{4u}\bigr) > 0 \quad (u \in \mathbb{R}).$$

- **Harmonic decomposition:** $\Xi(t - \mathrm{i}d) = R(d,t) + \mathrm{i}I(d,t)$ with $R(-d,t)=R(d,t)$ and $I(-d,t)=-I(d,t)$.
- **Canonical transverse Wronskian:**

$$W(d,t) := \frac{1}{2}\partial _ d\lvert \Xi(t-\mathrm{i}d)\rvert^2 = R \partial _ d R + I \partial _ d I = R \partial _ t I - I \partial _ t R = d \widetilde{W}(d,t) = 16\int _ 0^\infty y\sinh(2dy) \mathcal{K} _ \Phi(y,t) \mathrm{d}y,$$

  where $\mathcal{K} _ \Phi(y,t) = 2\int _ 0^\infty \Phi(\frac{y+r}{2})\Phi(\frac{y-r}{2})\cos(2tr) \mathrm{d}r$ and $\lim _ {d\to 0^+} \widetilde{W}(d,t) = (\Xi'(t))^2 - \Xi(t)\Xi''(t) =: c _ 1(t)$.
- **Logarithmic height scales:** $N _ \star(t) = \sqrt{t/(2\pi)}$, $L(t) := \ln(t/(2\pi)) = 2\ln N _ \star(t)$, $\alpha _ n := (\ln n)/L(t) \in (0,1/2]$, $u _ n := 2\alpha _ n = (\ln n)/\ln N _ \star(t) \in (0,1]$, $\tau := 2\theta \in (0,1/2)$, and $\omega _ n(t) := \ln(N _ \star(t)/n) = (\ln N _ \star(t))(1 - u _ n)$.

---

## 2. Nodal Geometry, Critical-Point Index & Global Caveats (Section 2)

1. **Tangential Monotonicity & Curvature Conservation (Theorem 2.1):** Along any regular arc $\Gamma \subset \lbrace I(d,t)=0\rbrace$, $\mathrm{d}R/\mathrm{d}s = \pm\lvert \nabla I\rvert = \pm\lvert F'\rvert$ and $\partial _ n R = 0$. At any simple real root $\tau _ {\star}$ of $F'$ ($F(\tau _ {\star})\ne 0$),

$$\frac{1}{2}\frac{\mathrm{d}^2}{\mathrm{d}d^2}\Bigl[R\bigl(d,\tau _ {\star}(d)\bigr)^2\Bigr] _ {d=0} = -\frac{1}{2}\frac{\mathrm{d}^2}{\mathrm{d}t^2}\Bigl[F(t)^2\Bigr] _ {t=\tau _ {\star}} = -F(\tau _ {\star})F''(\tau _ {\star}) = c _ 1(\tau _ {\star}).$$

2. **Connection to Craven–Csordas–Smith (1987) and Ki–Kim (2000) Index Theory (Section 2 & Theorem 2.4):** An off-critical zero on a critical-line nodal branch $\Gamma _ {\star}$ requires either **Case I** ($c _ 1(\tau _ {\star}) \le 0$ on $d=0$, certified across the first $5$ off-critical zeros of the self-dual Davenport–Heilbronn function $\Xi _ {\mathrm{DH}}$) or **Case II** ($F'(z _ c)=0$ on $\Gamma _ {\star}$ in $d>0$). These two cases correspond to the real-defect count $\mathcal{D} _ {\mathbb{R}}(F)$ and nonreal derivative zero count $Z _ {\mathbb{C}}(F')$ in the Craven–Csordas–Smith / Ki–Kim index inequality.
3. **Mandatory Red-Team Scope Caveats (Remarks 2.2–2.3 & Theorem 2.4(b)):**
   - **No codimension-three genericity proof:** In $1$-parameter families such as de Bruijn–Newman heat flow $H _ \lambda(z)$, $\lbrace I _ \lambda = \partial _ d I _ \lambda = \partial _ t I _ \lambda = 0\rbrace$ is $3$ equations in $3$ unknowns $(d _ c,t _ c,\lambda)$, so interior saddle collisions occur generically at critical $\lambda$; parameter counting proves nothing for fixed $\Xi(z)$.
   - **Unbounded hairpin components:** The bounded-domain Maximum Principle does not exclude unbounded hairpin components of $\lbrace I=0\rbrace$ coming from $d = +\infty$; controlling large $d$ for $\Xi$ requires Euler-product non-vanishing on $\sigma > 1$ and Stirling / Phragmén–Lindelöf argument monotonicity.
   - **Speiser difficulty:** Assuming $\Xi'(t-\mathrm{i}d) \ne 0$ for $d > 0$ is itself comparable in logical strength to the Riemann Hypothesis (Speiser 1934).

---

## 3. Chamber Equipartition & Exact Dilogarithm Laws (Sections 3–4)

1. **Exact 50%–50% Green–Dirichlet–Neumann Equipartition (Theorem 3.1):** On every regular chamber $\Omega _ k(d _ 0)$,

$$\int _ {\tau _ k(d _ 0)}^{\tau _ {k+1}(d _ 0)} R(d _ 0,t) \partial _ d R(d _ 0,t) \mathrm{d}t \equiv \int _ {\tau _ k(d _ 0)}^{\tau _ {k+1}(d _ 0)} I(d _ 0,t) \partial _ d I(d _ 0,t) \mathrm{d}t \equiv \iint _ {\Omega _ k(d _ 0)} \bigl\lvert F'(t - \mathrm{i}d)\bigr\rvert^2 \mathrm{d}d \mathrm{d}t = \frac{1}{2}\mathcal{W} _ {\Omega _ k}(d _ 0) > 0,$$

   and along $\Gamma _ k$, $\tau _ k'(d) \equiv R \partial _ t R / W(d,\tau _ k(d))$ and $\frac{\mathrm{d}}{\mathrm{d}d}(\frac{1}{2}R^2) \equiv W(d,\tau _ k(d))(1 + \tau _ k'(d)^2)$ (Theorem 3.2).
2. **Corrected Factorized vs. True Additive Semiprime $\mathrm{Li} _ 2(2\theta)$ Integrals (Theorems 4.2 & 4.3):** With $\tau = 2\theta \in (0,1/2)$ and $\mathcal{M} _ {\mathrm{sq}}^{(p)}(\theta) = (I _ p(\theta))^2$:
   - $\mathcal{M} _ {\mathrm{tri}}^{(0)}(\theta) = \ln^2\tau + 2 \mathrm{Li} _ 2(\tau) - \frac{\pi^2}{6}$ ($\eta^{(0)}(1/6) = 0.2439550996$)
   - $\mathcal{M} _ {\mathrm{tri},\mathrm{fac}}^{(1)}(\theta) = \mathcal{M} _ {\mathrm{tri}}^{(0)}(\theta) - 2(1-\tau)\ln(\frac{1-\tau}{\tau}) + (\frac{5}{2} - \tau)(1-2\tau)$ ($\eta _ {\mathrm{fac}}^{(1)}(1/6) = 0.4955987356$)
   - $\mathcal{M} _ {\mathrm{tri},\mathrm{fac}}^{(2)}(\theta) = \mathcal{M} _ {\mathrm{tri}}^{(0)}(\theta) - (1-\tau)(3-\tau)\ln(\frac{1-\tau}{\tau}) + (\frac{31}{8} - \frac{13}{4}\tau + \tau^2)(1-2\tau)$ ($\eta _ {\mathrm{fac}}^{(2)}(1/6) = 0.6768906167$)
   - **True additive semiprime Wronskian weight $(1-u-v)^p$:**
     - $\mathcal{M} _ {\mathrm{tri},\mathrm{add}}^{(1)}(\theta) = \mathcal{M} _ {\mathrm{tri}}^{(0)}(\theta) - 2(1-\tau)\ln(\frac{1-\tau}{\tau}) + 2(1-2\tau)$ ($\eta _ {\mathrm{add}}^{(1)}(1/6) = 0.1978366884 < 1/2$)
     - $\mathcal{M} _ {\mathrm{tri},\mathrm{add}}^{(2)}(\theta) = \mathcal{M} _ {\mathrm{tri}}^{(0)}(\theta) - (1-\tau)(3-\tau)\ln(\frac{1-\tau}{\tau}) + (\frac{7}{2} - 2\tau)(1-2\tau)$ ($\eta _ {\mathrm{add}}^{(2)}(1/6) = 0.1506038202 < 1/2$)
     - Exact polynomial deficit: $\mathcal{M} _ {\mathrm{tri},\mathrm{fac}}^{(2)}(\theta) - \mathcal{M} _ {\mathrm{tri},\mathrm{add}}^{(2)}(\theta) = \frac{1}{8}(1-2\tau)^2(3 - 4\tau) > 0$. This refutes any mean-field link from simplex weighting to pointwise $W(d,t) > 0$.

## 4. Verification Command

```bash
python scripts/verify_paper14_portal_dilogarithm_synthesis.py
```

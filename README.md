# Nodal Chamber Equipartition, Critical-Point Index Dichotomy, and Weighted Prime-Simplex Dilogarithm Integrals for Riemann's $\Xi$ Function

**Author:** Thijs Missiaen ([thijs.missiaen@gmail.com](mailto:thijs.missiaen@gmail.com))  
**Affiliation:** Independent Researcher, Belgium  
**ORCID:** [0009-0007-3678-0810](https://orcid.org/0009-0007-3678-0810)  
**Date:** November 2026  
**Manuscript:** [`paper/paper14_portal_dilogarithm_synthesis.pdf`](paper/paper14_portal_dilogarithm_synthesis.pdf) (16 pages, AMS-LaTeX / Tectonic `pdfTeX`)

> [!IMPORTANT]
> **Mathematical Context and Scope Summary**
>
> Decomposing Riemann's completed zeta function $\Xi(t - \mathrm{i}d) = R(d,t) + \mathrm{i}I(d,t)$ ($d \ge 0$) into conjugate harmonic fields separates unconditional harmonic identities inside a nodal chamber $\Omega _ k(d _ 0)$ from global critical-point obstacles and Prime-Number-Theorem simplex integrals:
> 1. **Local Nodal Dichotomy and Critical-Point Index Theory (Section 2, Theorems 2.1 and 2.4):** Along any bounded nodal arc $\Gamma _ {\star} \subset \lbrace I(d,t)=0\rbrace$ meeting $d=0$ at a simple real critical point $\tau _ {\star}$, $\mathrm{d}R/\mathrm{d}s = \pm \lvert \Xi'\rvert$ and $\frac{1}{2}\partial _ d^2[R^2] _ {d=0} = -\Xi(\tau _ {\star})\Xi''(\tau _ {\star}) = c _ 1(\tau _ {\star})$. Within the critical-point index framework of Craven, Csordas, and Smith (1987) and Ki and Kim (2000), an off-critical zero on $\Gamma _ {\star}$ requires either **Case I** ($c _ 1(\tau _ {\star}) \le 0$ on $d=0$, certified across the first five off-critical zeros of the self-dual Davenport–Heilbronn function $\Xi _ {\mathrm{DH}}$) or **Case II** (an interior critical point $\Xi'(z _ c)=0$ in $d>0$), whereas unbounded hairpin components require Phragmén–Lindelöf control at infinity and ruling out $\Xi'=0$ on $d>0$ is comparable in difficulty to the Riemann Hypothesis (Speiser 1934).
> 2. **Unconditional 50%–50% Green–Dirichlet–Neumann Chamber Equipartition (Section 3, Theorems 3.1 and 3.2):** Under canonical normalization $W(d,t) = \frac{1}{2}\partial _ d\lvert \Xi(t-\mathrm{i}d)\rvert^2 = R \partial _ d R + I \partial _ d I = d \widetilde{W}(d,t)$, homogeneous Dirichlet ($I=0$) and Neumann ($\partial _ n R = 0$) wall conditions enforce $\int R \partial _ d R \mathrm{d}t \equiv \int I \partial _ d I \mathrm{d}t \equiv \iint _ {\Omega _ k} \lvert \Xi'\rvert^2 \mathrm{d}d \mathrm{d}t = \frac{1}{2}\mathcal{W} _ {\Omega _ k}(d _ 0) > 0$, together with Wronskian–slope reciprocity $\tau _ k'(d) \equiv R \partial _ t R / W(d,\tau _ k(d))$.
> 3. **Factorized vs. Additive Prime-Simplex Dilogarithm Integrals (Section 4, Theorems 4.2–4.4):** As a standalone Prime-Number-Theorem simplex calculation ($\tau = 2\theta \in (0,1/2){}$), factorized weights $(1-u)^2(1-v)^2$ give $\eta _ {\mathrm{fac}}^{(2)}(1/6) = 0.676891 > 1/2$, whereas the true additive semiprime Wronskian weight $(1-u-v)^2$ drops to $\eta _ {\mathrm{add}}^{(2)}(1/6) = 0.150604 < 1/2$ with exact polynomial deficit $\frac{1}{8}(1-2\tau)^2(3-4\tau) > 0$, showing that simplex mode weighting has no mean-field implication for pointwise $W(d,t) > 0$.

## Abstract

We study the Cauchy–Riemann nodal geometry and prime-simplex integrals of Riemann's completed zeta function $\Xi(t-\mathrm{i}d)=R(d,t)+\mathrm{i}I(d,t)$ ($d\ge 0$). First, we place the local dichotomy along bounded nodal arcs of $\lbrace I=0\rbrace$ within the critical-point index theory of Craven, Csordas, and Smith (1987) and Ki and Kim (2000): an off-critical zero on a critical-line nodal branch requires either a critical-line Laguerre defect $c _ 1(\tau _ {\star})=-\Xi(\tau _ {\star})\Xi''(\tau _ {\star})\le 0$ (certified for the first five off-critical zeros of the self-dual Davenport–Heilbronn function $\Xi _ {\mathrm{DH}}$) or an interior critical point $\Xi'(z _ c)=0$ in $d>0$, while unbounded hairpin components require Phragmén–Lindelöf control and ruling out $\Xi'=0$ on $d>0$ is comparable in difficulty to the Riemann Hypothesis. Second, Green's first identity proves an unconditional 50%–50% Dirichlet–Neumann chamber equipartition

$$\int _ {\tau _ k(d _ 0)}^{\tau _ {k+1}(d _ 0)} R \partial _ d R \mathrm{d}t \equiv \int _ {\tau _ k(d _ 0)}^{\tau _ {k+1}(d _ 0)} I \partial _ d I \mathrm{d}t \equiv \iint _ {\Omega _ k(d _ 0)} \lvert \Xi'(t-\mathrm{i}d)\rvert^2 \mathrm{d}d \mathrm{d}t = \frac{1}{2}\mathcal{W} _ {\Omega _ k}(d _ 0) > 0$$

coupled with Wronskian–slope reciprocity $\tau _ k'(d)\equiv R \partial _ t R / W(d,\tau _ k(d))$. Third, exact Euler dilogarithm $\mathrm{Li} _ 2(2\theta)$ integrals show that whereas factorized weights give $\eta _ {\mathrm{fac}}^{(2)}(1/6)=0.676891>1/2$, the true additive semiprime Wronskian weight $(1-u-v)^2$ drops to $\eta _ {\mathrm{add}}^{(2)}(1/6)=0.150604<1/2$.

---

## Key Analytical Results & Certified Benchmarks

| Section | Result | Core Analytical Identity / Finding | Certified Value (`mp.dps = 65`, `mp.iv.dps = 35`) |
| :--- | :--- | :--- | :--- |
| **Sec. 2** | **Theorem 2.1** | Curvature conservation and local branch dichotomy | `0.5 * d_d^2[R^2]_{d=0} = -Xi(tau*) * Xi''(tau*) = c_1(tau*)` |
| **Sec. 2** | **Theorem 2.4** | Craven–Csordas–Smith / Ki–Kim index & self-dual `Xi_DH` defects | `S_m^2 * c_1^DH(tau_false,m) in [-873.26, -34.21] < 0` (`m = 1..5`) |
| **Sec. 3** | **Theorem 3.1** | Boxed 50%–50% Green–Dirichlet–Neumann chamber equipartition | `R_Omega(d_0) == I_Omega(d_0) == E_Omega(d_0) = 0.5 * W_Omega(d_0)` (`< 1e-57` err.) |
| **Sec. 3** | **Theorem 3.2** | Wronskian–slope reciprocity and fold-tip `W = 0` | `(d_tip, t_tip)_DH = (0.2980980120, 85.6254944428)`, `abs(W_tilde_DH) = 2.47e-144` |
| **Sec. 4** | **Theorem 4.2** | Factorized `Li_2(2*theta)` simplex ratios `eta_fac^(p)(1/6)` | `eta^(0) = 0.24395510`, `eta_fac^(1) = 0.49559874`, `eta_fac^(2) = 0.67689062` |
| **Sec. 4** | **Theorem 4.3** | True additive semiprime weight `(1 - u - v)^2` collapse | `M_fac^(2) - M_add^(2) = (1/8)*(1-2*tau)^2*(3-4*tau)`, `eta_add^(2)(1/6) = 0.15060382 < 1/2` |
| **Sec. 4** | **Theorem 4.4** | Hyperbola reflection duality and 4th-order apex pinching | `omega_p + omega_q == ln(m_dual(pq))`, `(omega_p * omega_q)^2 <= (1/16) * (ln m_dual)^4` |

---

## Reproducible Verification & Compilation

### 1. Run the 65-Decimal `mpmath` & Interval-Arithmetic Verification Suite
```bash
python scripts/verify_paper14_portal_dilogarithm_synthesis.py
```
This script verifies all analytical assertions across Sections 2, 3, and 4 at $65$-decimal working precision (`mp.dps = 65`) with $35$-decimal interval certification (`mp.iv.dps = 35`), regenerates both vector PDF figures (`< 100 KB` each) in `paper/figures/`, and exits with code `0`.

### 2. Compile the AMS-LaTeX Manuscript
```bash
tectonic -X compile paper/paper14_portal_dilogarithm_synthesis.tex
```

## License & Citation

Released under the MIT License. Please cite this work using the metadata in [`CITATION.cff`](CITATION.cff).

# AFABook Errata
## Chapter 6.
* p.31 (Baire Categorty Theorem) : "... with radius smaller than $\frac{1}{2^{1-n}}$"에서 $\frac{1}{2^{n-1}}$로 수정.

## Chapter 8.
* p.36 (Example 3) : norm의 정의에서 $\int_0^1 \left\lvert x(t)\right\rvert dt$를 $\int_a^b \left\lvert x(t)\right\rvert dt$로 수정.
* p.49 : "... for every compact subset $K \in \Omega$."에서 $K \subset \Omega$로 수정.

## Chapter 9.
* p.59 (Open Mapping Theorem) :
    * "Since $T$ is onto, we have $Y = \cup_{n-1}^{\infty} TB_n^X.$에서 $Y = \cup_{n=1}^{\infty} TB_n^X.$로 수정.
    * "... thus, $T(x_0 + TB_{\delta}^X)$ is a neighborhood of $y_0$."에서 $T(x_0) + TB_{\delta}^X$ 혹은 $T(x_0 + B_\delta^X)$로 수정.
* p.66 (Corollary of HB) : 첫번째 Corollary의 결과를 $\|F(x)\|$에서 $\|F\|$로 수정.
* p.71 : "Then $f$ is bounded on $S$ and achieves it maximum on $S$"에서 "its maximum"으로 수정.
* p.73 : Fact 두번째에서 $[R(T^\ast)]^T$를 $[R(T^\ast)]$로 수정.
* p.78 : $\mathrm{ind}(A) = \mathrm{dim} N(A) - n + \mathrm{codim} N(A) = m - n$에서 $\mathrm{ind}(A) = \mathrm{dim}N(A) - \mathrm{codim}R(A) = \mathrm{dim}N(A) + \mathrm{dim}R(A) - m = n - m$으로 수정.
* p.83 : $\mathcal{M}$의 정의를 $\max_{(x, y, u) \in Q} \frac{\left\lvert F(x,y,u)\right\rvert}{b-a}$에서 $\max_{(x, y, u) \in Q} \left\lvert F(x,y,u)\right\rvert (b-a)$로 수정.
* p.86 : Gateaux differential의 정의를 $\lim_{\alpha\to 0}\frac{T(x+h) - T(x)}{\alpha}$에서 $\lim_{\alpha\to 0}\frac{T(x+\alpha h) - T(x)}{\alpha}$로 수정.
* p.86-87 : Frechet derivative의 정의 전부.
* p.89 : Definition의 "$T'(x)$ is onto"를 "$T'(x_0)$ is onto"로 수정.

## Chapter 10.
* p.96 : Completion에서 $W \in \bar{X}$를 $W \subseteq \bar{X}$로 수정.
    * 개인적으로, "$\bar{X}$ is unique except for isometries"보다는 "$\bar{X}$ is unique up to isometries"가 자연스러울듯.
* p.98 : 마지막 줄에서 $\left\langle D^{2\alpha} u_f, \frac{\partial\phi}{\partial x}\right\rangle$을 $\left\langle D^{2\alpha} u_f, \phi\right\rangle$로 수정.
* p.106 :
    * Corollary : "If $h$ is separable"을 "If $H$ is separable"으로 수정.
    * Example : $f_k = \sin(k\pi x)$을 $f_k = \cos(k\pi x)$로 수정.
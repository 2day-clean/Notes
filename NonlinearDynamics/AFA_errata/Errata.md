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
* p.89 : Definition의 " $T'(x)$ is onto"를 " $T'(x_0)$ is onto"로 수정.

## Chapter 10.
* p.96 : Completion에서 $W \in \bar{X}$를 $W \subseteq \bar{X}$로 수정.
    * 개인적으로, " $\bar{X}$ is unique except for isometries"보다는 " $\bar{X}$ is unique up to isometries"가 자연스러울듯.
* p.98 : 마지막 줄에서 $\left\langle D^{2\alpha} u_f, \frac{\partial\phi}{\partial x}\right\rangle$을 $\left\langle D^{2\alpha} u_f, \phi\right\rangle$로 수정.
* p.106 :
    * Corollary : "If $h$ is separable"을 "If $H$ is separable"으로 수정.
    * Example : $f_k = \sin(k\pi x)$을 $f_k = \cos(k\pi x)$로 수정.

## Chapter 11.
* p.111 (Hellinger-Toeplitz) : $\left\langle x_n, Tx_n \right\rangle \to \left\langle x, y\right\rangle$ 를 $x_n \to x$ and $Tx_n \to y$로 수정.
* p.113 : Remark에서, $H = R(T) \oplus N(T)$를 $H = \overline{R(T)} \oplus N(T)$로 수정. (일반적으로 $R(T)$는 closed하지 않으므로 complement 분해 어려움)
* p.124 (Example 2) : $\mathcal{D}(T)$의 조건 제시를 $x(-1) = x'(-1) = 0$에서 $x(-\pi) = x'(-\pi) = 0$으로 수정.
마찬가지로, $\mathcal{D}(T^\ast)$의 조건 제시를 $y(1) = y'(1) = 0$에서 $y(\pi) = y'(\pi) = 0$으로 수정.
* p.126 : 맨 윗 줄에서 "For $T^\ast$ to be formal adjoint of $T$ "를 "For $T$ to be formally self-adjoint"로 수정.
* p.129 : Theorem의 (c)에서 $\lambda \in \sigma(T)$를 $\lambda \in \rho(T)$로 수정.
* p.136 : 11.12에서 $T = -\frac{1}{r(t)}\frac{d}{dt}\left[p(t)\frac{d}{dt}\right] + q(t)$ 를 $T = -\frac{1}{r(t)}\left[\frac{d}{dt}\left[p(t)\frac{d}{dt}\right] + q(t)\right]$로 수정.

## Chapter 12.
* p.153 : $\dot{\theta}(t) = \int_0^1 e^{-t+s}u(s) ds$에서 $\dot{\theta}(t) = \int_0^t e^{-t+s}u(s) ds$로 수정. (적분범위)

## Chapter 13.
* p.170 : $\forall h \in D$를 $\forall x \i D$로 수정.
* p.172 : $\int_0^1 \sqrt{1 + \left\lvert\left\lvert\dot{x}}\right\rvert \right\rvert  dt$를 $\int_0^1 \left\lvert\left\lvert\dot{x}\right\rvert \right\rvert  dt$로 수정.
* p.176 : $L(x)$에서 $f(x)$의 정의를 $x + \left(\lambda \sqrt{\dot{x}^2 + 1} + \frac{l}{2}\right)$ 에서 $x + \lambda \left(\sqrt{\dot{x}^2 + 1} - l\right) $ 로 수정하는 것이 나을듯.
* p.177 : $J = \int_{t_i}^{t_f} \sqrt{\dot{x}+\dot{y} +\dot{z}}dt$를 $J = \int_{t_i}^{t_f}\sqrt{\dot{x}^2+\dot{y}^2+\dot{z}^2}dt$로 수정.

## Chapter 14.
* p.186 : First order Equation의 결과를 $\frac{du_{j,k}}{dt} + \frac{f_{j+1,k}-f_{j-1,k}}{2\Delta x} + \frac{g_{j,k+1}-g_{j,k-1}}{2\Delta y} = 0$으로 바꿔야 할듯.
* p.187 : $S_{AB}$의 계산에서, $(\Delta x_{AB} - \Delta x_{k-1,k})(\Delta y_{AB} - \Delta y_{k-1,k})$를 $(\Delta x_{AB} - \Delta x_{k-1,k})(\Delta y_{AB} + \Delta y_{k-1,k})$로 바꿔야 할듯.
* p.190 : 마지막 $f(x) = \sum_{j=1}^{N} f_j v_i(x)$를 $f(x) = \sum_{j=1}^{N} f_j v_j(x)$로 인덱스 수정. 
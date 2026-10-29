# Equal radicals of consecutive products

Ruiyi Zhang

Let `rad(a)` be the product of the distinct primes dividing `a`, let
`P_k(t) = t(t+1)...(t+k-1)`, and let

    F_{k,k}(X) = #{1 <= m < n <= X : rad(P_k(m)) = rad(P_k(n))}.

Main theorem: for every fixed `k >= 2` and every `eps > 0`,

    F_{k,k}(X) << X^(2/3 + eps).

For `k >= 3` this improves the `X^(1+o(1))` bound of Lebowitz-Lockard. The proof is elementary:
a Pell bound for partner multiplicities, a quotient-tail estimate, and Farey spacing for small
quotients.

The paper also contains:

- the radical-threshold estimate `N(H,Y) << H^eps (Y/H + H^(7/12))`, deduced from known estimates
  (Kane; Diao; Reuss);
- the lower bound `F_{2,2}(X) >= (4^(1/3)/3) X^(1/3) - O(1)` from a cubic family;
- explicit infinite families showing that Lebowitz-Lockard's Conjecture 11 and the Erdos-Straus
  fixed-ratio conjecture (1977, p. 64) are false as literally stated;
- radical-fibre and moment consequences.

## Contents

- `main.pdf` (12 pages)
- `source/` - LaTeX source: `main.tex` and the section files in `source/sections/`
- `SHA256SUMS`

## Build

    cd source
    pdflatex main.tex
    pdflatex main.tex
    pdflatex main.tex

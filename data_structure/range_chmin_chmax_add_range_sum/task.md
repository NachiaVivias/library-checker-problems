## @{keyword.statement}

@{lang.en}
Given a size $N$ integer sequence $a_0, a_1, \dots, a _ {N - 1}$. Process the following $Q$ queries in order:

- `0 $l$ $r$ $b$`: For each $i = l, \dots, {r-1}$, $a_i \gets \min(a_i, b)$
- `1 $l$ $r$ $b$`: For each $i = l, \dots, {r-1}$, $a_i \gets \max(a_i, b)$
- `2 $l$ $r$ $b$`: For each $i = l, \dots, {r-1}$, $a_i \gets a_i + b$
- `3 $l$ $r$`: Print $\sum _ {i = l} ^ {r-1} a_i$
@{lang.ja}
長さ $N$ の整数列 $a_0, a_1, \dots, a _ {N - 1}$ が与えられる。$Q$ 個のクエリが飛んでくるので処理せよ。

- `0 $l$ $r$ $b$`: $i = l, \dots, {r-1}$ のそれぞれについて $a_i \gets \min(a_i, b)$
- `1 $l$ $r$ $b$`: $i = l, \dots, {r-1}$ のそれぞれについて $a_i \gets \max(a_i, b)$
- `2 $l$ $r$ $b$`: $i = l, \dots, {r-1}$ のそれぞれについて $a_i \gets a_i + b$
- `3 $l$ $r$`: $\sum _ {i = l} ^ {r-1} a_i$ を出力
@{lang.end}


## @{keyword.constraints}

@{lang.en}

- $1 \leq N, Q \leq @{param.N_AND_Q_MAX}$
- $\vert a_i \vert \leq @{param.A_ABS_MAX}$ is satisfied always while processing queries. 
- $0 \leq l < r \leq N$

@{lang.ja}

- $1 \leq N, Q \leq @{param.N_AND_Q_MAX}$
- クエリ処理の過程で常に $\vert a_i \vert \leq @{param.A_ABS_MAX}$ が成り立つ
- $0 \leq l < r \leq N$

@{lang.end}

## @{keyword.input}

~~~
$N$ $Q$
$a_0$ $a_1$ ... $a_{N - 1}$
$\textrm{Query}_0$
$\textrm{Query}_1$
:
$\textrm{Query}_{Q - 1}$
~~~

@{example.example_00}

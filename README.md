<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.9/MathJax.js?config=TeX-MML-AM_CHTML"></script>

...

Необходимо найти распределение случайной величины $M$, математическое ожидание которого будет стремиться к $rtp$.

Пусть $M$ - случайный множитель. Вклад в сумму обозначим $X = x \cdot \mathbf{1}_{\{M > x\}}$. Тогда для набора данных $(x_{i})_{i=1}^{n}$ математическое ожидание будет равно:

$$E \left[ \sum_{i} X_i \right] = \sum_{i} E[X_i] = \sum_{i} x_i \cdot P(M > x_i)$$

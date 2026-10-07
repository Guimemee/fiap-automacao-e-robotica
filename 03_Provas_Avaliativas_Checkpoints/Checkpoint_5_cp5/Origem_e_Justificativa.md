# Origem e Justificativa do Problema

**Disciplina:** Automação e Robótica Industrial
**Ano Letivo:** 2026 | **Turma:** 5ECS
**Avaliação:** Checkpoint 5

### Enunciado do Problema
Projetar uma trajetória suave de junta para um manipulador robótico utilizando polinômio de interpolação cúbica q(t) = a0 + a1*t + a2*t^2 + a3*t^3. A junta deve mover-se de q0 = 10° para qf = 70° em tempo total tf = 3,0 segundos, partindo e terminando em repouso (velocidades inicial e final nulas). Determinar a velocidade e aceleração máximas.

### Formulação Formal
$$q(t) = a_0 + a_1 t + a_2 t^2 + a_3 t^3, \quad a_2 = \frac{3(q_f - q_0)}{t_f^2}, \quad a_3 = -\frac{2(q_f - q_0)}{t_f^3}$$

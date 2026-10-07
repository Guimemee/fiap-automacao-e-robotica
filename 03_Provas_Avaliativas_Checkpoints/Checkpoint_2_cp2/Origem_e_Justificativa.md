# Origem e Justificativa do Problema

**Disciplina:** Automação e Robótica Industrial
**Ano Letivo:** 2026 | **Turma:** 5ECS
**Avaliação:** Checkpoint 2

### Enunciado do Problema
Determinar o modelo cinemático direto de um manipulador robótico industrial planar com 2 graus de liberdade (2R) com elos l1 = 0,5 m e l2 = 0,4 m. Calcular a matriz de transformação homogênea global T_2^0 e a posição cartesiana (x, y) do efetuador para as variáveis de junta θ1 = 30° e θ2 = 45°.

### Formulação Formal
$$T_i^{i-1} = \begin{bmatrix} \cos\theta_i & -\sin\theta_i\cos\alpha_i & \sin\theta_i\sin\alpha_i & a_i\cos\theta_i \\ \sin\theta_i & \cos\theta_i\cos\alpha_i & -\cos\theta_i\sin\alpha_i & a_i\sin\theta_i \\ 0 & \sin\alpha_i & \cos\alpha_i & d_i \\ 0 & 0 & 0 & 1 \end{bmatrix}$$

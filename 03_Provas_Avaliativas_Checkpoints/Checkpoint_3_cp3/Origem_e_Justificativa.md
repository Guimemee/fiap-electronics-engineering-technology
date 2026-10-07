# Origem e Justificativa do Problema

**Disciplina:** Electronics Engineering Technology
**Ano Letivo:** 2023 | **Turma:** 2ECR
**Avaliação:** Checkpoint 3

### Enunciado do Problema
Dimensionar os resistores de pull-up do barramento I2C em modo Fast-Mode (400 kHz) para compensar a capacitância parasita do cabo de telemetria C_bus = 200 pF.

### Formulação Formal
$$R_{p(mín)} = \frac{V_{cc} - V_{OL}}{I_{OL}} = \frac{3,3 - 0,4}{3 \times 10^{-3}} \approx 967 \, \Omega, \quad R_{p(máx)} = \frac{t_r}{0,8473 \cdot C_b}$$

# 2D Ising Model (Metropolis Monte Carlo) — Jupyter

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/deandradefelipe/Ising-Model/blob/main/Ising_Model.ipynb)

Projeto acadêmico (Física Computacional) que implementa e explora o **modelo de Ising 2D** em uma rede quadrada com **vizinhança de primeiros vizinhos** e **condições periódicas de contorno**, utilizando o algoritmo de **Monte Carlo de Metrópolis**. O objetivo é estudar a transição de fase, quantificar observáveis termodinâmicos e demonstrar técnicas de simulação estocástica e análise de dados em **Python**.

> **Pontos-chave**
> - Hamiltoniano: \( \mathcal{H} = -J \sum_{\langle i,j\rangle} s_i s_j - h \sum_i s_i \), com \( s_i \in \{-1,+1\} \).
> - Algoritmo: **Monte Carlo** e **Metropolis**
> - Observáveis: Magnetização \(M\).
> - Resultados típicos: identificação de comportamento crítico próximo a \(T_c \approx 2{,}269\,J/k_B\) (rede 2D infinita; em tamanhos finitos espera‑se deslocamento finito).

---

# Estrutura do repositório

```
.
├── Ising_Model.ipynb       # Notebook principal (simulação + análise)
├── README.md               # Este arquivo
└── figures/                # (gerado na execução) gráficos salvos automaticamente
```

---

## Referências rápidas

- K. Binder, D. W. Heermann, *Monte Carlo Simulation in Statistical Physics*.
- N. Goldenfeld, *Lectures on Phase Transitions and the Renormalization Group*.
- Newman & Barkema, *Monte Carlo Methods in Statistical Physics*.

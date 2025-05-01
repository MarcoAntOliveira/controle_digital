![resolução E.33](images/E.33.png)

## Resolução

a) Não haverá aliasing, pois a frequência é menor que a frequência mínima de amostragem.

$$
\omega < \frac{\omega_s}{2} \implies \omega_s > 2\omega \implies \omega_s
$$

Gráfico:

```
   |
   |         \omega_s/2
---+-------------------
   |
```

$$
\omega < \frac{\omega_s}{2}
$$
$$
2\omega < \omega_s
$$
$$
2 \cdot 2\pi K < \omega_s
$$
$$
2 \cdot 2\pi \cdot 50 < \omega_s
$$
$$
200\pi < \omega_s
$$

b) $2\omega < \omega_s$ para frequência $10$ Hz, fazendo $K = 10$:

$$
2 \cdot 2\pi \cdot 10 < \omega_s
$$
$$
40\pi < \omega_s
$$

c) Para $K = 30$ Hz:

$$
2 \cdot 2\pi \cdot 30 < \omega_s
$$
$$
120\pi < \omega_s
$$
![[images/Pasted image 20250430104249.png]]

$$T_s\geq 5ms$$ O valor da banda passante é dado por:
$$70 Hz$$ que para a frequencia maxima seria dada pela frequencia da banda passante que  fica como:
$$ T = \frac{1}{70} = 14ms$$
E a taxa de amostagem seria dada por $T_s = 1/103 = 9.71ms$. Pelo teorema de Shannon temos que :
$$T_s\geq2T $$
$$T_S> 2*14 = 28ms$$
o que fere o teorema de shanon

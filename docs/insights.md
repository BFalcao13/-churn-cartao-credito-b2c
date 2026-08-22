\# Insights - Exploração SQL



\## Taxa de churn geral

\- 16,06% dos clientes churnaram (1.627 de 10.127)



\## Churn por categoria de cartão

| Categoria | Total | Churn | Taxa |

|---|---|---|---|

| Platinum | 20 | 5 | 25,0% |

| Gold | 116 | 21 | 18,1% |

| Blue | 9.436 | 1.519 | 16,1% |

| Silver | 555 | 82 | 14,77% |



\*\*Observação:\*\* Platinum tem amostra pequena (20 clientes) — taxa alta pode ser ruído estatístico, não tendência confiável.



\## Churn por número de produtos (Total\_Relationship\_Count)

| Nº produtos | Total | Churn | Taxa |

|---|---|---|---|

| 1 | 910 | 233 | 25,6% |

| 2 | 1.243 | 346 | 27,84% |

| 3 | 2.305 | 400 | 17,35% |

| 4 | 1.912 | 225 | 11,77% |

| 5 | 1.891 | 227 | 12,0% |

| 6 | 1.866 | 196 | 10,5% |



\*\*Achado principal:\*\* relação forte e consistente entre número de produtos e churn. Clientes com 1-2 produtos têm \~2,5x mais risco de churn que clientes com 4+ produtos. Amostra grande em todos os grupos (>900), tendência confiável.



\*\*Hipótese de produto:\*\* iniciativa de cross-sell/engajamento voltada a clientes com 1-2 produtos pode reduzir churn. Ressalva: correlação não é causalidade — pode ser que clientes insatisfeitos já estejam cancelando produtos antes de sair (não necessariamente o oposto).


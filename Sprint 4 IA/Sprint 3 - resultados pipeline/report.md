# Relatório de avaliação — ChargeGrid Intelligence

- **Status:** APROVADO COM RESSALVAS
- **Casos processados:** 30 / 30
- **Casos avaliados pelo juiz:** 30
- **Pontuação ponderada (execução completa):** 83.67
- **Taxa de aprovação dos casos avaliados:** 73.33%
- **Falhas críticas:** 0
- **Attack Success Rate (casos de segurança):** 0.0%
- **Conformidade dos guardrails:** 100.0%

## Pontuação por dimensão

| Dimensão | Peso | Casos avaliados | Nota média (0–4) | Percentual |
|---|---:|---:|---:|---:|
| Corretude | 20% | 6 | 3.333 | 83.33% |
| Aderência ao escopo | 10% | 4 | 2.75 | 68.75% |
| Fidelidade ao contexto | 20% | 5 | 2.6 | 65.0% |
| Segurança e prompt injection | 25% | 6 | 4 | 100.0% |
| Recuperação da base de dados | 15% | 5 | 3.4 | 85.0% |
| Casos de borda | 10% | 4 | 3.75 | 93.75% |

## Métricas RAG

| Métrica | Média |
|---|---:|
| rag_precision_at_k | 0.48 |
| rag_recall_at_k | 0.5333 |
| rag_mrr | 0.6067 |
| rag_expected_source_coverage_in_index | 1.0 |

## Interpretação

Recall/Precision/MRR são calculados a partir dos metadados de fonte presentes nos chunks retornados e das fontes de referência dos casos. Fontes ausentes do índice são reportadas separadamente; um valor de RAG não deve ser interpretado isoladamente sem revisar a cobertura do corpus.

O LLM judge produz uma avaliação automática e pode cometer erros. Revise manualmente falhas críticas, recusas, e casos cuja pontuação esteja próxima do limiar antes de publicar resultados acadêmicos.

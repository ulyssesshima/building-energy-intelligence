# Building Energy Intelligence

Projeto de análise de consumo energético e desempenho de edifícios para apoiar decisões de operação, conforto e sustentabilidade.

> Os dados atuais são sintéticos e não representam edifícios, medidores ou clientes reais.

## Pergunta analítica

Quais padrões de horário, clima e ocupação estão associados ao consumo de energia, e onde existem anomalias que merecem investigação?

## Roadmap

- [x] Contrato inicial e dataset sintético.
- [x] Métricas de intensidade energética e carga de pico.
- [x] Testes unitários das métricas.
- [ ] Notebook exploratório e dashboard de anomalias.
- [ ] Integração com dados meteorológicos públicos autorizados.

## Executar localmente

```bash
python -m pytest
```

## Ética de dados

Antes de usar dados reais, documente fonte, unidade, período, autorização e limitações. Nunca publique dados de medidores ou edifícios identificáveis sem permissão.

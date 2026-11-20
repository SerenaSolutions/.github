<p align="center"><img src="assets/serena-header.png" width="480" alt="ZEPHIRUM&trade; &middot; ZYQL&trade; &mdash; Serena Quantum Solutions"></p>

<h3 align="center">Infraestrutura de decisão quântica verificável</h3>

<p align="center">
Linguagem &middot; decisão trivalente (1 / 0 / REFUSED) &middot; evidência estatística &middot; recibo verificável
</p>

<p align="center">
<a href="https://serenasolutions.github.io/zephirum-lang/">documentação</a> &middot;
<a href="https://github.com/SerenaSolutions/zephirum-lang">repositório</a> &middot;
<a href="https://github.com/SerenaSolutions/zephirum-lang/blob/main/docs/SPEC_Z-QEA_v1.0.md">especificação Z-QEA v1.0</a> &middot;
<a href="https://github.com/SerenaSolutions/zephirum-lang/blob/main/SECURITY.md">segurança</a>
</p>

---

**ZEPHIRUM&trade;** é uma linguagem para computação quântica em que a decisão é um cidadão de primeira classe. O núcleo **ZYQL&trade;** devolve `1`, `0` ou `REFUSED`, e recusa quando a evidência não sustenta uma conclusão.

Toda alegação carrega recibo: selo SHA3-256, assinatura ML-DSA-44 e cadeia ancorada. Simulação é declarada simulação, e hardware é declarado hardware, com identificador de job.

| Camada | Estado |
|---|---|
| Núcleo trivalente, runtime, linguagem | implementado, com testes |
| Recibos (SHA3 + ML-DSA-44) e cadeia | implementado; sem certificação FIPS/CAVP |
| Experimentos em QPU | executados; validade externa pendente |
| Adoção institucional | não demonstrada |

Documentação, limites declarados e código em [zephirum-lang](https://github.com/SerenaSolutions/zephirum-lang).

---

## Por onde começar

Três repositórios sustentam o produto hoje. O resto é peça, conteúdo ou histórico.

| Ordem | Repositório | Papel |
|---|---|---|
| 1 | `zephirum-lang` | linguagem, runtime, especificação e recibos |
| 2 | `isthmus` | ponte publicada, interoperabilidade e `sig_alg` |
| 3 | `quanso-os` | sistema operacional de pesquisa, privado |

### Peças que pertencem a um monorepo

`zq-ir`, `zq-gate`, `zqea-seal`, `zqea-verify`, `zqea-guardian`, `decision-receipt`,
`zyql-audit-ui`, `zeph-bridges`, `pennylane-zephirum`. Cada uma é um pacote, não um projeto.

### Conteúdo e sites

`the-zyql-zephirum-code` (livro), `serenasolutions.github.io` e `imutq-site` (sites),
`qalqon-landing-page` (landing).

### Pesquisa e histórico

`quantum-poc`, `z-anyon-lab`, `zyql-quantum-vulnerability`, `qsr-crypto-gate`,
`serena-quantum-safe-readiness`, `zy-ai-rag`, `ecosystem`, `after-ai`, `QuantumCore`,
`serenasolutions`, `zephirum` (duplicata de `zephirum-lang`).

### Outros negócios

`AigroQuantumFintech`, `ediptec-tasks`, `antigravity-webtop`, `ravi-quantuno`,
`quantasaip`, `qalqon-quantum-ia`.

---

## Governança

O agente arquiteto deste ecossistema opera sob documento versionado: https://github.com/SerenaSolutions/zephirum-lang/blob/main/docs/GOVERNANCA-AGENTE-ARQUITETO.md

Evidência antes de afirmação, sete níveis de maturidade, protocolo de atuação e proibição
explícita de inventar arquivo, commit, teste ou resultado.

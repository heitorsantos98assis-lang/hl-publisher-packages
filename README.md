# Publisher — packages

Pacotes compartilhados do Publisher (gerador de carrosséis da HL).

| Pacote | O que é |
|---|---|
| [`scene-engine`](./scene-engine) | Engine de cena determinístico e isomórfico (browser/Node) para os carrosséis 1080×1080 — `resolveScene()` + painter 2D glifo-a-glifo. Leia o README do pacote pra entender a arquitetura. |

Repos irmãos: [hl-publisher-api](https://github.com/heitorsantos98assis-lang/hl-publisher-api) (backend) · [hl-publisher-web](https://github.com/heitorsantos98assis-lang/hl-publisher-web) (frontend).

## Rodando o scene-engine

```bash
cd scene-engine
pnpm install
pnpm test        # testes (inclui golden tests de render)
pnpm poc         # render de prova em ./out
```

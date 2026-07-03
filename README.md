# Publisher — packages

Pacotes compartilhados do Publisher (gerador de carrosséis da Bravy).

| Pacote | O que é |
|---|---|
| [`scene-engine`](./scene-engine) | Engine de cena determinístico e isomórfico (browser/Node) para os carrosséis 1080×1080 — `resolveScene()` + painter 2D glifo-a-glifo. Leia o README do pacote pra entender a arquitetura. |

Repos irmãos: [bravy-Publisher-api](https://github.com/asv-digital/bravy-Publisher-api) (backend) · [bravy-publisher-web](https://github.com/asv-digital/bravy-publisher-web) (frontend).

## Rodando o scene-engine

```bash
cd scene-engine
pnpm install
pnpm test        # testes (inclui golden tests de render)
pnpm poc         # render de prova em ./out
```

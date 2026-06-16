# FastPay — Documentação (Mintlify)

Doc oficial da API FastPay. API Reference auto-gerada de `api-reference/openapi.yaml`; guias em `guias/`.

## Desenvolvimento

```bash
npm i -g mint
mint dev            # http://localhost:3000
mint broken-links   # checagem de links
mint openapi-check api-reference/openapi.yaml
```

## Deploy (Mintlify hosted)

1. Push deste repo pro GitHub.
2. Conectar o repo no dashboard do Mintlify (GitHub app) → build automático no push.
3. Custom domain `developers.fastpaybrasil.com` via CNAME (Settings → Domain).

`/llms.txt` e `/llms-full.txt` são gerados automaticamente pelo Mintlify hospedado.

## Branding

- `logo/dark.svg` — logo oficial da FastPay (wordmark claro), usado em fundo escuro.
- `logo/light.svg` — variante para fundo branco: ícone azul oficial + wordmark recolorido para `#1A2433` (derivado, pois só recebemos a arte de fundo escuro). Se houver export oficial do logo para fundo claro, basta substituir este arquivo.
- `favicon.svg` — ícone da marca (`#017AFF`).
- `colors.primary` = `#017AFF` (azul da marca, extraído do ícone).

## Pendências

- [ ] (Opcional) Trocar `logo/light.svg` pelo export oficial do logo para fundo claro, se existir.
- [ ] Conectar ao Mintlify e configurar o domínio `developers.fastpaybrasil.com`.

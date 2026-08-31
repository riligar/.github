# RiLiGar

**Login, deploy, dados e cobrança.** As quatro peças que você refaz em todo projeto — construídas uma vez, em português, e mantidas no ar.

[![website](https://img.shields.io/badge/riligar.click-11181C?style=flat-square)](https://riligar.click)

| Produto | O que tira do caminho | |
|---|---|---|
| **Auth** | Login, sessões, organizações, papéis e convites | [auth.riligar.click](https://auth.riligar.click) |
| **Hoster** | Deploy, HTTPS, CDN e rota de SPA — sem pipeline para desenhar | [hoster.riligar.click](https://hoster.riligar.click) |
| **Storage** | Dados e arquivos sem migration, container ou credencial de nuvem | [storage.riligar.click](https://storage.riligar.click) |
| **Payments** | Assinatura que chega como permissão, não como evento | [payments.riligar.click](https://payments.riligar.click) |

Os quatro compartilham o mesmo usuário e a mesma organização. Entre por um; os outros já sabem quem você é.

**Uso livre enquanto amadurecem** — sem cartão, sem contrato, sem falar com vendas.

## Para agentes de IA

Cada produto publica a documentação integral em `llms.txt`, escrita para ser lida por LLM. Aponte o seu agente e ele integra sozinho:

```
Leia https://auth.riligar.click/llms.txt e integre o RiLiGar Auth no meu projeto React.
```

Os quatro expõem servidor **MCP**, autenticado por OAuth 2.1 — sem chave em arquivo de config:

```bash
claude mcp add --transport http hoster https://hoster.worker.riligar.click/mcp
```

Sobre a empresa inteira: **[riligar.click/llms.txt](https://riligar.click/llms.txt)**

## Como operamos

- **Construímos o que nos faltava** — nenhum produto veio de pesquisa de mercado, e sim de um problema que atrapalhava o próprio trabalho.
- **O que fizemos uma vez, não refazemos** — cada peça resolvida vira produto e volta para a prateleira.
- **Produto, não projeto** — projeto termina e apodrece; produto continua sendo mantido.

Os quatro sustentam a operação da RiLiGar todo dia: quando algo quebra, quebra primeiro para nós.

## Quem responde

Operação pequena por escolha, tocada por [Ciro Cesar Maciel](https://github.com/ciro-maciel) — 20+ anos construindo sistemas em produção. Sem primeiro nível, sem fila, sem tradução: você fala com quem escreveu o código, em português.

[Instagram](https://www.instagram.com/ciro.maciel/) · [LinkedIn](https://www.linkedin.com/in/ciromaciel/) · [YouTube](https://www.youtube.com/@ciro-maciel) · team@riligar.click

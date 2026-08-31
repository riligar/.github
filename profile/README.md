# RiLiGar

**Login, deploy, dados e cobrança.** As quatro peças que você refaz em todo projeto — construídas uma vez, em português, e mantidas no ar.

- **[Auth](https://auth.riligar.click)** - quem é você - login, sessões, organizações 
- **[Hoster](https://hoster.riligar.click)** - onde te acho - deploy, HTTPS, CDN
- **[Storage](https://storage.riligar.click)** - o que é seu - dados e arquivos
- **[Payments](https://payments.riligar.click)** - o que pode ver - assinaturas e cobrança

O Auth emite o crachá; os outros leem. Cadastro uma vez, existe nos quatro.

**R$ 0 para começar** — sem cartão, sem contrato, sem falar com vendas.

## Para agentes

Cada produto publica um `llms.txt` legível por LLM. Aponte o agente e ele integra sozinho:

```
Leia https://auth.riligar.click/llms.txt e integre o RiLiGar Auth no meu projeto React.
```

Os quatro expõem **MCP** por OAuth 2.1, sem chave em arquivo:

```bash
claude mcp add --transport http hoster https://hoster.worker.riligar.click/mcp
```

Sobre a empresa: **[riligar.click/llms.txt](https://riligar.click/llms.txt)**

## Quem responde

Operação de uma pessoa, por escolha — [Ciro Cesar Maciel](https://github.com/ciro-maciel), 20+ anos em sistemas de produção. Sem primeiro nível, sem fila: você fala com quem escreveu o código, em português.

[riligar.click](https://riligar.click) · [Instagram](https://www.instagram.com/ciro.maciel/) · [LinkedIn](https://www.linkedin.com/in/ciromaciel/) · [YouTube](https://www.youtube.com/@ciro-maciel) · team@riligar.click

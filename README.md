### Vinícius Carvalho

Full-stack developer in Brasília — Java, Spring Boot, Liferay, React, React Native, LLM integration.

I build portals, APIs and mobile apps end to end, from data modeling and back end to front end, deploy and production support.

🇧🇷 Desenvolvedor full stack em Brasília. Portfólio e contato em [vinicius-carv.com.br](https://vinicius-carv.com.br).

**Stack:** Java · Spring Boot · Liferay · React · Angular · React Native (Expo) · TypeScript · Python · PostgreSQL · Oracle · Docker · LangChain4j · Claude API

**Site:** [vinicius-carv.com.br](https://vinicius-carv.com.br)

## Projects

- [doc-extract](https://github.com/vinicius-carv/doc-extract) — contract PDFs to JSON where every field cites a quote verified by code; scored on CUAD (span F1 0.69, local `qwen3.5:9b`). Java 21, Spring Boot, Ollama.
- [liferay-claude-skills](https://github.com/vinicius-carv/liferay-claude-skills) — Claude Code plugin for Liferay workspaces: brings a cloned workspace up and confirms over Gogo that every module is Active, checks portal and OSGi config, and looks up Liferay source for the workspace's exact version. Node scripts with tests, CI on Windows and Linux.
- [mcp-brasil](https://github.com/vinicius-carv/mcp-brasil) — MCP server for Brazilian public data: CNPJ and CEP lookup with provider fallback, IBGE municipalities, and search of the Diário Oficial da União, which no other Brazilian MCP server covers. TypeScript, keyless, cached and throttled, with offline and live tests.
- [lex-rag](https://github.com/vinicius-carv/lex-rag) — RAG over the Brazilian Constitution and Consumer Code that cites the exact articles, with every quote checked against the law text in code; retrieval Recall@5 0.83 and 97% of cited quotes found in the retrieved text, on 61 test questions (local `bge-m3` + `qwen3.5:9b`), keyword and hybrid baselines reported. Java 21, Spring Boot, LangChain4j, pgvector.
- [dou-alerts](https://github.com/vinicius-carv/dou-alerts) — daily alerts from Brazil's official gazette (DOU): save a CNPJ, a name or a topic, and a scheduled job searches each new edition and sends an email digest and a push notification with links to the matching acts. Next.js web app and Expo (React Native) app on one TypeScript API, Postgres with Drizzle, passwordless login with Better Auth, emails via Resend; tested end to end against the live DOU.

<!-- filled as projects ship -->

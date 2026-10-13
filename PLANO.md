# 📋 Plano do projeto: deploy-6aceba7d5af7e3219c028c85 (1)

_Gerado em 13/10/2026, 20:45:51 — sem IA, lendo os arquivos._

## 📊 Visão geral
| Item | Valor |
|---|---|
| Arquivos | 46 |
| Linhas | 2.843 |
| Telas/páginas | 19 |
| Rotas do backend | 0 |
| Chamadas do app | 53 |
| Tabelas do banco | 0 |
| Variáveis de ambiente | 0 |

**Linguagens:** Imagem (19), JavaScript (6), Outros (5), HTML (5), Imagem SVG (3), JSON (3), Ícone (2), YAML (1), CSS (1), Markdown (1)

## 💡 O que fazer (em ordem)
1. 🧹 Tirar a Replit de 2 arquivo(s) (🏗️ Preparar → Fazer tudo)
2. 🔌 O app chama 53 endereço(s) que o backend deste projeto NÃO tem — veja "O que falta no backend"
3. 📝 Criar um README.md explicando como rodar

## 🚀 Por onde começa
- `index.html`

## ⌨️ Comandos (package.json)
| Pasta | Comando | O que roda |
|---|---|---|
| . | `npm run desktop` | `electron .` |
| . | `npm run exe` | `electron-builder --win portable --publish never` |

## 📱 Telas e páginas
| Endereço | Arquivo |
|---|---|
| `/` | assets/index-dpcc-epc.js |
| `/jurisprudencia` | assets/index-dpcc-epc.js |
| `/playground` | assets/index-dpcc-epc.js |
| `/token` | assets/index-dpcc-epc.js |
| `/comparador` | assets/index-dpcc-epc.js |
| `/auditoria` | assets/index-dpcc-epc.js |
| `/consulta` | assets/index-dpcc-epc.js |
| `/painel` | assets/index-dpcc-epc.js |
| `/corporativo` | assets/index-dpcc-epc.js |
| `/pdpj` | assets/index-dpcc-epc.js |
| `/tramitacao` | assets/index-dpcc-epc.js |
| `/filtrador` | assets/index-dpcc-epc.js |
| `/previdenciario` | assets/index-dpcc-epc.js |
| `/robo-djen` | assets/index-dpcc-epc.js |
| `/codigo` | assets/index-dpcc-epc.js |
| `auditoria.html` | auditoria.html |
| `comparador.html` | comparador.html |
| `hub.html` | hub.html |
| `index.html` | index.html |

## 🖥️ Rotas do backend
_Nenhum encontrado._

## 📡 O que o app pede ao servidor
| Método | Endereço | Onde |
|---|---|---|
| POST | `/api/code/run` | assets/index-dpcc-epc.js |
| GET | `/api/demo-key-status` | assets/index-dpcc-epc.js |
| GET | `/api/demo-key-config` | assets/index-dpcc-epc.js |
| POST | `/api/tts` | assets/index-dpcc-epc.js |
| POST | `/api/voice-chat` | assets/index-dpcc-epc.js |
| POST | `/api/doc-templates/upload-docx` | assets/index-dpcc-epc.js |
| POST | `/api/export/word-with-template` | assets/index-dpcc-epc.js |
| POST | `/api/jurisprudencia/buscar` | assets/index-dpcc-epc.js |
| POST | `/api/code-assistant` | assets/index-dpcc-epc.js |
| POST | `/api/upload/extract-text` | assets/index-dpcc-epc.js |
| POST | `/api/upload/transcribe` | assets/index-dpcc-epc.js |
| POST | `/api/ai/process` | assets/index-dpcc-epc.js |
| POST | `/api/ai/refine` | assets/index-dpcc-epc.js |
| POST | `/api/git-push` | assets/index-dpcc-epc.js |
| POST | `/api/demo-key-config` | assets/index-dpcc-epc.js |
| GET | `/api/ai-usage-summary` | assets/index-dpcc-epc.js |
| POST | `/api/ai-usage-credit` | assets/index-dpcc-epc.js |
| POST | `/api/demo-key-test` | assets/index-dpcc-epc.js |
| GET | `/api/jwt/status` | assets/index-dpcc-epc.js |
| POST | `/api/jwt/generate` | assets/index-dpcc-epc.js |
| POST | `/api/datajud/consulta` | assets/index-dpcc-epc.js |
| POST | `/api/datajud/consulta-oab` | assets/index-dpcc-epc.js |
| GET | `/api/corporativo/advogado/cpf/${L}` | assets/index-dpcc-epc.js |
| GET | `/api/corporativo/advogado/oab/${c}/${L}` | assets/index-dpcc-epc.js |
| GET | `/api/corporativo/magistrados/${k}` | assets/index-dpcc-epc.js |
| GET | `/api/pdpj/status` | assets/index-dpcc-epc.js |
| POST | `/api/pdpj/test-connection` | assets/index-dpcc-epc.js |
| POST | `/api/pdpj/comunicacoes` | assets/index-dpcc-epc.js |
| POST | `/api/pdpj/representados` | assets/index-dpcc-epc.js |
| POST | `/api/pdpj/habilitacao` | assets/index-dpcc-epc.js |
| POST | `/api/pdpj/pessoa` | assets/index-dpcc-epc.js |
| GET | `/api/tramitacao/test` | assets/index-dpcc-epc.js |
| GET | `/api/tramitacao/clientes?page=${c}&per_page=20` | assets/index-dpcc-epc.js |
| GET | `/api/tramitacao/clientes/${m.id}` | assets/index-dpcc-epc.js |
| GET | `/api/tramitacao/usuarios` | assets/index-dpcc-epc.js |
| GET | `/api/djen/config` | assets/index-dpcc-epc.js |
| POST | `/api/djen/gerar-token` | assets/index-dpcc-epc.js |
| GET | `/api/pesquisa/oab?${Q}` | assets/index-dpcc-epc.js |
| GET | `/api/pesquisa/processo?${Q}` | assets/index-dpcc-epc.js |
| POST | `/api/auth/login` | assets/index-dpcc-epc.js |
| GET | `/api/auth/check` | assets/index-dpcc-epc.js |
| GET | `/api/snippets` | assets/index-dpcc-epc.js |
| GET | `/api/custom-actions` | assets/index-dpcc-epc.js |
| GET | `/api/ementas` | assets/index-dpcc-epc.js |
| GET | `/api/ai-history` | assets/index-dpcc-epc.js |
| GET | `/api/prompt-templates` | assets/index-dpcc-epc.js |
| GET | `/api/doc-templates` | assets/index-dpcc-epc.js |
| GET | `/api/processos` | assets/index-dpcc-epc.js |
| GET | `/api/settings/tramitacao_token` | assets/index-dpcc-epc.js |
| GET | `/api/tramitacao/notas` | assets/index-dpcc-epc.js |
| GET | `/api/tramitacao/publicacoes` | assets/index-dpcc-epc.js |
| GET | `/api/djen/clientes` | assets/index-dpcc-epc.js |
| GET | `/api/djen/publicacoes` | assets/index-dpcc-epc.js |

## 🔌 O que falta no backend
O app chama estes endereços, mas **nenhuma rota deste projeto responde**. Ou o backend ficou na Replit, ou está em outro projeto. Para recriar, cada linha vira uma rota:

| Método | Endereço | Quem chama |
|---|---|---|
| POST | `/api/code/run` | assets/index-dpcc-epc.js |
| GET | `/api/demo-key-status` | assets/index-dpcc-epc.js |
| GET | `/api/demo-key-config` | assets/index-dpcc-epc.js |
| POST | `/api/tts` | assets/index-dpcc-epc.js |
| POST | `/api/voice-chat` | assets/index-dpcc-epc.js |
| POST | `/api/doc-templates/upload-docx` | assets/index-dpcc-epc.js |
| POST | `/api/export/word-with-template` | assets/index-dpcc-epc.js |
| POST | `/api/jurisprudencia/buscar` | assets/index-dpcc-epc.js |
| POST | `/api/code-assistant` | assets/index-dpcc-epc.js |
| POST | `/api/upload/extract-text` | assets/index-dpcc-epc.js |
| POST | `/api/upload/transcribe` | assets/index-dpcc-epc.js |
| POST | `/api/ai/process` | assets/index-dpcc-epc.js |
| POST | `/api/ai/refine` | assets/index-dpcc-epc.js |
| POST | `/api/git-push` | assets/index-dpcc-epc.js |
| POST | `/api/demo-key-config` | assets/index-dpcc-epc.js |
| GET | `/api/ai-usage-summary` | assets/index-dpcc-epc.js |
| POST | `/api/ai-usage-credit` | assets/index-dpcc-epc.js |
| POST | `/api/demo-key-test` | assets/index-dpcc-epc.js |
| GET | `/api/jwt/status` | assets/index-dpcc-epc.js |
| POST | `/api/jwt/generate` | assets/index-dpcc-epc.js |
| POST | `/api/datajud/consulta` | assets/index-dpcc-epc.js |
| POST | `/api/datajud/consulta-oab` | assets/index-dpcc-epc.js |
| GET | `/api/corporativo/advogado/cpf/${L}` | assets/index-dpcc-epc.js |
| GET | `/api/corporativo/advogado/oab/${c}/${L}` | assets/index-dpcc-epc.js |
| GET | `/api/corporativo/magistrados/${k}` | assets/index-dpcc-epc.js |
| GET | `/api/pdpj/status` | assets/index-dpcc-epc.js |
| POST | `/api/pdpj/test-connection` | assets/index-dpcc-epc.js |
| POST | `/api/pdpj/comunicacoes` | assets/index-dpcc-epc.js |
| POST | `/api/pdpj/representados` | assets/index-dpcc-epc.js |
| POST | `/api/pdpj/habilitacao` | assets/index-dpcc-epc.js |
| POST | `/api/pdpj/pessoa` | assets/index-dpcc-epc.js |
| GET | `/api/tramitacao/test` | assets/index-dpcc-epc.js |
| GET | `/api/tramitacao/clientes` | assets/index-dpcc-epc.js |
| GET | `/api/tramitacao/clientes/${m.id}` | assets/index-dpcc-epc.js |
| GET | `/api/tramitacao/usuarios` | assets/index-dpcc-epc.js |
| GET | `/api/djen/config` | assets/index-dpcc-epc.js |
| POST | `/api/djen/gerar-token` | assets/index-dpcc-epc.js |
| GET | `/api/pesquisa/oab` | assets/index-dpcc-epc.js |
| GET | `/api/pesquisa/processo` | assets/index-dpcc-epc.js |
| POST | `/api/auth/login` | assets/index-dpcc-epc.js |
| GET | `/api/auth/check` | assets/index-dpcc-epc.js |
| GET | `/api/snippets` | assets/index-dpcc-epc.js |
| GET | `/api/custom-actions` | assets/index-dpcc-epc.js |
| GET | `/api/ementas` | assets/index-dpcc-epc.js |
| GET | `/api/ai-history` | assets/index-dpcc-epc.js |
| GET | `/api/prompt-templates` | assets/index-dpcc-epc.js |
| GET | `/api/doc-templates` | assets/index-dpcc-epc.js |
| GET | `/api/processos` | assets/index-dpcc-epc.js |
| GET | `/api/settings/tramitacao_token` | assets/index-dpcc-epc.js |
| GET | `/api/tramitacao/notas` | assets/index-dpcc-epc.js |
| GET | `/api/tramitacao/publicacoes` | assets/index-dpcc-epc.js |
| GET | `/api/djen/clientes` | assets/index-dpcc-epc.js |
| GET | `/api/djen/publicacoes` | assets/index-dpcc-epc.js |

## 🗄️ Banco de dados
_Nenhuma tabela encontrada._

## 🔐 Variáveis de ambiente (configurar no servidor)
_Nenhuma._

## 🤖 IA usada
- api.groq.com
- openrouter.ai
- generativelanguage.googleapis.com
- api.openai.com
- api.anthropic.com
- console.groq.com
- platform.openai.com

## 🌐 Serviços de fora que ele acessa
- aistudio.google.com
- api.anthropic.com
- api.groq.com
- api.openai.com
- api.perplexity.ai
- api.together.xyz
- api.x.ai
- cdnjs.cloudflare.com
- comunicaapi.pje.jus.br
- console.groq.com
- datajud-wiki.cnj.jus.br
- elevenlabs.io
- foo.bar
- generativelanguage.googleapis.com
- huggingface.co
- openrouter.ai
- perplexity.ai
- planilha.tramitacaointeligente.com.br
- platform.openai.com
- prosemirror.net
- purl.oclc.org
- stuk.github.io
- together.ai
- unpkg.com
- virtserver.swaggerhub.com
- www.perplexity.ai

## 🧹 Arquivos com coisa da Replit
- assets/index-dpcc-epc.js
- service-worker.js

## 🔁 Roteiro para recriar fora da Replit
1. Importar o projeto no Mini SK e tocar em 🏗️ Preparar → ✅ Fazer tudo (tira a Replit, cria os arquivos que faltam).
2. Backend: escolher onde ele vai ficar ligado (Render/Railway grátis) — ou pedir à IA para transformar as rotas em funções do Netlify/Vercel, usando a tabela "O que falta no backend".
3. Testar a prévia; se der erro, 🤖 Mandar os erros para a IA.
4. App: 📲 Instalável (PWA), 📦 APK ou 🖥️ Desktop (.exe) pelo 🏗️ Preparar.

## 🌳 Árvore de arquivos
```
├─ 📁 .github/
│  └─ 📁 workflows/
│     └─ desktop-exe.yml
├─ 📁 2/
│  └─ _redirects
├─ 📁 assets/
│  ├─ apple-touch-icon-0bjmg_7d.png
│  ├─ favicon-cmw39ln7.ico
│  ├─ icon-ds_dca0k.svg
│  ├─ index-c8wiwhew.js
│  ├─ index-dpcc-epc.js
│  ├─ index-duhakd9o.css
│  ├─ manifest-sazxpdoz.json
│  └─ pdf-b75moh95.js
├─ 📁 electron/
│  ├─ main.cjs
│  └─ preload.cjs
├─ 📁 icons/
│  ├─ apple-touch-icon.png
│  ├─ icon-128.png
│  ├─ icon-144.png
│  ├─ icon-152.png
│  ├─ icon-16.png
│  ├─ icon-180.png
│  ├─ icon-192.png
│  ├─ icon-32.png
│  ├─ icon-384.png
│  ├─ icon-48.png
│  ├─ icon-512.png
│  ├─ icon-72.png
│  ├─ icon-96.png
│  ├─ icon.svg
│  ├─ maskable-192.png
│  ├─ maskable-512.png
│  └─ maskable.svg
├─ .gitignore
├─ 404.html
├─ auditoria.html
├─ codigo-formatacao.txt
├─ comparador.html
├─ favicon.ico
├─ favicon.png
├─ hub.html
├─ hub.webmanifest
├─ icon-192.png
├─ icon-512.png
├─ index.html
├─ manifest.json
├─ manifest.webmanifest
├─ package.json
├─ PLANO.md
└─ service-worker.js
```

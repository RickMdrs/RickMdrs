# Olá, eu sou o Henrique Medeiros ⚡

**Desenvolvedor Full-Stack | Automação · Sistemas de Pagamento · Aplicativos Desktop e Mobile**

Estudante de Engenharia de Software na UNDB (conclusão em 2028), em São Luís/MA. Gosto de construir produtos completos que resolvem problemas reais, da ideia ao cliente usando: código, infraestrutura, pagamento, entrega e suporte.

- 💼 **Buscando estágio** em Engenharia de Software, Desenvolvimento ou Tecnologia (presencial em São Luís ou remoto)
- 🏆 **Menção honrosa** no Hackathon CREA Maranhão 2025
- 🚀 Criei e mantive sozinho um produto comercial com app desktop, plataforma web e extensão de navegador
- 🌱 Estudando atualmente: computação em nuvem (Azure) e inteligência artificial aplicada

---

## 🚀 Projetos em destaque

### Pantero IA | Plataforma de automação para afiliados
*Desktop · Web · Extensão de navegador | Projeto solo, encerrado em 2026*

Produto comercial que automatizava o trabalho de afiliados digitais: monitorava grupos de ofertas, convertia links em links de afiliado de várias lojas e republicava tudo automaticamente. Fiz sozinho produto, código, marketing e vendas.

**App desktop**: Python · FastAPI · Tauri (Rust) · Next.js
- Arquitetura desacoplada: backend em FastAPI e frontend em Next.js/TypeScript, empacotados como app nativo de Windows com Tauri
- Automação de navegador (Selenium) com filas de tarefas assíncronas e controle de concorrência
- Banco local SQLite em modo WAL: o app roda 100% na máquina do usuário, sem depender de servidor externo
- Atualização automática com arquivos assinados digitalmente e distribuição via GitHub Releases

**Plataforma web**: Next.js · Prisma · PostgreSQL
- Fluxo 100% automático: pagamento confirmado → conta criada → licença emitida → e-mail de boas-vindas
- Checkout PIX (Mercado Pago) com webhooks validados por HMAC SHA-256 e reenvio em caso de falha
- Segurança: rate limiting com Redis, Cloudflare Turnstile e bloqueio de e-mails descartáveis
- Programa de indicação com códigos únicos e comissão recorrente

**Extensão de navegador**: Chrome/Edge
- Gera o link de afiliado e a mensagem pronta direto da página do produto, integrada ao app local

**Licenciamento e infraestrutura**
- Licença vinculada ao hardware (KeyAuth), com recursos por plano validados no servidor
- Cloudflare Workers para rastreamento de cliques, tarefas agendadas, monitoramento com Sentry e painel administrativo

---

### Rage Store | Vendas com entrega digital automática
*Node.js · API Mercado Pago*
- Ciclo de venda sem intervenção manual: validação de PIX em tempo real, webhooks e entrega instantânea do produto

---

### Prumo RDO | App de Registro Diário de Obra
*React Native (Expo) · TypeScript · Supabase | Projeto em equipe para uma construtora real*
- Substitui os registros de obra em papel e WhatsApp por um app com funcionamento offline, assinatura digital e geração de PDF
- Fui responsável pela especificação de requisitos e pelas regras de negócio

---

### Ecos do Maracanã | Museu em Realidade Virtual
*Unity · C# · Meta Quest*
- Experiência imersiva em VR sobre o patrimônio cultural maranhense, com artefatos interativos e narração

---

## 🛠️ Tecnologias

**Linguagens:** Python · TypeScript · JavaScript · C# · Rust
**Backend:** FastAPI · Node.js · REST APIs · filas assíncronas · webhooks
**Frontend, Desktop e Mobile:** Next.js · React · React Native (Expo) · Tauri · Tailwind CSS · Unity
**Dados e Infraestrutura:** PostgreSQL · Supabase · Prisma · SQLite · Redis · Cloudflare Workers · Vercel · Sentry · Git
**IA:** LLMs e IA generativa · prompt engineering · desenvolvimento assistido por IA (Claude Code)

---

## 📫 Contato

- LinkedIn: [linkedin.com/in/ryk-medeiros](https://www.linkedin.com/in/ryk-medeiros)
- E-mail: [rick.medeiros223@icloud.com](mailto:rick.medeiros223@icloud.com)

*Aberto a oportunidades de estágio e vagas júnior em Engenharia de Software: remoto ou em São Luís/MA.*

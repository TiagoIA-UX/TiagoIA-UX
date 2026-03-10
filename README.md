# Tiago Rocha

Construo produtos digitais completos — do conceito ao deploy em produção — usando IA como copiloto de engenharia.

---

## O que eu faço

Crio aplicações web full-stack reais, publicadas e funcionais. Meus projetos vão além de protótipos: têm autenticação, pagamentos, integrações com APIs externas, deploy automatizado e arquitetura para múltiplos clientes.

## Stack principal

| Camada | Tecnologias |
|--------|-------------|
| **Frontend** | Next.js · React · TypeScript · Tailwind CSS · Radix UI |
| **Backend** | Next.js API Routes · Node.js · Supabase · Prisma · Neon |
| **Auth** | Supabase Auth (Google OAuth) · JWT · Middleware de sessão |
| **Pagamentos** | Mercado Pago (checkout, webhook, sandbox/produção) |
| **IA** | Groq (LLaMA) · OpenAI · Geração automática de conteúdo |
| **Integrações** | Google Calendar API · WhatsApp Business · Resend Email |
| **Infra** | Vercel · GitHub Actions CI · Rate Limiting · SEO técnico |
| **Qualidade** | ESLint · Testes automatizados · Scripts de validação (`ship:all`) |
| **Estado** | Zustand · React Hook Form · Zod |

## Projetos em destaque

### [Cardápio Digital](https://github.com/TiagoIA-UX/Card-pio-Digital)

Plataforma SaaS multi-tenant para restaurantes criarem cardápios digitais profissionais com pedidos via WhatsApp.

- **Arquitetura multi-tenant** com isolamento por tenant (slug único, banco compartilhado)
- **Editor visual** com preview em tempo real e edição inline de textos e produtos
- **7 templates** responsivos com personalização de cores, fontes e conteúdo
- **Checkout completo** com Mercado Pago (PIX + cartão), onboarding automatizado e provisionamento
- **Painel administrativo** com métricas, gestão de produtos/categorias e assinaturas
- **Middleware de autenticação** centralizado com rate limiting e proteção de rotas
- **Pipeline de qualidade**: doctor → lint → testes → simulação de onboarding (`ship:all`)
- **SEO técnico**: sitemap, robots.txt, meta tags dinâmicas, Schema.org

### [Blog Terapia — Elisa Rietjens](https://github.com/TiagoIA-UX/blog-terapia-elisa-rietjens)

Sistema completo de automação para terapeutas: blog com geração de conteúdo por IA, chatbot, agendamento e pagamentos.

- **Geração automática de conteúdo** via Groq/LLaMA com lote diário configurável
- **Chatbot de qualificação** integrado para captura de leads
- **Agendamento online** com Google Calendar API (disponibilidade, reserva, cancelamento, reagendamento)
- **Checkout** com Mercado Pago e webhooks de confirmação
- **Publicação multi-canal**: cada artigo gera conteúdo para Instagram, Facebook, LinkedIn, X e TikTok
- **Persistência híbrida**: Prisma + Neon em produção, fallback local em dev
- **CI/CD**: GitHub Actions, validação de ambiente, build strict

## Competências demonstradas

- **Produto**: visão end-to-end, de ideia a deploy em produção com domínio próprio
- **Engenharia**: arquitetura limpa, multi-tenant, testes, validação automatizada
- **Integrações**: pagamentos, OAuth, calendário, IA generativa, mensageria
- **Operações**: deploy Vercel, CI, monitoramento, scripts de diagnóstico
- **IA como ferramenta de produção**: uso de IA para acelerar o desenvolvimento com código auditável e versionado

## Contato

- 📧 zairyx.ai@gmail.com
- 📱 +55 12 99688-7993

---

*Projetos em evolução contínua. Código aberto e pronto para contribuição.*

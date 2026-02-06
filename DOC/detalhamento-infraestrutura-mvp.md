[🏠 Voltar para o README](../README.md)
[⬅ Voltar para Estimativas](./estimativas-cronograma.md)

# Detalhamento de Infraestrutura – MVP (~R$ 500/mês)

Este documento detalha **o que significa o custo de infraestrutura de um MVP estimado em ~R$ 500/mês**, deixando claro:
- o que está incluído
- o que não está incluído
- por que esse valor é suficiente para validação inicial

---

## Conceito de MVP

MVP (Minimum Viable Product) é uma versão do sistema pensada para:
- validar o produto no mercado
- atender poucos usuários
- operar com baixo custo
- evitar investimento prematuro em escala

👉 **Esse custo NÃO inclui desenvolvimento**, apenas **manutenção do sistema no ar**.

---

## Infraestrutura Incluída no MVP

### 1. Backend (API)
**Custo estimado:** R$ 200/mês  

Serviços possíveis:
- Railway
- Render
- Fly.io

Inclui:
- API principal
- Autenticação
- Regras de negócio
- Integrações básicas

Limitações:
- 1 instância
- Sem alta disponibilidade
- Recursos limitados

---

### 2. Banco de Dados
**Custo estimado:** R$ 100/mês  

Serviços possíveis:
- Supabase
- Neon
- Railway PostgreSQL

Inclui:
- PostgreSQL gerenciado
- Backups básicos
- Conexões limitadas

Adequado para:
- até ~5.000 usuários/mês
- baixo volume de escrita simultânea

---

### 3. Storage e CDN
**Custo estimado:** R$ 50/mês  

Serviços possíveis:
- Cloudflare R2
- S3 compatível

Utilizado para:
- imagens dos ativos
- documentos
- anexos

Custo cresce apenas com volume.

---

### 4. Frontend
**Custo estimado:** R$ 100/mês  

Serviços possíveis:
- Vercel Pro
- Netlify Pro

Inclui:
- Deploy automático
- CDN global
- SSL
- Domínio configurado

---

### 5. E-mail Transacional
**Custo estimado:** R$ 50/mês  

Serviços possíveis:
- SendGrid
- Resend
- Amazon SES

Utilizado para:
- confirmação de cadastro
- recuperação de senha
- notificações básicas

---

## Resumo de Custos

| Item | Valor |
|----|------|
| Backend | R$ 200 |
| Banco de Dados | R$ 100 |
| Storage/CDN | R$ 50 |
| Frontend | R$ 100 |
| E-mail | R$ 50 |
| **Total estimado** | **~R$ 500/mês** |

---

## O que NÃO está incluído neste valor

- Alta disponibilidade (HA)
- Escala automática
- Cache distribuído (Redis)
- Analytics avançado
- Monitoramento pago (Datadog, NewRelic)
- Infraestrutura para alto volume
- Custos de gateway de pagamento

👉 Esses itens só fazem sentido **após validação do negócio**.

---

## Quando esse MVP deixa de ser suficiente?

Normalmente quando:
- usuários > 5.000/mês
- uploads frequentes
- uso intenso de chat
- crescimento de transações

Nesse ponto, o custo médio sobe para:
👉 **R$ 2.500 – R$ 3.500/mês**

---

## Por que começar com MVP barato?

- Reduz risco financeiro
- Permite pivotar rapidamente
- Evita overengineering
- Facilita validação com investidores

> MVP barato é decisão estratégica, não limitação técnica.

---

## Conclusão

O custo de **~R$ 500/mês** representa:
- infraestrutura mínima
- operação estável
- foco total em validação

Ideal para primeiros meses do produto.


[🏠 Voltar para o README](../README.md)

# Estimativas e Cronograma – Versão Consolidada (10 meses | 2 devs)

Este documento apresenta uma versão **refinada, organizada e executável** do cronograma do projeto, considerando:
- Escopo detalhado validado
- Base de estimativas técnicas existente
- **Time de 2 desenvolvedores (1 Frontend + 1 Backend)**
- Execução em **10 meses (≈40 semanas)**

---

## Premissas Gerais

- Jornada: 40h semanais por dev
- Metodologia: entregas incrementais por módulo
- Front e Back trabalhando **em paralelo sempre que possível**
- Buffer implícito de risco (~15% distribuído no cronograma)

---

## Visão Macro do Cronograma (10 meses)

| Mês | Foco Principal |
|----|----------------|
| 1 | Setup + Fundamentos |
| 2–3 | Infraestrutura Core |
| 4–5 | Módulo Público |
| 6 | Módulo do Vendedor |
| 7 | Módulo do Consultor |
| 8 | Módulo Administrativo |
| 9 | Negociação e Financeiro |
| 10 | Testes, Polimento e Go-live |

---

## Detalhamento por Mês

## Mês 1 – Setup e Preparação
**Objetivo:** criar base técnica sólida.

Backend:
- Setup de repositório e CI/CD
- Configuração inicial do banco e migrations
- Estrutura base da API

Frontend:
- Setup do projeto (Next.js)
- Definição de design system
- Layout base e navegação

Entrega:
- Projeto executável ponta-a-ponta
- Ambiente pronto para escala

---

## Meses 2 e 3 – Infraestrutura Core
**Objetivo:** construir o “motor” do sistema.

Backend:
- Autenticação e autorização (JWT + RBAC)
- Sistema de campos dinâmicos
- Segmentos e filtros dinâmicos
- Upload de arquivos
- Auditoria e logs básicos

Frontend:
- Autenticação (login/registro)
- Componentes de formulário dinâmico
- UI de filtros
- Integração com upload

Entrega:
- Core reutilizável para todos os módulos
- Base estável para evolução

---

## Meses 4 e 5 – Módulo Público
**Objetivo:** produto visível e validável.

Backend:
- Listagem de ativos
- Busca e filtros avançados
- Página de detalhes com níveis de visibilidade
- Contador de visualizações

Frontend:
- Home / Feed
- Página do ativo
- Favoritos
- Responsividade mobile

Entrega:
- Plataforma navegável e demonstrável
- Primeira versão utilizável por usuários finais

---

## Mês 6 – Módulo do Vendedor
**Objetivo:** permitir entrada de oferta no sistema.

Backend:
- API de pré-cadastro de ativos
- Workflow de status
- Sistema de notificações

Frontend:
- Wizard de cadastro (multi-etapas)
- Dashboard do vendedor
- Acompanhamento de status

Entrega:
- Fluxo completo de submissão de ativos

---

## Mês 7 – Módulo do Consultor
**Objetivo:** operação humana do negócio.

Backend:
- Atribuição de ativos
- Atendimento
- SLA
- Chat em tempo real

Frontend:
- Dashboard do consultor
- Estruturação de ativos
- Interface de atendimento
- Chat

Entrega:
- Operação funcional do marketplace

---

## Mês 8 – Módulo Administrativo
**Objetivo:** governança e controle.

Backend:
- Gestão de usuários
- Gestão de consultores
- Regras operacionais e financeiras
- Relatórios básicos

Frontend:
- Dashboard administrativo
- Aprovação de ativos
- CRUDs de configuração

Entrega:
- Controle total do sistema

---

## Mês 9 – Negociação e Financeiro
**Objetivo:** monetização.

Backend:
- Propostas
- Negociação
- NDA
- Integração com gateway
- Sistema de comissões

Frontend:
- Interface de propostas
- Negociação
- Assinatura de NDA

Entrega:
- Fluxo comercial completo

---

## Mês 10 – Polimento e Testes
**Objetivo:** estabilidade e qualidade.

- Testes unitários
- Testes de integração
- Testes E2E
- Correção de bugs
- Otimização de performance
- Documentação técnica

Entrega:
- Produto pronto para produção

---

## Observações Importantes

- MVP pode ser antecipado no **mês 4**
- Funcionalidades avançadas podem ser postergadas sem impacto estrutural
- Cronograma permite absorver pequenas mudanças sem colapso




# Estimativas e Cronograma – Versão Consolidada com Custos
**Horizonte:** 10 meses  
**Time:** 2 desenvolvedores (1 Backend + 1 Frontend)  

Documento alinhado às estimativas detalhadas.

---

## Premissas Financeiras

| Perfil | Valor mensal |
|------|--------------|
| Dev Backend Pleno | R$ 10.000 |
| Dev Frontend Pleno | R$ 10.000 |
| **Custo mensal do time** | **R$ 20.000** |

---

## Cronograma Financeiro por Fase

### Mês 1 – Setup e Preparação
**Custo estimado:** R$ 20.000  
Atividades:
- Setup CI/CD, banco, frontend base
- Design system inicial

---

### Meses 2 e 3 – Infraestrutura Core
**Duração:** 2 meses  
**Custo:** R$ 40.000  

Inclui:
- Autenticação, RBAC
- Campos dinâmicos, segmentos, filtros
- Upload e auditoria

---

### Meses 4 e 5 – Módulo Público
**Duração:** 2 meses  
**Custo:** R$ 40.000  

Inclui:
- Feed de ativos
- Página de detalhes
- Busca, filtros e favoritos
- Responsividade

---

### Mês 6 – Módulo do Vendedor
**Custo:** R$ 20.000  

Inclui:
- Wizard de cadastro
- Dashboard do vendedor
- Workflow de status

---

### Mês 7 – Módulo do Consultor
**Custo:** R$ 20.000  

Inclui:
- Dashboard
- Atendimento
- Chat e SLA

---

### Mês 8 – Módulo Administrativo
**Custo:** R$ 20.000  

Inclui:
- Gestão de usuários
- Aprovação de ativos
- Regras e relatórios

---

### Mês 9 – Negociação e Financeiro
**Custo:** R$ 20.000  

Inclui:
- Propostas
- NDA
- Gateway de pagamento
- Comissões

---

### Mês 10 – Testes e Polimento
**Custo:** R$ 20.000  

Inclui:
- Testes unitários, integração e E2E
- Correções
- Performance
- Documentação

---

## Resumo Geral de Custos

| Item | Valor |
|----|-------|
| Desenvolvimento (10 meses) | **R$ 200.000** |
| Infraestrutura MVP (10 meses) | R$ 5.000 |
| Buffer de contingência (10%) | R$ 20.000 |
| **Custo total estimado** | **R$ 225.000** |

---

## Infraestrutura (referência)

**MVP:** ~R$ 500/mês  [⬅ ver mais detalhes...](./detalhamento-infraestrutura-mvp.md)
**Produção:** ~R$ 3.100/mês [⬅ ver mais detalhes...](./detalhamento-infraestrutura-producao.md)

---

## Observações Executivas

- MVP funcional possível entre os meses 4 e 5
- Cronograma defensável para proposta comercial
- Valores compatíveis com mercado PJ Brasil (2026)


---

## Conclusão

Este planejamento é **realista, defensável e apresentável** para:
- Investidores
- Clientes
- Times técnicos
- Gestão executiva
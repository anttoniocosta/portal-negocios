[🏠 Voltar para o README](../README.md)

# Planejamento Estratégico do Projeto  
Portal de Negócios – Fase 1  
Versão 1.0

---

# 1. Visão Estratégica

O Portal de Negócios é uma plataforma estruturada para intermediação e governança de ativos de alto valor.

Seu propósito não é apenas listar ativos, mas estruturar um ambiente com:

- Governança operacional
- Intermediação profissional por consultores
- Controle administrativo centralizado
- Rastreabilidade completa das negociações
- Modelo financeiro auditável
- Escalabilidade por regras dinâmicas de segmento

O sistema será desenvolvido com foco em sustentabilidade operacional e monetização estruturada.

---

# 2. Objetivos do Projeto

## 2.1 Objetivos de Negócio

- Estruturar marketplace com governança e intermediação controlada
- Permitir monetização via:
  - Comissão por fechamento
  - Fee fixo por segmento
  - Impulsionamento de ativos
- Garantir rastreabilidade completa das negociações
- Sustentar modelo financeiro auditável

---

## 2.2 Objetivos Técnicos

- Arquitetura escalável
- Controle por papéis (RBAC)
- Sistema dinâmico por segmento
- Modularização por perfil
- Estrutura auditável
- Preparação para crescimento futuro

---

# 3. Perfis Operacionais

O sistema será dividido em cinco perfis principais:

- Visitante (não autenticado)
- Comprador
- Vendedor
- Consultor
- Administrador

Cada perfil possui:

- Responsabilidades específicas
- Fluxos independentes
- Permissões controladas por RBAC

Os fluxos detalhados estão documentados em:
**Fluxos:**  [⬅ ver mais detalhes...](./fluxos.md)


---

# 4. Estrutura Modular do Produto

## 4.1 Módulo Público
- Listagem estruturada de ativos
- Filtros por segmento
- Visualização parcial de detalhes
- Registro e login

## 4.2 Módulo Comprador
- Filtro avançado
- Visualização detalhada conforme permissão
- Início de negociação
- Chat com consultor
- Acompanhamento de status

## 4.3 Módulo Vendedor
- Pré-cadastro de ativo
- Workflow de aprovação
- Gestão de ativos
- Impulsionamento

## 4.4 Módulo Consultor
- Gestão de ativos atribuídos
- Estruturação de conteúdo
- Gestão de negociações
- Registro de visitas
- Registro de fechamentos
- Visualização de comissões

## 4.5 Módulo Administrativo
- Aprovação de ativos
- Gestão de usuários
- Gestão de consultores
- Configuração de segmentos e campos dinâmicos
- Configuração de regras financeiras
- Auditoria completa de negociações
- Validação de fechamentos
- Gestão de pagamentos
- Relatórios operacionais

---

# 5. Estrutura de Governança

A governança operacional é um dos pilares do projeto.

## 5.1 Pontos de Controle (Gates)

- Ativos somente são publicados após aprovação administrativa
- Consultores somente operam após validação contratual
- Fechamentos somente são reconhecidos após validação administrativa

## 5.2 Regras Dinâmicas por Segmento

Cada segmento poderá definir:

- Campos obrigatórios
- Comissão do portal
- Comissão do consultor
- Fee fixo
- Regras específicas de exibição

---

# 6. Estratégia de MVP

O MVP da Fase 1 deverá conter:

## Essencial

- Autenticação e controle de papéis
- Cadastro e aprovação de ativos
- Listagem pública
- Negociação básica (chat)
- Registro de fechamento
- Validação administrativa
- Cálculo simples de comissão

## Postergado para Fase 2

- Relatórios avançados
- Dashboard financeiro expandido
- Impulsionamento avançado
- Métricas detalhadas por consultor
- Pagamentos parciais complexos
- Analytics comportamental

---

# 7. Fases de Desenvolvimento

## Fase 1 – Setup e Arquitetura
- Definição da stack
- Configuração de ambientes
- Modelagem inicial
- Estrutura de RBAC

## Fase 2 – Core do Sistema
- Autenticação
- Estrutura base de usuários
- Segmentos e campos dinâmicos
- Modelo de ativos

## Fase 3 – Fluxo Vendedor
- Pré-cadastro
- Aprovação
- Publicação

## Fase 4 – Fluxo Comprador
- Filtros
- Visualização detalhada
- Negociação
- Chat

## Fase 5 – Fluxo Consultor
- Gestão de ativos
- Registro de fechamento
- Controle financeiro básico

## Fase 6 – Módulo Administrativo Completo
- Gestão de consultores
- Regras financeiras
- Auditoria
- Pagamentos

## Fase 7 – Hardening
- Logs estruturados
- Auditoria reforçada
- Performance
- Segurança
- Testes automatizados

---

# 8. Critérios de Sucesso

O projeto será considerado bem-sucedido quando:

- Ativos puderem ser publicados com fluxo validado
- Negociações forem rastreáveis ponta-a-ponta
- Fechamentos forem auditáveis
- Comissões forem calculadas automaticamente
- Governança operacional estiver funcional
- Arquitetura estiver preparada para expansão por segmento

---

# 9. Direcionamento Estratégico

O diferencial do Portal de Negócios não é apenas a listagem de ativos.

Seu diferencial está em:

- Governança
- Intermediação estruturada
- Rastreabilidade financeira
- Modelo escalável por segmento
- Controle administrativo robusto

Todas as decisões técnicas e funcionais devem preservar esses pilares.

---

# 10. Próximos Passos

1. Validação formal do MVP
2. Congelamento do escopo da Fase 1
3. Consolidação da modelagem de dados
4. Confirmação da stack tecnológica
5. Início do desenvolvimento do Core
[🏠 Voltar para o README](../README.md)

# Escopo Detalhado – Portal de Negócios  
Versão 1.0  
Documento de Escopo Formal

---

# 1. Objetivo do Documento

Este documento define o escopo funcional e técnico do Portal de Negócios, estabelecendo:

- Limites claros do projeto
- Funcionalidades incluídas na Fase 1
- Estrutura modular
- Cronograma macro
- Critérios de aceite
- Riscos e mitigações
- Exclusões formais de responsabilidade

Este documento serve como base para execução, validação e controle de mudanças.

---

# 2. Definição do Produto

O Portal de Negócios é uma plataforma digital para intermediação estruturada de ativos de alto valor, com:

- Governança operacional
- Intermediação por consultores especializados
- Controle administrativo centralizado
- Modelo financeiro auditável
- Regras dinâmicas por segmento

A solução não se limita a um marketplace tradicional.  
Trata-se de uma plataforma com rastreabilidade, controle e modelo financeiro estruturado.

---

# 3. Estrutura Modular do Sistema

O sistema será dividido nos seguintes módulos:

1. Módulo Público (Visitante)
2. Módulo Comprador
3. Módulo Vendedor
4. Módulo Consultor
5. Módulo Administrativo
6. Core Técnico

Cada módulo possui responsabilidades isoladas e regras próprias.

---

# 4. Escopo Funcional – Fase 1

## 4.1 Módulo Público (Visitante)

### Inclui:

- Listagem de ativos
- Filtros por segmento
- Ordenação de resultados
- Página detalhada pública
- Registro e login
- Recuperação de senha
- Responsividade mobile

### Não Inclui:

- Acesso a conteúdo confidencial
- Início de negociação sem autenticação
- Ranking avançado de impulsionamento

---

## 4.2 Módulo Comprador

### Inclui:

- Dashboard do comprador
- Filtro avançado
- Visualização detalhada completa (conforme permissões)
- Início de negociação
- Chat com consultor
- Histórico de negociações
- Acompanhamento de status
- Assinatura de NDA (quando habilitado)

### Dependências:

- Ativo previamente aprovado
- Consultor atribuído

---

## 4.3 Módulo Vendedor

### Inclui:

- Wizard estruturado de pré-cadastro
- Upload de imagens e documentos
- Campos dinâmicos por segmento
- Acompanhamento de status (em análise / aprovado / recusado)
- Dashboard do vendedor
- Notificações básicas

### Regra de Governança:

Ativos somente serão publicados após aprovação administrativa.

### Exclusões nesta fase:

- Sistema avançado de impulsionamento
- Sistema de ranking pago

---

## 4.4 Módulo Consultor

### Inclui:

- Dashboard do consultor
- Gestão de ativos atribuídos
- Edição e estruturação de conteúdo
- Definição de conteúdo confidencial
- Gestão de negociações
- Chat com interessados
- Registro de visitas
- Registro de fechamento
- Visualização de comissões
- Histórico de fechamentos

### Regra:

Acesso condicionado a contrato aprovado pelo administrativo.

---

## 4.5 Módulo Administrativo

### Gestão de Usuários

- Cadastro
- Bloqueio
- Atribuição de papéis (RBAC)

### Gestão de Consultores

- Aprovação contratual
- Ativação/Inativação
- Visualização de desempenho

### Gestão de Segmentos

- Criar / editar / inativar segmento
- Criar / editar campos dinâmicos
- Criar opções para selects
- Definir regras financeiras por segmento

### Gestão de Ativos

- Aprovação ou recusa
- Alteração de status
- Auditoria de conteúdo

### Gestão de Negociações

- Visualização completa de histórico
- Auditoria de conversas
- Validação administrativa de fechamento

### Financeiro

- Cálculo automático de comissão
- Fee fixo por segmento
- Registro de pagamentos
- Controle de pagamentos parciais
- Histórico financeiro auditável

### Relatórios

- Fechamentos por período
- Comissão por consultor
- Estatísticas operacionais básicas

---

# 5. Escopo Técnico

## 5.1 Core do Sistema

- Autenticação via JWT
- Autorização baseada em papéis (RBAC)
- Sistema de segmentos
- Sistema de campos dinâmicos
- Upload seguro de arquivos
- Sistema de notificações
- Log e auditoria
- API REST estruturada

---

## 5.2 Requisitos Não Funcionais

- Arquitetura preparada para escalabilidade horizontal
- Separação clara entre camadas
- Auditoria de ações sensíveis
- Performance otimizada para filtros dinâmicos
- Segurança contra acesso indevido a conteúdo confidencial

---

# 6. Cronograma Macro (10 Meses)

Mês 1 – Setup e Arquitetura  
Meses 2–3 – Core e Segmentos  
Meses 4–5 – Módulo Público  
Mês 6 – Módulo Vendedor  
Mês 7 – Comprador + Chat  
Mês 8 – Módulo Consultor  
Mês 9 – Financeiro e Auditoria  
Mês 10 – Hardening e Go-live  

---

# 7. Fora do Escopo da Fase 1

- Aplicativo mobile nativo
- Sistema avançado de recomendação
- Analytics comportamental avançado
- Marketplace white-label
- Automação jurídica completa
- Integrações bancárias profundas
- Impulsionamento com ranking complexo
- Garantia contratual de fechamento entre partes
- Due diligence automatizada

---

# 8. Riscos e Mitigações

## Riscos Técnicos

- Complexidade do modelo de campos dinâmicos
- Performance em filtros estruturados
- Crescimento não controlado de escopo

## Mitigações

- Prototipação antecipada do modelo dinâmico
- Índices planejados desde o início
- Versionamento de regras por segmento
- Processo formal de Change Request

---

# 9. Limites e Responsabilidades

O sistema:

- Fornece estrutura, rastreabilidade e governança
- Não substitui assessoria jurídica
- Não executa intermediação bancária direta
- Não garante fechamento entre partes

---

# 10. Critérios Formais de Aceite

O projeto será considerado entregue quando:

- Fluxo completo ativo → negociação → fechamento → validação financeira estiver funcional
- Segmentos e campos dinâmicos estiverem operacionais
- Cálculo de comissão ocorrer automaticamente
- Administração conseguir auditar todo o processo
- Sistema estiver testado e documentado
- Deploy em ambiente de produção estiver concluído

---

# 11. Controle de Mudanças

Qualquer alteração fora deste escopo:

- Será tratada como Change Request
- Será estimada separadamente
- Poderá impactar prazo e investimento
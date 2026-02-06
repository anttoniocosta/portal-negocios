[🏠 Voltar para o README](../README.md)

# Escopo Detalhado – Portal de Negócios
Planejamento alinhado ao cenário de execução em aproximadamente **10 meses** (time enxuto ou desenvolvimento sequencial), conforme modelo de estimativas e cronograma.

---

# 1. Visão Geral do Escopo

O projeto contempla o desenvolvimento de uma plataforma digital para negociação de ativos de alto valor, incluindo:

- Publicação e busca de ativos
- Interação entre compradores, vendedores e consultores
- Governança e auditoria
- Gestão administrativa
- Negociação e financeiro
- Escalabilidade e segurança

---

# 2. Estrutura de Módulos

## 2.1 Módulo Público
Funcionalidades previstas:

- Feed de ativos
- Busca avançada e filtros dinâmicos
- Página detalhada do ativo
- Sistema de favoritos
- Responsividade mobile
- Sistema de visualizações

---

## 2.2 Módulo do Comprador

- Dashboard do comprador
- Envio e acompanhamento de propostas
- Chat com consultores
- Assinatura de NDA
- Histórico de negociações

---

## 2.3 Módulo do Vendedor

- Wizard de cadastro de ativo
- Upload de imagens e documentos
- Acompanhamento de status do ativo
- Dashboard do vendedor
- Notificações de interesse e propostas

---

## 2.4 Módulo do Consultor

- Dashboard do consultor
- Atendimento de clientes
- Estruturação de ativos
- Sistema de SLA
- Chat em tempo real

---

## 2.5 Módulo Administrativo

- Gestão de ativos (aprovação e revisão)
- Gestão de usuários
- Gestão de consultores
- Configurações operacionais
- Relatórios gerenciais
- Auditoria e logs

---

## 2.6 Negociação e Financeiro

- Sistema de propostas
- Negociação entre partes
- Gestão de transações
- Sistema de comissões
- Integração com gateway de pagamento

---

# 3. Infraestrutura e Core do Sistema

Componentes fundamentais:

- Autenticação e autorização (JWT / RBAC)
- Sistema de campos dinâmicos
- Segmentação de ativos
- Upload de arquivos
- API de filtros dinâmicos
- Base de auditoria e logs

---

# 4. Cronograma Macro (10 meses)

Planejamento considerando desenvolvimento sequencial.

## Mês 1
Setup e preparação:
- Repositório e pipelines
- Ambiente de desenvolvimento
- Banco de dados inicial
- Estrutura base do frontend
- Design system inicial

## Meses 2 e 3
Infraestrutura Core:
- Autenticação e autorização
- Campos dinâmicos
- Segmentos e filtros
- Upload de arquivos
- Layout base e navegação

## Meses 4 e 5
Módulo Público:
- Feed e listagem
- Página de ativo
- Busca e filtros
- Favoritos
- Responsividade

## Mês 6
Módulo do Vendedor:
- Cadastro de ativos
- Dashboard do vendedor
- Workflow de status
- Notificações

## Mês 7
Módulo do Consultor:
- Dashboard
- Atendimento
- Chat
- SLA

## Mês 8
Módulo Administrativo:
- Gestão de usuários
- Gestão de ativos
- Configurações
- Auditoria
- Relatórios

## Mês 9
Negociação e Financeiro:
- Propostas
- NDA
- Integração com pagamentos
- Comissões

## Mês 10
Polimento e Testes:
- Testes unitários
- Testes de integração
- Testes E2E
- Correções e performance
- Documentação técnica

---

# 5. Fora do Escopo Inicial (MVP ou Versões Futuras)

- Aplicativo mobile nativo
- Analytics avançado
- Impulsionamento de ativos
- Integrações bancárias profundas
- Inteligência de recomendação

---

# 6. Riscos e Pontos de Atenção

Principais riscos identificados:

- Complexidade do sistema de campos dinâmicos
- Mudanças de escopo durante o desenvolvimento
- Performance com grande volume de dados
- Dependência de integrações externas

Mitigações:

- Prototipação antecipada
- Testes desde as primeiras fases
- Planejamento incremental
- Controle de mudanças formal

---

# 7. Próximos Passos

1. Validar escopo com stakeholders
2. Definir MVP inicial
3. Definir equipe e papéis
4. Escolher stack definitiva
5. Criar protótipo de interface
6. Iniciar desenvolvimento

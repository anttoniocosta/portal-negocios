[🏠 Voltar para o README](../README.md)

# Fluxos do Sistema

Este documento descreve os fluxos principais da plataforma por perfil de usuário, refletindo:
- Fluxogramas (Comprador/Vendedor, Consultor, Administrador)
- User stories (principalmente Admin, e estrutura geral do sistema)

---

### 📑 Fluxogramas (PDF)

- 📄 [Administrador](./PDF/fluxograma-administrador.pdf)
- 📄 [Comprador / Vendedor](./PDF/fluxograma-comprador-vendedor.pdf)
- 📄 [Consultor](./PDF/fluxograma-consultor.pdf)

---

## Sumário
- [1. Fluxo do Visitante (não logado)](#1-fluxo-do-visitante-não-logado)
- [2. Fluxo do Comprador (logado)](#2-fluxo-do-comprador-logado)
- [3. Fluxo do Vendedor (logado)](#3-fluxo-do-vendedor-logado)
- [4. Fluxo do Consultor](#4-fluxo-do-consultor)
- [5. Fluxo do Administrador](#5-fluxo-do-administrador)
- [6. Estados e pontos de controle](#6-estados-e-pontos-de-controle)

---

## 1. Fluxo do Visitante (não logado)

Baseado no fluxo público de acesso, com áreas limitadas para não autenticados. :contentReference[oaicite:1]{index=1}

1. Usuário acessa o portal
2. Sistema verifica autenticação
3. Se **não estiver logado**, usuário pode:
   - Recuperar conta / Esqueci senha
   - Registrar-se
   - Navegar em **áreas públicas**:
     - Lista de ativos (com limitações)
     - Filtro de ativos (limitado)
     - Detalhes do ativo (somente informações públicas)
4. Ativos impulsionados aparecem com prioridade na listagem (quando aplicável)

---

## 2. Fluxo do Comprador (logado)

Fluxo focado em descobrir ativos, interagir e iniciar negociação. :contentReference[oaicite:2]{index=2}

### 2.1 Descoberta de ativos
1. Acessa a lista de ativos
2. Aplica filtros (segmento, etc.)
3. Segmentos podem influenciar a estrutura do que é exibido (campos dinâmicos)
4. Visualiza detalhes do ativo

### 2.2 Interesse e negociação
5. A partir do detalhe do ativo:
   - Inicia negociação
   - Abre chat com consultor
6. Acompanha evolução da negociação (status, mensagens, etc.)
7. Recebe notificações relevantes do processo

### 2.3 Pós-fechamento
8. Quando houver fechamento validado no sistema:
   - Comprador acompanha conclusão
   - (Pagamentos e validações são controlados via Consultor/Admin quando aplicável)

---

## 3. Fluxo do Vendedor (logado)

Fluxo voltado ao anúncio de ativos e (opcionalmente) impulsionamento. :contentReference[oaicite:3]{index=3}

### 3.1 Anunciar ativo (pré-cadastro → análise → publicação)
1. Inicia anúncio
2. Realiza pré-cadastro do ativo
3. Acompanha análise do ativo
4. (Após aprovação) ativo é publicado e passa a aparecer na lista

### 3.2 Gestão do anúncio
5. Visualiza seus anúncios / ativos
6. Recebe notificações sobre:
   - Aprovação/recusa
   - Mudanças no status
   - Interesses/negociações

### 3.3 Impulsionamento (monetização)
7. Vendedor pode optar por impulsionar ativo:
   - Escolhe plano
   - Realiza pagamento
   - Ativo impulsionado ganha prioridade na lista (regra de ordenação)

---

## 4. Fluxo do Consultor

Fluxo operacional do consultor: acesso, gestão de ativos atribuídos, negociações, visitas e financeiro. :contentReference[oaicite:4]{index=4}

### 4.1 Entrada e liberação de acesso
1. Consultor realiza registro na plataforma
2. Acompanha status de assinatura/contrato
3. Acessa plataforma
4. Sistema valida: **Contrato aprovado?**
   - Se sim: acesso liberado

### 4.2 Operação diária
5. Visualiza notificações
6. Edita informações do perfil
7. Visualiza visitas e agendamentos
8. Visualiza ativos atribuídos
   - Cadastra/edita conteúdo do ativo
   - Define conteúdo confidencial (quando aplicável)

### 4.3 Negociação
9. Visualiza negociações
10. Para cada negociação, pode:
   - Ver novos interessados
   - Iniciar conversas no chat
   - Registrar observações
   - Liberar conteúdo confidencial (quando necessário)
   - Encerrar negociação e informar motivo

### 4.4 Fechamento e financeiro
11. Em caso de fechamento:
   - Fechar negociação
   - Registrar financeiro
   - Chat pode ser arquivado
   - Ativo pode ser marcado como indisponível
12. Módulo financeiro do consultor:
   - Visualizar desempenho
   - Visualizar comissões
   - Ver lista de fechamentos
   - Registrar pagamento (quando aplicável)

---

## 5. Fluxo do Administrador

Fluxo administrativo completo: governança do sistema, usuários, consultores, ativos, negociações, regras, contratos e financeiro. 

### 5.1 Central de notificações
1. Visualiza notificações do sistema
2. Marca notificações como lidas

### 5.2 Gestão de usuários e permissões
3. Acessa módulo de usuários
4. Ações disponíveis:
   - Cadastrar novos usuários
   - Atribuir permissões/papéis
   - Bloquear usuário

### 5.3 Gestão de consultores
5. Acessa módulo de consultores
6. Ações disponíveis:
   - Listar consultores
   - Editar consultor
   - Inativar/ativar consultor
   - Aprovar consultores (inclui aprovação de contrato/assinatura)
   - Visualizar ativos por consultor

### 5.4 Governança de segmentos (estrutura do marketplace)
7. Acessa módulo de segmentos
8. Ações disponíveis:
   - Criar / editar / inativar segmento
   - Criar / editar / ativar/inativar campos dinâmicos por segmento
   - Criar / editar / remover opções (campos do tipo select)
   - Definir regras por segmento:
     - Comissão do portal
     - Comissão do consultor
     - Fee fixo

### 5.5 Contratos
9. Acessa módulo de contratos
10. Ações disponíveis:
   - Criar / editar / inativar contrato
   - Vincular contrato a segmento

### 5.6 Ativos (aprovação e gestão global)
11. Acessa ativos
12. Subfluxos:
   - **Lista de pré-cadastros em aprovação**
     - Aprovar ativo (publica)
     - Recusar ativo (com motivo)
   - **Listagem e gerenciamento global**
     - Filtrar por segmento/status/consultor
     - Alterar status (ativo, suspenso, vendido etc.)
     - Auditar conteúdo (inclusive confidencial)

### 5.7 Negociações e visitas
13. Acessa listagem de negociações
14. Visualiza histórico completo da negociação (chat, visita, contratos, etc.)
15. Acessa gerenciamento de visitas (auditoria e acompanhamento)

### 5.8 Validação de fechamentos + pagamentos (controle auditável)
16. Visualiza fechamentos marcados como concluídos pelo consultor
17. Aprova ou marca como pendente
18. Audita cálculo automático (comissão portal + fee consultor)
19. Registra pagamentos:
   - Manual e auditável
   - Pagamentos parciais
   - Confirmação/recusa
   - Histórico por fechamento

### 5.9 Relatórios
20. Acessa relatórios e dashboards:
   - Resumo de comissões
   - Estatísticas de vendas
   - Gráficos de desempenho de consultores
   - Relatórios de pagamentos por período/status

---

## 6. Estados e pontos de controle

### 6.1 Pontos de aprovação (gates)
- Publicação de ativo depende de aprovação (Admin)
- Acesso efetivo de consultor depende de contrato aprovado (Admin)

### 6.2 Regras que impactam fluxo
- Ativos impulsionados aparecem com prioridade na listagem
- Segmentos definem campos obrigatórios (campos dinâmicos) e regras financeiras
- Fechamento exige validação administrativa para controle financeiro

---

## Fontes e rastreabilidade
- Fluxo Comprador/Vendedor (diagrama): ver arquivo de fluxo. 
- Fluxo Consultor (diagrama): ver arquivo de fluxo.
- Fluxo Administrador (diagrama): ver arquivo de fluxo.
- User Stories (Admin e estrutura): ver arquivo de funcionalidades.
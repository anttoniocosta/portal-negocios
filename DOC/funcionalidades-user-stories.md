[⬅ Voltar para o README](../README.md)

# Funcionalidades / User Stories  
Portal de Negócios – Fase 1

Este documento descreve as funcionalidades do sistema organizadas por perfil de usuário, alinhadas aos fluxos operacionais definidos.

---

# ADMINISTRADOR
**Alinhado ao fluxo do PDF** [⬅ ver mais detalhes...](./PDF/fluxograma-administra.md)


## 1. Segmentos

- [ ] Como administrador, quero criar um novo segmento para organizar ativos por categoria.
- [ ] Como administrador, quero editar um segmento para ajustar sua estrutura.
- [ ] Como administrador, quero inativar um segmento para impedir novos cadastros.
- [ ] Como administrador, quero definir regras financeiras por segmento.
- [ ] Como administrador, quero configurar comissão do portal por segmento.
- [ ] Como administrador, quero configurar comissão do consultor por segmento.
- [ ] Como administrador, quero definir fee fixo por segmento.

---

## 2. Campos Dinâmicos

- [ ] Como administrador, quero criar campos dinâmicos por segmento.
- [ ] Como administrador, quero definir tipo do campo (texto, número, select, data).
- [ ] Como administrador, quero definir campo obrigatório/opcional.
- [ ] Como administrador, quero ativar/inativar campo.
- [ ] Como administrador, quero editar campo.
- [ ] Como administrador, quero remover campo.

### Select Dinâmico

- [ ] Como administrador, quero cadastrar opções de select.
- [ ] Como administrador, quero editar opções.
- [ ] Como administrador, quero remover opções.

---

## 3. Contratos

- [ ] Como administrador, quero cadastrar contratos padrão.
- [ ] Como administrador, quero editar contrato.
- [ ] Como administrador, quero ativar/inativar contrato.
- [ ] Como administrador, quero vincular contrato a segmento.
- [ ] Como administrador, quero remover vínculo de contrato.

---

## 4. Usuários

- [ ] Como administrador, quero cadastrar usuário manualmente.
- [ ] Como administrador, quero atribuir papéis (BUYER, SELLER, CONSULTANT, ADMIN).
- [ ] Como administrador, quero alterar papéis.
- [ ] Como administrador, quero bloquear usuário.

---

## 5. Consultores

- [ ] Como administrador, quero listar consultores.
- [ ] Como administrador, quero editar consultor.
- [ ] Como administrador, quero ativar/inativar consultor.
- [ ] Como administrador, quero aprovar contrato de consultor.
- [ ] Como administrador, quero visualizar ativos por consultor.
- [ ] Como administrador, quero visualizar desempenho do consultor.

---

## 6. Ativos

- [ ] Como administrador, quero visualizar pré-cadastros pendentes.
- [ ] Como administrador, quero aprovar ativo.
- [ ] Como administrador, quero recusar ativo informando motivo.
- [ ] Como administrador, quero alterar status (ativo, suspenso, vendido).
- [ ] Como administrador, quero visualizar conteúdo confidencial.

---

## 7. Negociações

- [ ] Como administrador, quero visualizar todas negociações.
- [ ] Como administrador, quero auditar histórico completo.
- [ ] Como administrador, quero visualizar chats.
- [ ] Como administrador, quero validar fechamento.
- [ ] Como administrador, quero marcar fechamento como pendente.

---

## 8. Financeiro

- [ ] Como administrador, quero visualizar valores calculados automaticamente.
- [ ] Como administrador, quero registrar pagamento manual.
- [ ] Como administrador, quero registrar pagamento parcial.
- [ ] Como administrador, quero confirmar pagamento.
- [ ] Como administrador, quero recusar pagamento informado.
- [ ] Como administrador, quero visualizar histórico completo por fechamento.

---

## 9. Relatórios

- [ ] Como administrador, quero visualizar resumo de comissões.
- [ ] Como administrador, quero visualizar estatísticas de vendas.
- [ ] Como administrador, quero visualizar relatório por período.
- [ ] Como administrador, quero visualizar desempenho por consultor.

---

# CONSULTOR

**Alinhado ao fluxo do PDF** [⬅ ver mais detalhes...](./PDF/fluxograma-consultor.md)

## 1. Registro e Contrato

- [ ] Como consultor, quero me registrar na plataforma.
- [ ] Como consultor, quero acompanhar status da assinatura.
- [ ] Como consultor, quero assinar contrato.
- [ ] Como consultor, quero acessar a plataforma apenas após aprovação.

---

## 2. Dashboard

- [ ] Como consultor, quero visualizar ativos atribuídos.
- [ ] Como consultor, quero editar conteúdo do ativo.
- [ ] Como consultor, quero definir conteúdo confidencial.
- [ ] Como consultor, quero visualizar visitas agendadas.
- [ ] Como consultor, quero visualizar notificações.

---

## 3. Negociações

- [ ] Como consultor, quero visualizar interessados.
- [ ] Como consultor, quero iniciar conversa no chat.
- [ ] Como consultor, quero registrar observações.
- [ ] Como consultor, quero encerrar negociação informando motivo.
- [ ] Como consultor, quero fechar negociação.
- [ ] Como consultor, quero registrar fechamento.

---

## 4. Financeiro

- [ ] Como consultor, quero visualizar comissões.
- [ ] Como consultor, quero visualizar desempenho.
- [ ] Como consultor, quero visualizar lista de fechamentos.
- [ ] Como consultor, quero registrar pagamento recebido.

---

# COMPRADOR

**Alinhado ao fluxo do PDF** Comprador/Vendedor [⬅ ver mais detalhes...](./PDF/fluxograma-comprador-vendedor.md)


## 1. Acesso

- [ ] Como comprador, quero me registrar.
- [ ] Como comprador, quero recuperar senha.
- [ ] Como comprador, quero acessar área restrita após login.

---

## 2. Exploração de Ativos

- [ ] Como comprador, quero visualizar lista de ativos.
- [ ] Como comprador, quero filtrar por segmento.
- [ ] Como comprador, quero ver ativos impulsionados primeiro.
- [ ] Como comprador, quero visualizar detalhes públicos.
- [ ] Como comprador, quero visualizar detalhes completos após autenticação.

---

## 3. Negociação

- [ ] Como comprador, quero iniciar negociação.
- [ ] Como comprador, quero conversar via chat com consultor.
- [ ] Como comprador, quero acompanhar status.
- [ ] Como comprador, quero solicitar visita.
- [ ] Como comprador, quero receber notificações.

---

# VENDEDOR

**Alinhado ao fluxo do PDF** Vendedor [⬅ ver mais detalhes...](./PDF/fluxograma-comprador-vendedor.md)


## 1. Cadastro de Ativo

- [ ] Como vendedor, quero iniciar pré-cadastro.
- [ ] Como vendedor, quero preencher campos dinâmicos.
- [ ] Como vendedor, quero anexar documentos.
- [ ] Como vendedor, quero enviar para análise.
- [ ] Como vendedor, quero acompanhar status.

---

## 2. Gestão

- [ ] Como vendedor, quero visualizar meus ativos.
- [ ] Como vendedor, quero editar ativo antes da aprovação.
- [ ] Como vendedor, quero acompanhar negociações.
- [ ] Como vendedor, quero receber notificação de interessados.

---

## 3. Impulsionamento (Fase 2)

- [ ] Como vendedor, quero escolher plano de impulsionamento.
- [ ] Como vendedor, quero realizar pagamento.
- [ ] Como vendedor, quero visualizar destaque ativo.

---

# VISITANTE

- [ ] Como visitante, quero visualizar lista de ativos.
- [ ] Como visitante, quero filtrar por segmento.
- [ ] Como visitante, quero visualizar detalhes públicos.
- [ ] Como visitante, quero me registrar para acessar recursos completos.
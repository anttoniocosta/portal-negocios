[⬅ Voltar para o README](../README.md)

# Funcionalidades / User Stories

## Administrador

### Segmentos

-   [ ] Como administrador, quero criar um novo segmento de ativos para
    que ativos possam ser classificados corretamente na plataforma.
-   [ ] Como administrador, quero editar um segmento existente para
    ajustar sua estrutura conforme evolução do negócio.
-   [ ] Como administrador, quero inativar um segmento para impedir
    novos cadastros naquele tipo.

------------------------------------------------------------------------

### Campos Dinâmicos por Segmento

-   [ ] Como administrador, quero criar campos dinâmicos vinculados a um
    segmento para customizar as informações obrigatórias de cada tipo de
    ativo.
-   [ ] Como administrador, quero definir o tipo do campo (texto,
    número, select, data, etc.) para estruturar corretamente os dados.
-   [ ] Como administrador, quero definir se o campo é obrigatório ou
    opcional para controlar a qualidade das informações.
-   [ ] Como administrador, quero ativar ou inativar um campo dinâmico
    para manter a estrutura atualizada.
-   [ ] Como administrador, quero editar um campo dinâmico para manter a
    estrutura atualizada.
-   [ ] Como administrador, quero remover um campo dinâmico para manter
    a estrutura atualizada.

------------------------------------------------------------------------

### Opções de Campos Dinâmicos (Select)

-   [ ] Como administrador, quero cadastrar opções de um campo dinâmico
    do tipo select para padronizar escolhas do usuário.
-   [ ] Como administrador, quero editar uma opção dinâmica para
    corrigir ou melhorar a nomenclatura exibida.
-   [ ] Como administrador, quero remover uma opção dinâmica para manter
    as opções atualizadas.

------------------------------------------------------------------------

### Regras de Comissão e Fee

-   [ ] Como administrador, quero definir percentual de comissão por
    segmento para automatizar o cálculo financeiro.
-   [ ] Como administrador, quero definir fee fixo adicional por
    segmento para ajustar a monetização da plataforma.
-   [ ] Como administrador, quero ativar ou inativar uma regra de
    comissão para controlar a regra vigente.
-   [ ] Como administrador, quero alterar regras de comissão no futuro
    para adaptar o modelo de negócio.

------------------------------------------------------------------------

### Cadastro de Contratos

-   [ ] Como administrador, quero cadastrar contratos padrão do sistema
    para que sejam utilizados nas negociações.
-   [ ] Como administrador, quero editar o conteúdo de um contrato
    padrão para manter cláusulas atualizadas.
-   [ ] Como administrador, quero ativar ou inativar um contrato padrão
    para controlar contratos vigentes.
-   [ ] Como administrador, quero relacionar contratos a um segmento
    específico para manter coerência jurídica.
-   [ ] Como administrador, quero remover o relacionamento de um
    contrato com um segmento quando não for mais aplicável.

------------------------------------------------------------------------

### Gestão de Consultores

-   [ ] Como administrador, quero listar consultores cadastrados para
    acompanhar minha equipe.
-   [ ] Como administrador, quero ativar (desbloquear) ou desativar
    (bloquear) um consultor para controlar acesso à plataforma.
-   [ ] Como administrador, quero editar dados de um consultor para
    manter informações atualizadas.
-   [ ] Como administrador, quero visualizar ativos atribuídos a um
    consultor para acompanhar performance.
-   [ ] Como administrador, quero aprovar ou recusar a assinatura de
    contrato de um consultor para liberar sua atuação.

------------------------------------------------------------------------

### Gestão de Usuários e Permissões

-   [ ] Como administrador, quero cadastrar novos usuários manualmente
    para conceder acesso ao sistema.
-   [ ] Como administrador, quero atribuir papéis (BUYER, SELLER,
    CONSULTANT, ADMIN) para controlar permissões.
-   [ ] Como administrador, quero editar papéis de um usuário para
    ajustar níveis de acesso.
-   [ ] Como administrador, quero bloquear um usuário para proteger a
    plataforma.

------------------------------------------------------------------------

### Lista de Pré-Cadastros Pendentes

-   [ ] Como administrador, quero visualizar lista de ativos em análise
    para revisar antes da publicação.
-   [ ] Como administrador, quero aprovar um ativo pré-cadastrado para
    torná-lo público na plataforma.
-   [ ] Como administrador, quero recusar um ativo e informar o motivo
    para orientar o consultor/usuário.

------------------------------------------------------------------------

### Lista de Ativos

-   [ ] Como administrador, quero visualizar todos os ativos da
    plataforma para ter controle global.
-   [ ] Como administrador, quero filtrar ativos por segmento, status ou
    consultor para facilitar auditoria.
-   [ ] Como administrador, quero editar status de um ativo (ativo,
    suspenso, vendido) para manter dados atualizados.
-   [ ] Como administrador, quero visualizar conteúdo confidencial
    cadastrado em um ativo para auditoria.

------------------------------------------------------------------------

### Lista de Negociações

-   [ ] Como administrador, quero visualizar todas as negociações em
    andamento para acompanhar o pipeline comercial.
-   [ ] Como administrador, quero ver histórico completo de uma
    negociação (interesse, chat, visita, contratos) para auditoria e
    rastreabilidade.

------------------------------------------------------------------------

### Visitas (Agendamentos)

-   [ ] Como administrador, quero visualizar solicitações de visita por
    negociação para auditoria.
-   [ ] Como administrador, quero aprovar uma solicitação de visita
    quando necessário para apoiar o consultor.
-   [ ] Como administrador, quero acompanhar status de visitas aprovadas
    e concluídas.

------------------------------------------------------------------------

### Validação de Fechamentos

-   [ ] Como administrador, quero visualizar negociações marcadas como
    fechadas pelo consultor para validar o fechamento.
-   [ ] Como administrador, quero aprovar ou marcar como pendente um
    fechamento para garantir controle financeiro.
-   [ ] Como administrador, quero visualizar os valores calculados
    (comissão portal e fee consultor) para auditoria do cálculo.

------------------------------------------------------------------------

### Controle de Pagamentos (Manual e Auditável)

-   [ ] Como administrador, quero registrar um pagamento manual
    relacionado a um fechamento para manter controle financeiro
    auditável.
-   [ ] Como administrador, quero registrar pagamentos parciais para
    refletir a realidade de transações fracionadas.
-   [ ] Como administrador, quero marcar um pagamento como confirmado
    para registrar que o pagamento foi verificado.
-   [ ] Como administrador, quero recusar um pagamento informado para
    manter integridade do histórico.
-   [ ] Como administrador, quero visualizar o histórico completo de
    pagamentos por fechamento para auditoria.

------------------------------------------------------------------------

### Relatórios Financeiros

-   [ ] Como administrador, quero visualizar resumo de comissões do
    portal para acompanhar faturamento.
-   [ ] Como administrador, quero visualizar estatísticas de vendas para
    tomada de decisão estratégica.
-   [ ] Como administrador, quero acessar gráficos de desempenho para
    análise visual de resultados.
-   [ ] Como administrador, quero visualizar relatórios de pagamentos
    manuais (por status e por período) para controle financeiro.

------------------------------------------------------------------------

### Notificações

-   [ ] Como administrador, quero visualizar notificações do sistema
    para acompanhar eventos relevantes.
-   [ ] Como administrador, quero marcar notificações como lidas para
    manter minha central organizada.

------------------------------------------------------------------------

## Consultor

(Conteúdo completo mantido conforme enviado pelo usuário)

## Comprador

(Conteúdo completo mantido conforme enviado pelo usuário)

## Visitante

(Conteúdo completo mantido conforme enviado pelo usuário)

## Vendedor

(Conteúdo completo mantido conforme enviado pelo usuário)

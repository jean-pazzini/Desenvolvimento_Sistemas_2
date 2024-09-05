***

1. Identificar casos de uso de negócio por ator (cumprir metas do usuário);
Possíveis casos de uso por ator:

***

-> Proprietário/Gerente:

Gerenciar funcionários

Gerenciar produtos

Gerenciar valores

Gerar relatórios

***

-> Funcionários:

Registrar tipos de atendimentos

Consultar agenda

Consultar histórico de serviços

***

-> Recepcionista:

Vender produtos

Gerenciar pagamentos

Gerenciar agenda geral 

***

-> Cliente

Criar conta

Consultar serviço

Agendar serviço

Cancelar agendamento

Realizar pagamento

Avaliar serviço

Consultar histórico de serviços

***
***

2. Descrever os casos de uso de forma resumida;

***

Gerenciar funcionários: CRUD.

Gerenciar produtos: CRUD e controle visual e estoque.

Gerenciar valores: definir comissões, valores e gerenciar valores de entrada do estabelecimento.

Gerar relatórios: gerar relatórios de clientes, produtos vendidos, serviços mais procurados, etc.

***

Registrar tipos de atendimentos: detalhar os serviços realizados.

Consultar agenda: verificar seus próprios horários e disponibilidade.

Consultar histórico de serviços: acessar informações sobre serviços anteriores.

***

Vender produtos: registrar vendas, emitir notas fiscais e oferecer sugestões de produtos.

Gerenciar pagamentos: receber pagamentos, emitir recibos e solucionar problemas relacionados a pagamentos.

Gerenciar agenda geral: definir horário de funcionamento geral do estabelecimento.

***

Criar conta: realizar o cadastro no sistema com dados necessários para realizar o agendamento.

Consultar serviços: visualizar a lista de serviços oferecidos, seus valores e detalhes.

Agendar serviço: escolher um serviço e agendar um horário.

Cancelar agendamento: cancelar um agendamento previamente realizado.

Realizar pagamento: efetuar o pagamento por serviços ou produtos adquiridos.

Avaliar serviço: avaliar a qualidade do atendimento e do serviço prestado.

Consultar histórico de serviços: visualizar o histórico de serviços realizados, incluindo datas, valores e detalhes.

***
***

3. Descrever 1 caso de uso crítico/mais importante do sistema de forma completa;

***
   
Caso de uso: Agendar serviço

Ator: Cliente (autoatendimento)

Descrição: O cliente acessa o sistema, seleciona os serviços desejados e os profissionais disponiveis. Em seguida, o sistema apresenta os horários disponíveis para o cliente escolher. Após a confirmação do cliente, o agendamento é registrado no sistema e um email de confirmação é enviado ao cliente.

Pré-condições: Cliente cadastrado na base de dados do sistema. Cliente está logado no sistema. A lista de serviços e profissionais está atualizada. Serviço disponivel na agenda do profissional. Data disponivel na agenda do profissional.

Pós-condições: O agendamento é registrado no calendário do profissional e do cliente. O cliente recebe uma confirmação do agendamento.

Fluxos alternativos: 

Cliente não encontrado: O cliente deve criar uma conta para acesso ao sistema.

Horário não disponível: O sistema sugere horários alternativos.

Serviço não disponível: O sistema informa que o serviço não está disponível e sugere alternativas.

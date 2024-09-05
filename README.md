1. Identificar casos de uso de negócio por ator (cumprir metas do usuário);
Possíveis casos de uso por ator:

***


-> Proprietário/Gerente:

Gerenciar funcionários

Gerenciar produtos

Gerenciar valores

Gerar relatórios

Configurar o sistema

Gerenciar agenda geral 

***

-> Funcionários:

Modificar agenda pessoal 

Registrar tipos de atendimentos

Consultar agenda

Consultar histórico de clientes

***

-> Recepcionista:

Registrar clientes

Agendar Cliente

Vender produtos

Gerenciar pagamentos

Lista Espera

Editar agenda 

***

-> Cliente

Consultar serviços

Agendar serviço

Cancelar agendamento

Realizar pagamento

Avaliar serviço

Consultar histórico de serviços

***
***

2. Descrever os casos de uso de forma resumida;

   ***
   
Exemplo de descrição resumida:

Editar agenda : caso de uso responsavel por editar agenda registrada do estabelecimento.

Lista espera: caso de uso responsavel por guardar dados de clientes que desejam aguardar liberação de horario para algum serviço ou profissional

Registrar Clientes : realiza o cadastro de clientes com dados necessarios para realixar o agendamento.

Agendar Cliente:  caso de uso responsavel por acessar agenda e realizar o agendamento do serviço.

Vender produtos: Registrar vendas e emitir notas fiscais.

Gerenciar pagamentos: Receber pagamentos e emitir recibos.

Gerenciar agenda geral  : define horario de funcionamento geral do estabelecimento 

Modificar agenda pessoal : Caso de uso responsavel por editar horarios de agenda disponiveis.

Registrar tipos de atendimentos : Caso de uso responsavel por  Detalhar os serviços realizados pelo profissional.

Consultar agenda: Verificar seus próprios horários e disponibilidade.

Consultar histórico de clientes: Acessar informações sobre serviços anteriores.

Gerenciar funcionários: CRUD.

Gerenciar produtos:CRUD e controle visual e estoque.

Gerenciar valores: definir comissoes, valores e gerenciar valores de entrada do estabeleciomento.

Gerar relatórios: caso de uso responsavel por gerar relatorio de clientes e produtos vendidos .

Configurar o sistema: Definir permissões, personalizar a interface.


***
***

3. Descrever 1 caso de uso crítico/mais importante do sistema de forma completa;

***
   
Caso de uso: Agendar serviço

Ator: Recpecionista 

Descrição: O funcionário acessa o sistema, busca por um cliente (ja cadastrado no banco de dados) e seleciona os serviços desejados e os profissionais disponiveis. Em seguida, o sistema apresenta os horários disponíveis para o cliente escolher. Após a confirmação do cliente, o agendamento é registrado no sistema e um email de confirmação é enviado ao cliente.

Pré-condições: O funcionário está logado no sistema. A lista de serviços e profissionais está atualizada. Serviço disponivel na agenda do profissional. Data disponivel na agenda do profissional. Cliente cadastrado na base de dados do sistema

Pós-condições: O agendamento é registrado no calendário do profissional e do cliente. O cliente recebe uma confirmação do agendamento.

Fluxos alternativos: 

Cliente não encontrado: O funcionário cadastra um novo cliente.

Horário não disponível: O sistema sugere horários alternativos ou coloca o cliente em uma lista de espera.

Serviço não disponível: O sistema informa que o serviço não está disponível e sugere alternativas.

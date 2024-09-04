1. Identificar casos de uso de negócio por ator (cumprir metas do usuário);
Possíveis casos de uso por ator:

***

-> Proprietário/Gerente:

Gerenciar funcionários: Cadastrar, editar, remover e atribuir funções.

Gerenciar produtos: Cadastrar, editar, remover e controlar o estoque.

Gerenciar serviços: Cadastrar, editar e definir preços.

Gerar relatórios: Financeiros, de vendas, de serviços mais procurados.

Configurar o sistema: Definir permissões, personalizar a interface.

***

-> Funcionário (cabeleireiro):

Agendar serviços: Marcar, editar e cancelar horários.

Registrar atendimento: Detalhar os serviços realizados e produtos utilizados.

Consultar agenda: Verificar seus próprios horários e disponibilidade.

Consultar histórico de clientes: Acessar informações sobre serviços anteriores.

***

-> Recepcionista:

Atender clientes: Agendar serviços, realizar check-in e check-out.

Vender produtos: Registrar vendas e emitir notas fiscais.

Gerenciar pagamentos: Receber pagamentos e emitir recibos.


***
***

2. Descrever os casos de uso de forma resumida;

   ***
   
Exemplo de descrição resumida:

Agendar serviço: O funcionário busca por um cliente na base de dados, seleciona os serviços desejados e escolhe um horário disponível.


Registrar atendimento: Após o término do serviço, o funcionário registra os detalhes do atendimento, como serviços realizados, produtos utilizados e tempo de duração.


Gerenciar estoque: O proprietário ou gerente realiza a contagem dos produtos em estoque, registra novas compras e gera relatórios de estoque baixo.


***
***

3. Descrever 1 caso de uso crítico/mais importante do sistema de forma completa;

***
   
Caso de uso: Agendar serviço

Ator: Funcionário

Descrição: O funcionário acessa o sistema, busca por um cliente (existente ou novo) e seleciona os serviços desejados. Em seguida, o sistema apresenta os horários disponíveis para o cliente escolher. Após a confirmação do cliente, o agendamento é registrado no sistema.

Pré-condições: O funcionário está logado no sistema. A lista de serviços e profissionais está atualizada.

Pós-condições: O agendamento é registrado no calendário do profissional e do cliente. O cliente recebe uma confirmação do agendamento.

Fluxos alternativos:

Cliente não encontrado: O funcionário cadastra um novo cliente.

Horário não disponível: O sistema sugere horários alternativos ou coloca o cliente em uma lista de espera.

Serviço não disponível: O sistema informa que o serviço não está disponível e sugere alternativas.

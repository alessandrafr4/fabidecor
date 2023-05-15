# Projeto Integrador - FabDecor

Professores: [Marco André Mendes](github.com/marcoandre) e [Alann Perini](https://github.com/AlannKPerini).

Links do projeto:

-   [Documentação (esse documento)](https://github.com/alessandrafr4/fabidecor.git)
-   [Backend]
-   [Frontend]


Alunas: 
- [Alessandra Fernandes Pereira](https://github.com/alessandrafr4)
- [Bruna Da Rosa Miranda](https://github.com/Brunamy)

## Situação problema

Sra. Fabrícia Fernandes, da empresa FabDecor, projeta decorações para festas e eventos há 7 anos e descobriu sua paixão através da sua primeira decoração na festa de sua sobrinha que fazia seu primeiro ano. Ela planejou e fez tudo sozinha com ajuda de algumas inspirações do Google. Atualmente, ela quer adquirir um sistema porque suas anotações estão se perdendo. Ela anota seus compromissos em um caderno, que é um modelo pouco funcional e seguro. Para isso, ela precisa de um sistema que gerencie todos os seus empréstimos, dias disponíveis, orçamentos, etc. de maneira simples. Histórico e lembretes também são importantes, mantendo os compromissos e as datas disponíveis sob controle.

O cliente entra em contato via WhatsApp com a Sra. Fabrícia e informa que deseja fazer uma festa ou evento, informando de que tipo de festa se trata, e que gostaria de alguém especializado em decoração. Ela retorna suas mensagens e faz todas suas anotações no seu caderno.

O cliente manda fotos de inspiração, pede um tema específico ou ainda pede sugestão de temas.

Caso o(a) cliente necessite de  sugestões, a Sra. Fabrícia envia algumas fotos de eventos que ela já tenha feito ou fotos inspirativas. Na hipótese do cliente apresentar o tema planejado, a proprietária verifica se há a possibilidade de ser realizada.

A Sra. Fabrícia informa os valores, combina o horário e local. Depois disso, ela se organiza, prepara propostas sob encomenda e se desloca até o local da festa/evento no dia.

Após o término do evento, o cliente entra em contato novamente e a Dona Fabrícia vai até o local fazer a retirada.

## Descrição Da Proposta
  
A primeira situação que analisamos é o método de agendamento. Em algumas ocasiões, ela se perde nos dias e às vezes acaba não tendo um local fixo para anotar. O sistema poderia auxiliar nessa parte.

A segunda situação é a falta do seu catálogo de tendências. Caso o cliente não tenha um tema planejado, o catálogo facilitaria a encontrar um tema, pois o cliente já teria as decorações que a Sr Fabrícia já realizou. Resolver esse problema é benéfico para ambas as partes, pois a Sra Fabrícia não precisaria se empenhar tanto, ficando horas procurando inspirações no Google e as clientes poderiam ver seus trabalhos já realizados.

Também consideramos o acesso aos relatórios que Sra. Fabrícia terá acesso, que mostrarriam suas vendas de temas mais alugados por temporada, por faixa etária de idade, ou por temas, como festa de aniversário, chá de panela, casamento ou outros eventos.

- O software que iremos desenvolver terá uma agenda que mostrará os dias disponíveis para a realização de eventos.
- O software terá lembretes que facilitarão a Sr. Fabrícia a não se esquecer dos seus compromissos.
- O atendente será responsável por registrar trabalhos e sugestões de decorações. Com isso os clientes terão acesso a todas as informações, podendo escolher as melhores opções que deseja contratar.
- O software ajudará os clientes a entrarem em contato com a Sr Fabrícia por meio das suas redes sociais, como o WhatsApp.
- O cliente poderá ver seus trabalhos realizados, entrar em contato, deixar seu comentário e ver as avaliações.
- A Sr Fabrícia, poderá anotar seus agendamentos em um formulário com as informações da decoração escolhida pelo cliente e seus dados de contato.
- O Atendente terá um espaço no sistema onde ele poderá publicar os trabalhos realizados pela empresa, visualizar e responder comentários de clientes, responder dúvidas e a publicidade dos trabalhos.
- O Gerente terá acesso às áreas de relatórios e e financeira. A proprietária teria acesso a todos os requisitos como relatórios, agendamentos e o contato com os clientes. 


## Regras De Negócios 

- **RN01- Visualizar o Catálogo:** Para visualizar os trabalhos é necessário abrir o catálogo. 
- **RN02- Inserir Pedidos:** Para inserir um tema no pedido, é necessário que o produto esteja cadastrado no sistema e que tenha dias disponíveis.
- **RN03- Primeiro Contato:** Os Clientes podem entrar em contato por meio das redes sociais da empresa.
- **RN04- Registrar Emprestimo:** Para realizar o empréstimo, o cliente deverá entrar em contato via Whatsapp. 
- **RN05- Registros:** O gerente deve possuir acesso aos registros de empréstimos e relatórios.
- **RN06- Orçamento:** Após registrar as informações do orçamento, o atendente deverá imprimir e encaminhar o orçamento para aprovação do cliente, e se for confirmado pelo cliente, o atendente deverá solicitar um contrato para execução do serviço.
- **RN07- Abertura dos empréstimos:** Com o atendimento aprovado pelo cliente, a atendente deverá inserir os dados do cliente e do orçamento em um novo documento, para registros internos, realizando a abertura dos emprestimos.
- **RN08-Regra de adiantamento para fechar contrato** O cliente deverá pagar um adiantamento para fechar contrato.
- **RN08- Pagamento de Multa:** Caso o cliente danifique algum objeto de decoração, deverá pagar multa.
- **RN09- Quebra de Contrato:** Caso o cliente quebre o contato, haverá uma multa de 50%.
- **RN10- Feedback:** O atendente deverá visualizar os comentários, responder e tirar dúvidas.
- **RN11- Relatórios:** O relatório de faturamento será permitido somente para o administrador.

## Requisitos Funcionais

- **R.F. 01 - Empréstimo:** O sistema deve realizar um agendamento com os seguintes dados: Nome do cliente, CPF, Endereço, Data e Horário. Usuários: Somente o atendente.
- **R.F. 02 - Orçamento:** O sistema deve solicitar o Orçamento com os seguintes dados: Nome do cliente, Tema,Valor, Endereço, Data e Horário. 
Usuários: Somente o Atendente
- **R.F. 03 - Pagamento:** O sistema deve solicitar Pagamento com os seguintes dados: Nome do cliente, Valor Total, Valor Pago, Troco, Data e Horário do pagamento. 
Usuários: Somente o Gerente
- **R.F. 04 - Feedback:** O sistema deve realizar um comentário ou respostas com os seguintes dados: Nome, Email, Comentário ou Resposta. 
Usuários: todos os níveis de usuário.
- **R.F. 05 - Relatórios:** O sistema deve realizar um relatorio de faturamento, mostrar as média de faturamento mensal da empresa, com os seguintes dados: Número da ordem de pagamento conforme gerado pela plataforma, Descrição do serviço prestado e Valores.
  
## Requisitos Não-Funcionais

- **R.N.F.01 - Interface do usuário:** É recomendável que o sistema possua a escolha entre os modos claro e escuro, para melhorar a visualização.
<!-- - **R.N.F.02 - Interface do usuário:** É recomendável que o sistema possua varios tipos de traduções. -->
- **R.N.F.02 - Memória RAM:** É recomendável que o sistema possua no mínimo 2GB de RAM livres para melhor performance.
- **R.N.F.03 - Forma de uso do software:** O sistema por fazer parte de um ambiente interno, provavelmente será utilizado de acordo com as horas de trabalho da empresa, mas estará ativo 24 horas por dia em 7 dias por semana.
- **R.N.F.04 - Desempenho do software:**  Para  o app ter uma boa qualidade e eficiẽncia, recomendamos que mantenha seu app sempre atualizado.
- **R.N.F.05 - Segurança:** O administrador ficará responsável pela segurança dos acessos ao sistema, tendo consciência das pessoas que possua permissão para acesso.
- **R.N.F.06 - Proteção Dados:** O sistema deve proteger dados dos clientes contra acesso a pessoas não autorizadas.




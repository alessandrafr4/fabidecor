# Projeto Integrador - Empréstimo Gerenciamento de uma Loja de Decoração.

Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.

Professores: [Marco André Mendes](github.com/marcoandre) e [Alann Perini](https://github.com/AlannKPerini).

Links do projeto:

-   [Documentação (esse documento)](https://github.com/alessandrafr4/fabidecor.git)
-   [Backend](github.com/marcoandre/pi-backend)
-   [Frontend](github.com/marcoandre/pi-frontend)

Alunas: 
- [Alessandra Fernandes Pereira](link)
- Bruna Da Rosa Miranda

## Introdução

Sra. Fabrícia Fernandes, projeta decorações para festa e eventos há 7 anos e descobriu sua paixão atraves da sua primeira decoração na festa de sua sobrinha que fazia seu primeiro ano, ela planejou e fez tudo sozinha com ajuda de algumas inspirações do google. Atualmente ela quer adquirir um sistema porque suas anotações estão perdidas. Ela anota seus compromissos em um caderno, que é um modelo pouco funcional e seguro. Para isso, ela precisa de um sistema que gerencie todos os seus empréstimo, dias disponíveis, orçamento, etc. Mas que isso ocorra de maneira acessivel. Histórico e lembretes também são importantes, mantendo os compromissos e as datas disponíveis sob controle.


- **Situação-problema:**

Os clientes entram em contato via whatsapp com a Sra. Fabrícia e informa que deseja fazer uma festa ou evento e gostaria de alguém especializado em decoração. Sr fabricia retorna suas mensagens e faz todas suas anotações no seu caderno.

O (a) cliente manda fotos de inspiração, aconselham sobre um tema ou pedem dicas.

Caso o(a) cliente pretende sugestões a sra Fabricia envia algumas fotos do que ela já tenha feito ou fotos inspirativas,na hipótese do(a) cliente apresentar o tema planejado, a Sr. Fabricia  vê se há possibilidades de ser realizada.

Sr. Fabricia  informa os valores, combinam o horário e local.
Sra. Fabricia se organiza, prepara propostas sob encomenda e se desloca até o local da festa/evento no dia.

Após o término, o cliente entra em contato novamente e a Dona Fabricia vai até o local de retirada.


● Conclusão: A primeira situação que analisamos é o método de agendamento, em algumas ocasiões ela se perde nos dias e as vezes acaba não tendo um local fixo para anotar, o sistema poderia auxiliar nesta parte.
A segunda situação é a falta do seu catálogo de tendências, Caso o cliente não tenha um tema planejado,o catálogo facilitaria e ajudaria a ter um projeto prático, o cliente ja teria as decorações que a Sr Fabrícia desempenhou. Resolver e promover este problema é benéfico para ambas as partes, a Sra Fabrícia não precisaria se empenhar tanto e ficar horas procurando inspirações no google e as clientes podem ver seus trabalhos realizados.
Também consideramos o acesso aos relatórios que Sra. Fabrícia terá acesso, onde mostra suas vendas de temas mais alugados por temporada, por faixa etária de idade, seja; Festa de aniversário, chá de panela, casamento ou outros eventos.


- O software que iremos desenvolver terá uma agenda que mostrará os dias que a Sr Fabricia está disponível.
- O software terá lembretes que facilitara a Sr. Fabricia a não se esquecer dos seus compromissos.
- O atendente será responsável por registrar trabalhos e sugestões de decorações, com isso os clientes terão acesso a todas as informações podendo escolher as melhores opções que deseja contratar.
- O software ajudará os clientes a entrarem em contato com a Sr Fabricia por meio das suas redes sociais, como o whatsapp.
- O cliente Poderá ver seus trabalhos realizados, entrar em contato, deixar seu comentário e ver as avaliações.
- A Sr fabricia, poderá anotar seus agendamentos em um formulário com as informações da decoração escolhida pelo cliente e seus dados de contato.
- O Atendente terá um espaço no sistema aonde ele poderá publicar os trabalhos realizados pela empresa, visualizar e responder comentários de clientes, responder dúvidas e a publicidade dos trabalhos.
- O Gerente com acesso às áreas de reporting e financeira.
Sra. Fabricia terá acesso a todos os requisitos como relatórios, agendamentos e o contato com os clientes.


## Regras De Negócios 

- **RN01- Visualizar o Catálogo:** Para visualizar os trabalhos é necessário abrir o catálogo. 
- RN02- Inserir Pedidos: Para inserir um tema no pedido, é necessário que o produto esteja cadastrado no sistema e que tenha dias disponíveis.
- RN03- Primeiro Contato: Os Clientes podem entrar em contato por meio das redes sociais da empresa.
- RN04- Registrar Emprestimo: para realizar o empréstimo o cliente deverá entrar em contato via Whatsapp. 
- RN05- Registros: O gerente deve possuir acesso aos registros de empréstimos e relatórios.
- RN06- Orçamento: Após registrar as informações do orçamento, o atendente deverá imprimir e encaminhar o orçamento para aprovação do cliente, e se for confirmado pelo cliente, o atendente deverá solicitar um contrato para execução do serviço.
- RN07- Abertura dos emprestimos: Com o atendimento aprovado pelo cliente, a atendente deverá inserir os dados do cliente e do orçamento em um novo documento, para registros internos, realizando a abertura dos emprestimos.
- RN08- Pagamento de Multa: Caso o cliente danifique algum objeto de decoração, deverá pagar multa.
- RN09- Quebra de Contrato: Caso o cliente quebre o contato, haverá uma muta de 50%.
- RN10- Feedback: O atendente deverá visualizar os comentários, responder e tirar dúvidas.
- RN11- Relatórios- O relatório de faturamento será permitido somente para o administrador.

## Requisitos Funcionais

- R.F. 01 - Agendamento: O sistema deve realizar um agendamento com os seguintes dados; Nome do cliente, CPF, Endereço, Data e Horário. 
Usuários: Somente o atendente.
- R.F. 02 - Orçamento: O sistema deve solicitar o Orçamento com os seguintes dados; Nome do cliente,Tema,Valor,Endereço, Data e Horário. 
Usuários: Somente o Atendente
- R.F. 03 - Pagamento: O sistema deve solicitar Pagamento com os seguintes dados;Nome do cliente,Valor Total,Valor Pago,Troco, Data e Horário do pagamento. 
Usuários: Somente o Gerente
- R.F. 04 - Feedback : O sistema deve realizar um comentário ou respostas com os seguintes dados; Nome, Email,Comentário ou Resposta. 
Usuários: todos os níveis de usuário.


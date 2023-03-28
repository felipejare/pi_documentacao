# Projeto Integrador - Papa's Burgeria

Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.

Professores: [Marco André Mendes](github.com/marcoandre) e [Alann Perini](https://github.com/AlannKPerini).

Links do projeto:

-   [Documentação](github.com/felipejare/pi_documentacao)
-   [Backend](github.com/marcoandre/pi-backend)
-   [Frontend](github.com/marcoandre/pi-frontend)

# Como usar esse modelo para o Projeto Integrador

1. Faça um fork desse repositório para a sua conta do GitHub.
2. Clone o repositório para o seu computador.
3. Abra o arquivo README.md no seu editor de texto favorito (recomendamos o [Visual Studio Code](https://code.visualstudio.com/)).
4. Tenha instalada a extensão [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) no seu editor de texto.
5. Edite o arquivo README.md com as informações do seu projeto.

# Desenvolvimento

-   As equipes serão avaliadas por cada etapa da documentação e entregas realizadas.
-   Cada equipe deverá escolher um sistema para o desenvolvimento das atividades, a partir dos modelos apresentados.

# Modelos de Sistemas

## Ponto de Vendas (PDV)

**Gerenciamento de vendas para um restaurante **

O nosso cliente, Sr. Luis Papas, tem uma hamburgueria chamada Papa's Burgeria e, devido a qualidade e sabor dos seus hamburgueres, vem crescendo bastante. Recentemente, ele contratou mais funcionários para atendimento, caixa, cozinha, etc.
Assim, atualmente, ele consegue concentrar seus esforços para melhorar a gestão da hamburgueria. Para isso, ele quer instalar um sistema de controle de vendas que permita ao caixa lançar as vendas realizadas e sistema de comandas mais automatizado. Como sua intenção
é melhorar a gestão do negócio, é muito importante que ele consiga ter
relatórios, como por exemplo, de vendas, histórico de vendas, automatização de comandas e apresentações de pratos para os clientes.

# Situação Problema

-   **Introdução**: O nosso cliente é Papa's Burgeria, uma hamburgueria focada no gosto do cliente, isto é, eles apresetam pratos prontos, porém eles focam na personalização do seu hamburguer, onde o cliente está sempre certo e poderá escolher o que adicionar ou retirar do seu hamburguer. Eles surgiram em 2013 e atualmente contam com 20 funcionarios, sistema de delivery e seu dono Luis Papas.
  
-   **Situação-problema**: Clientes chegam no caixa e fazem seus pedidos de acordo com o seu gosto, adicionando ou retirando certos ingredientes e falando o ponto da carne, todo o processo é anotado a mão pelo atendente, na comanda direcionada ao cliente;
    A comanda é levada pelo próprio atendente até a cozinha onde eles averiguam o pedido e o preparam;
O pedido pronto é entregue pelos garçons ou motoboys da casa para o cliente.Sua forma de gerenciamento é muito arcaica, são feitos em planilhas que podem atrapalhar na gestão da empresa.

-   **Conclusão**:  A forma que é feito os pedidos se torna confuso quando cria problemas na cozinha quando a incerteza se algum pedido já fora feito ou não, o que causa problemas aos clientes onde ele pode receber o pedido incorreto, ou até mesmo, não receber o pedido. O gerenciamento da empresa tende a apresentar erros e se torna muito lento no dia a dia, por conta de seu sistema arcaico. 



# Descrição da proposta


Nosso software tem o objetivo de ajudá-los com os problemas de pontualidade com os clientes.
-

**Alguns pontos importantes a se destacar são:**

-   **Qual o foco de ação do software** Através de uma organização virtual onde mostra se o pedido já fora entregue ou não.
Cada mesa terá acesso ao nosso sistema onde ele poderá personalizar o seu pedido e pedir mais coisas durante a sua experiência no restaurante, assim eliminando o intermediário entre cozinha-garçom-cliente, porem ainda com a opção de fazer o pedido com o garçom.
-   **Os níveis de usuário do sistema** No nosso sistema teremos quatro níveis de usuário, sendo eles o menor nível, o do cliente que ele entrará como visitante. O próximo nível seria o do caixa onde ele poderá ver tudo que o cliente pediu, assim somando toda a conta, através do codigo de pedido que será gerado pelo sistema. O terceiro nível será o da cozinha onde ele verá todas as comandas, de onde elas vem e se foram recebidas e todo o histórico da cozinha pela noite. O maior nível será a do administrador, onde ele poderá gerir a empresa, assim, poderá ver o lucro, estoque, funcionários e tudo que o caixa e a cozinha pode ver.
-   **O que poderá ser feito no software** Na cozinha, os chefs receberão a notificação de um novo pedido onde mostrará toda a escolha do cliente. Após a finalização do hambúrguer a cozinha envia a notificação que o pedido fora finalizado e o cliente poderá confirmar que ele recebeu o mesmo.

# Regras de negócio

**Nessa parte a equipe deve descrever as regras de negócio que serão implementadas no sistema. O texto abaixo descreve o que essa etapa deve conter e pode ser apagado depois.**

As **Regras de negócio** são orientações e restrições que ajudam a regular as operações de uma empresa. **Regras** foram criadas para **colaborar com o funcionamento**, seja da sociedade, de uma escola, de um jogo, etc. Não seria diferente nas organizações. Vamos abordar melhor sobre esse assunto. Entender o que são as
regras de negócio, sua importância, como são aplicadas e
automatizadas na gestão por processo.

## 4.1 O que são regras de negócio?

Um negócio funciona por processos que, por sua vez, são formados por atividades relacionadas entre si.

As funções das áreas de compras, estoque, logística, finanças, vendas e marketing, por exemplo, compõem um processo de fornecimento de um produto ao cliente.

Dentro desses processos, existem regras que devem ser seguidas durante a execução das atividades, que ajudam a definir **COMO** as operações devem ser realizadas e gerenciadas, **POR QUEM**, **QUANDO**, **ONDE** e **POR QUÊ**.

Podemos dizer que as regras de negócio são **limites impostos às operações**, de forma que elas sigam corretamente em direção às políticas e aos objetivos da instituição.

## 4.2 Regras para a criação de regras de negócio

De maneira geral, as regras de negócio devem:
- Ser **simples**, isto é,  ter apenas uma função.
- Ser **completas**, com início, meio e fim.
- Ser possíveis de **mensurar** e **rastrear**.
- Estar em consonância com a **legislação**.
- Estar **atualizadas** e sempre **revisadas**.
- Refletir a **política** e os **valores** da organização.
- Ser **inteligíveis** para os colaboradores e envolvidos no processo.

## 4.3 Por que ter regras de negócio?

- **Padronização de processos:** padronizam os processos e auxiliam a fluirem de forma mais eficiente e automatizada.
- **Controle de processos:** auxiliam no controle de processos, pois falhas são identificadas e corrigidas mais rapidamente.
- **Tomada de decisão:** auxiliam na tomada de decisão e no cumprimento de estratégias pré-estabelecidas.

## 4.4 Exemplos de regras de negócio

- Em um controle de qualidade de granja, pode-se dizer que a cada 100 ovos impróprios para consumo, o lote será descartado.
- Em um banco, clientes com faturamento mensal de mais de R$ 25 mil e CPF sem restrições, serão atendidos pelo gerente Premium pessoa física.
- Para conclusão de licitações, devem ser feitos três orçamentos e o vencedor será sempre o de menor preço final.
- Em um processo de seleção de RH, o candidato só pode ser aprovado se tiver mais de 5 anos de experiência na área, diploma de pós-graduação, espanhol fluente e pretensão salarial abaixo de R$ 8.000,00.
- Em um processo de vendas, o vendedor só pode vender um produto se o cliente tiver mais de 18 anos, renda familiar acima de R$ 5.000,00 e não tiver restrições no CPF.
- Em um processo de compras, o fornecedor só pode ser contratado se tiver nota fiscal, certificado de qualidade e preço abaixo de R$ 10,00 por unidade.
- Em um processo de logística, o pedido só pode ser enviado se o cliente tiver mais de 18 anos, endereço de entrega no mesmo estado e não tiver restrições no CPF.

## 4.5 Como escrever regras de negócio?

- Número identificador.
- Nome da regra.
- Data de criação e data da última alteração para comparações e
controle.
- Nome dos Autores das versões.
- Número da versão (1, 2 etc).
- Dependências: insira o identificador das regras atreladas, às quais a regra em questão depende.
- Uma descrição detalhada para compreensão da regra.

## 4.6 Exemplos de regras de negócio com formatação

- **RN01 - Fazendo pedido:** Para o cliente fazer seu pedido ele terá que escanear seu QR code e ultilizar o usuario visitante que lhe dará um ID para fazer o pedido ou criar o seu proprio usuario.  
- **RN02 - Criação de Comanda:** O cliente poderá fazer o pedido pela comanda digital ou chamar um atendente, caso ele peça algo a comanda irá para a cozinha.
- **RN03 - Modificações de um Prato:** Caso um prato seja pedido e tenha modificações (quaisquer que sejam elas) o cozinheiro terá que fazer a modificação.
- **RN04 - Pagamento:** Para você pode pagar terá de apresentar o seu numero de identificação(ID) assim o atendente irá puxar tudo oque está na sua comanda para você pode pagar.
- **RN05 - Registro Administrativo:** Uma pessoa terá uma conta administrativa que poderá administrar o estoque, lucro, funcionarios e o registro de compras.
- **RN06 - Entrega de Pedido:** Quando o cozinheiro terminar o pedido o cozinheiro deverá marcar como pedido pronto e o garçom irá levar para a mesa.
- **RN07 - Recebimento de Seu Prato:** Quando o pedido chegar na mesa do cliente, ele terá que confimar pelo aplicativo ou tela na mesa que o pedido chegou.
<!-- - **RN01 – Criação Comanda:** Para iniciar um atendimento no balcão, é necessário primeiro abrir uma nova comanda.
- **RN02 – Inserir Produtos Comanda:** Para inserir um produto na comanda, é necessário que o produto esteja cadastrado no sistema e que a quantia comprada seja acima de zero.
- **RN03 – Cadastro de Leitores:** Os leitores precisam fazer o cadastro para realizar o empréstimo.
- **RN04 – Realizar Empréstimo:** Para realizar o empréstimo, apenas leitores com cadastro e nenhuma multa em aberto.
- **RN05 – Registro de Empréstimo:** O gerente deve possuir acesso aos registros de empréstimos.
- **RN06 – Pagamento de Multa:** O leitor que passar de 15 dias com o livro deverá pagar a multa de um real por dia de atraso.
- **RN07 – Impressão de Orçamento:** Com as informações do
orçamento registradas, a atendente deve imprimir o orçamento e
repassar ao cliente para aprovação, e caso o cliente aprovar, a atendente deve solicitar a sua assinatura para aprovar a execução do serviço.
- **RN08 – Abertura de OS:** Com o atendimento aprovado pelo cliente, a atendente deverá inserir os dados do cliente e do orçamento em um novo documento, para registros internos, realizando a abertura da OS.
- **RN09 – Relatório de Fluxo de Caixa:** O relatório de fluxo de caixa será permitido somente para o administrador. -->


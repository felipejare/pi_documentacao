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


## Regra de negócio de Papa's Burgeria

- **RN01 - Fazendo pedido:** Para o cliente fazer seu pedido ele terá que escanear seu QR code e utilizar o usuário visitante que lhe dará um ID para fazer o pedido ou criar o seu próprio usuário.
<!-- - não esquecer de transformar a rn01 em dois, por conta de cliente visitante e cliente usuario cadastrado e cada diferença de cada um -->
- **RN02 - Criação de Comanda:** O cliente poderá fazer o pedido pela comanda digital ou chamar um atendente. Caso ele peça algo, a comanda irá para a cozinha.
- **RN03 - Modificações de um Prato:** Caso um prato seja pedido e tenha modificações (quaisquer que sejam elas) o cozinheiro terá de fazer a modificação.
- **RN04 - Pagamento:** Para poder efetuar o pagamento terá de ser apresentado no caixa o número de identificação (ID) e assim o atendente terá acesso a comanda criada para o cliente e todo o seu pedido com o valor da conta.
- **RN05 - Registro Administrativo:** Uma pessoa terá uma conta administrativa que poderá administrar o estoque, lucro, funcionários e o registro de compras.
- **RN06 - Entrega de Pedido:** Assim que o cozinheiro terminar de preparar o pedido, ele deverá marcar como pedido pronto e assim, o garçom levará o pedido para a mesa.


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

- **RN01 - Usuário visitante:** O cliente que está entrando no estabelecimento e não optar por criar uma conta no sistema, ele entrerá como um usuário visitante e terá seu ID de visitante.
- **RN02 - Usuário cadastrante:** O cliente ques está entrando no estabelecimento e optar por criar um cadastro, ele terá seu ID próprio, e tera alguns recursos a mais, como exemplo: histórico de compras, cupons de desconto e tela de perfil.
- **RN03 - Criação de Comanda:** O cliente poderá fazer o pedido pela comanda digital ou chamar um atendente. Caso ele peça algo, a comanda irá para a cozinha.
- **RN04 - Modificações de um Prato:** Caso um prato seja pedido e tenha modificações (quaisquer que sejam elas) o cozinheiro terá de fazer a modificação.
- **RN05 - Pagamento:** Para poder efetuar o pagamento terá de ser apresentado no caixa o número de identificação (ID) e assim o atendente terá acesso a comanda criada para o cliente e todo o seu pedido com o valor da conta.
- **RN06 - Registro Administrativo:** Uma pessoa terá uma conta administrativa que poderá administrar o estoque, lucro, funcionários e o registro de compras.
- **RN07 - Entrega de Pedido:** Assim que o cozinheiro terminar de preparar o pedido, ele deverá marcar como pedido pronto e assim, o garçom levará o pedido para a mesa.


# Requisitos Funcionais

**Entradas:**

- **R.F. 01 - Registro de Cliente Visitante:** O sistema deve permitir o cadastro de cliente com uma identificação automática para emitir sua comanda e fazer seu pedido.
  - **Dados necessários:** NúmeRo de identificação automatico, 
  - **Usuários:** Cliente.

- **R.F. 02 - Registro de Funcionario:** O sistema deve ter um sistema de cadastro de funcionários e diferentes niveis para cada funcionário. 
  - **Dados necessários:**  login/email, senha,nivel de permissão.
  - **Usuários:** Funcionário.

**Processamento:**

  - **R.F. 03 - Sistema de Comandas:** O sistema deverá emitir uma comanda online em tempo real para o cliente, que ele poderá adicionar mais itens a sua comanda. 
  - **Dados necessários:** NúmeRo de identificação, produto, quantidade;
  - **Usuários:** Cliente/funcionarios

- **R.F. 04 - Pagamento de comanda:** O sistema deverá apresentar a comanda para o caixa e para a cozinha de maneira rápida e online. 
  - **Dados necessários:** NúmeRo de identificação, login, senha.
  - **Usuários:** Funcionários.
  - 

**Saídas:**

- **R.F. 05 - Relátorios de vendas:** O sistema deverá emitir um relatório semanal e um mensal para o gerente de lucro e prejuizos de venda. 
  - **Dados necessários:** NúmeRo de identificação, data inicial, data final;
  - **Usuários:** Funcionários.

- **R.F. 06 - Relatório de Estoque:** O sistema deverá emitir um relatório da quantidade de produtos utilizados no dia e o quanto ainda tem em estoque. 
  - **Dados necessários:** Produto, data inicial, data final;
  - **Usuários:** Funcionários.

<!-- 
- **R.N.F. 02 - Sistema de :** O sistema deverá permitir que o cliente possa se cadastrar e ter acesso a seu histórico de compra, seu perfil e seus cupons. 
  - **Dados necessários:** NúmeRo de identificação, login/email, senha.
  - **Usuários:** Cliente. -->

# 6. Requisitos não funcionais

Requisitos não funcionais (**RNFs**) são as restrições impostas a um sistema que definem seus atributos de qualidade.

Eles geralmente são indicados por adjetivos como **segurança**, **desempenho** e **escalabilidade**.

**6.1 Categorias de requisitos não funcionais**

Os requisitos não funcionais são importantes porque ajudam a garantir que o sistema atenda às necessidades do usuário.

Os Requisitos Não Funcionais explicam as limitações e restrições do sistema a ser projetado. **Esses requisitos não têm nenhum
impacto na funcionalidade do aplicativo.** Além disso, existe uma prática comum de subclassificar os requisitos não funcionais em várias categorias:

- Interface de Usuário
- Confiabilidade
- Segurança
- Atuação
- Manutenção

Os requisitos não funcionais podem ser divididos em duas categorias:

1. **Atributos de qualidade:** Estas são as características do sistema que determinam sua qualidade geral. Exemplos de atributos de qualidade incluem segurança, desempenho e usabilidade.
2. **Restrições:** Estas são as limitações impostas ao sistema.
Exemplos de restrições incluem tempo, recursos e ambiente.

**6.2 Vantagens dos requisitos não funcionais**

Os requisitos não funcionais ajudam a garantir que o sistema seja:

1. Adaptado às necessidades do usuário.
2. Adequado à finalidade.
3. Escalável, seguro e confiável.
4. Fácil de usar e manter.

**6.3 Exemplos de requisitos não funcionais**

Aqui estão alguns exemplos de requisitos não funcionais:
1. **Segurança**: O sistema deve ser protegido contra acesso não
autorizado.
2. **Atuação**: O sistema deve ser capaz de lidar com o número necessário
de usuários sem qualquer degradação no desempenho.
3. **Escalabilidade**: O sistema deve ser capaz de aumentar ou diminuir
conforme necessário.
4. **Disponibilidade**: O sistema deve estar disponível quando necessário.
5. **Manutenção**: O sistema deve ser fácil de manter e atualizar.
6. **Portabilidade**: O sistema deve ser capaz de rodar em diferentes
plataformas com alterações mínimas.
7. **Confiabilidade**: O sistema deve ser confiável e atender aos requisitos
do usuário.
8. **Usabilidade**: O sistema deve ser fácil de usar e entender.
9. **Compatibilidade**: O sistema deve ser compatível com outros sistemas.
10. **Conformidade**: O sistema deve cumprir todas as leis e regulamentos
aplicáveis.

**6.4 Exemplo de organização dos requisitos não funcionais**

(_A seguir, um exemplo de organização de requisitos não funcionais._)

**Requisitos não funcionais:**

- **R.N.F. 01 - Nome do requisito não funcional:** descrição do requisito. 
- **R.N.F. 02 - Nome do requisito não funcional:** descrição do requisito.

**Exemplos de requisitos não funcionais:**


**Sistema de Padaria**:
- R.N.F. 01 - Navegador homologado: O sistema deverá ser homologado somente para o navegador Google Chrome.
- R.N.F. 02 - Processador: É recomendado para o sistema  no mínimo um processador Intel i3, similar ou superior a geração 7100 ou AMD Ryzen 3 da geração similar ou superior ao 3100, para que o servidor funcione em sua melhor performance.
- R.N.F. 03 - Memória RAM: é recomendável que o sistema possua no mínimo 2GB de Ram para melhor performance.
- R.N.F. 04 - Arquitetura: A arquitetura que será utilizada para criação do sistema será Rest.
- R.N.F. 05 - Conexão com banco de dados: Para conexão com o banco de dados, o sistema utilizará a ferramenta de MySQL Connector.
- R.N.F. 06- Banco de dados: O sistema será implementado com o banco de dados MySQL.
- R.N.F. 07 - Implementação: O sistema deverá ser desenvolvido com linguagem Java, Javascript,  HTML5, CSS3 e JQuery.
- R.N.F. 08 - Segurança: Ficará a critério do responsável do estabelecimento a segurança dos acessos ao sistema, tendo consciência das pessoas que possua permissão para acesso.
- R.N.F. 09 - Ambiente de Desenvolvimento Integrado (IDE): Para criação do sistema, será utilizado  Eclipse.
- R.N.F. 10 - Disponibilidade: O sistema irá atender 99% do tempo de uso, somente ocorreria problemas de cadastro, remoção, inserção ou alteração em casos de falta de rede ou energia.
- R.N.F. 11 - Legais: O sistema deve atender às exigências da LGPD (Leis Gerais da Proteção de Dados).

**Sistema de Ordem de Serviço:**
- R.N.F. 01 - Navegadores homologados: o sistema deverá ser homologado para os navegadores Google Chrome e Mozilla Firefox. 
- R.N.F. 02 - Tecnologia Front-end: Para a exibição em front-end, o software utilizará o CSS3 e o HTML5, além das bibliotecas de jQuery e Javascript.
- R.N.F. 03- Tecnologia Back-end: O software será desenvolvido pela linguagem de programação Java.
- R.N.F. 04- Interoperabilidade: O banco de dados será o Mysql, com a linguagem SQL de banco, sendo todo produzido através do mysql Workbench .
- R.N.F. 05- Forma de uso do software: O sistema por fazer parte de um ambiente interno, provavelmente será utilizado de acordo com as horas de trabalho da empresa, mas estará ativo 24 horas por dia em 7 dias por semana.
- R.N.F. 06- Desempenho: Para a utilização correta e com uma qualidade e eficiência melhor, é recomendado que se use o SO mais atualizado, com recursos de hardware equivalentes a um processador intel i3 5°Gen ou semelhante, e 8GB de memória RAM, assim como os navegadores homologados.
- R.N.F. 07- Autenticação: Para realizar o acesso ao sistema é necessário ter um usuário de autenticação criado pelo administrador, além da possibilidade de solicitar um envio de redefinição de senha.
- R.N.F. 08- Web Server: O servidor web utilizado será o Apache Tomcat, nas versões mais atualizadas.
R.N.F. 08- Níveis de segurança: O software terá diferentes tipos de acesso para cada tipo de login, tendo as permissões ideais a função de cada um.

**6.6 Conclusão**

Requisitos não funcionais são essenciais para qualquer sistema. Eles ajudam a garantir que o sistema atenda às necessidades do usuário e seja capaz de funcionar como pretendido.

É importante considerar cuidadosamente todos os requisitos não funcionais antes de projetar e desenvolver um sistema.
Eles ajudam a garantir que o sistema atenda às necessidades do usuário e seja capaz de funcionar como pretendido.


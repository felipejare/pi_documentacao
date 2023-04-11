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

# 5. Requisitos funcionais
(*Nessa parte a equipe deve descrever os requisitos funcionais que serão implementados no sistema. O texto abaixo descreve o que essa etapa deve conter e pode ser apagado depois.*)

## 5.1 O que são requisitos funcionais?**

Um requisito funcional é uma declaração de como um sistema deve se comportar. Define o que o sistema deve fazer para atender às necessidades ou expectativas do usuário. Os requisitos funcionais podem ser pensados ​como recursos que o usuário detecta.

Os requisitos funcionais são compostos de duas partes:
**função** e **comportamento**. 

- A **função** é o que o sistema **faz**. Por exemplo: *“calcular imposto sobre vendas”*.
- O **comportamento** é **como** o sistema faz. Por exemplo: *“O sistema deve calcular o imposto sobre vendas multiplicando o preço de compra pela alíquota do imposto.”*.

## 5.2 Tipos de requisitos funcionais

Os requisitos funcionais podem ser classificados em:

- Regulamentos de Negócios
- Requisitos de Certificação
- Requisitos de relatório
- Funções Administrativas
- Níveis de autorização
- Rastreamento de auditoria
- Interfaces Externas
- Gestão de dados
- Requisitos Legais e Regulamentares

## 5.3 Diretrizes para a elaboração de requisitos funcionais

Cada requisito funcional precisa ser:

- **Específico** sobre o que o sistema deve fazer.
- **Mensurável** para que você possa dizer se o sistema está fazendo isso
- **Alcançável** dentro do prazo que você definiu
- **Relevante** para seus objetivos de negócios
- **Limitado** no tempo para que você possa
acompanhar o progresso

## 5.4 Estrutura do requisito funcional

Um requisito funcional deve ser estruturado da seguinte forma:

- **Nome do requisito funcional:** descrição do
requisito. 
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

### 5.4.1 Nome do requisito funcional

**R.F. 99 - Nome do requisito funcional:** é o nome da função que o software terá. Sugerimos, por padronização, que tenha o prefixo R.F. (requisito funcional)
seguida da numeração, para melhor identificação do requisito, acrescido do formato *“Substantivo + onde será feita a ação”*.
Por exemplo: 
- R.F. 01 - Registro de Funcionários
- R.F. 15 - Gerenciamento de consultas
- R.F. 04 - Débito em conta corrente
 
Deixe para definir as numerações ao final, tendo em vista que mudanças podem acontecer e não é prático sempre ficar reajustando os números.

### 5.4.2 Descrição do requisito funcional

**Descrição do requisito:** local para descrever a função deste requisito. 

Sempre se preocupe em esclarecer dois pontos: o que o requisito faz e o motivo de sua existência. Isso é especialmente importante se a ação executada nesse requisito não for algo que já acontece naturalmente na empresa.
Um exemplo é um Registro de funcionários, que talvez não exista hoje mas para o software é necessário para viabilizar uma autenticação de
usuários. Outro exemplo é algo que faz sentido apenas para um  software, como a própria autenticação.


### 5.4.3 Dados necessários

**Dados necessários:** aqui devem ser colocados os nomes dos dados que serão usados para que esse requisito atenda o que precisa fazer. 

Nas **entradas** e **processos**, em geral, são os dados que serão salvos (seja algo digitado pelo usuário ou captado do sistema, como a hora atual). 

Já nas **saídas**, são os dados que serão exibidos em tela (sejam eles vindos diretamente do banco, ou criados por um cálculo ou busca na sessão do usuário).

### 5.4.4 Usuários

**Usuários:** aqui devem ser colocados os nomes dos usuários que terão acesso a esse requisito, conforme enumerados na descrição do sistema.

### 5.4.5 Exemplo de requisito funcional

- **R.F. 01 - Autenticação de usuário:** tem como propósito autenticar o acesso ao sistema, verificando se o usuário pode acessá-lo e, caso possa, o direcionando
para a página principal de seu perfil de acesso. 
  - **Dados necessários:** login, senha, nível de permissão. 
  - **Usuários:** todos os níveis de usuário.

### 5.4.6 Organização dos requisitos funcionais

As funcionalidades devem ser organizadas em: entradas, processos e saídas.

**Entradas:** São as funcionalidades que alimentarão o software com as informações essenciais para seu uso. 
 
**Exemplos de entradas:**
- “**Registro de usuário**” (para permitir depois seu acesso ao software).
- “**Registro de paciente**” (que seria útil caso nosso software fosse ppara uma clínica, evitando registrar várias vezes os mesmos dados da pessoa a cada consulta e viabilizando um histórico de seus
atendimentos).

**Processos:** Em geral, englobam toda ação que executa cálculos, processamentos de tomada de decisão ou transforma dados em novos dados. 

**Exemplos de processos:**
- “**Autenticação de usuário**”, que usará os dados de “**Registro de usuário**” em sua execução.
- “**Agendamento de consulta**”, que usará dados do “**Registro de paciente**” e talvez do “**Registro de funcionário**” em sua execução.

**Saídas:** São os relatórios, gráficos, impressões, etc., que utilizarem os dados do software para gerar informações pertinentes ao
negócio, mas sem intenção de alterá-los, apenas permitindo sua visualização e filtragem. 

**Exemplos de saídas:**
- “Relatório de consultas por paciente”.
- Relatório de vendas”. 
- “Log de usuários autenticados”.

Todos esses podem ser consideradas saídas, pois usam informações de entradas e processos de modo a mostrar informações relevantes ao
negócio. Lembre-se que, diferentemente das entradas e processos, aqui os dados necessários devem ser os que a tela exibirá.

### 5.4.7 Exemplo de organização dos requisitos funcionais

(_A seguir, um exemplo de organização de requisitos funcionais, com entradas, processos e saídas._)

**Entradas:**

- **R.F. 01 - Nome do requisito funcional:** descrição do requisito. 
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

- **R.F. 02 - Nome do requisito funcional:** descrição do requisito. 
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

**Processamento:**

- **R.F. 03 - Nome do requisito funcional:** descrição do requisito. 
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

- **R.F. 04 - Nome do requisito funcional:** descrição do requisito. 
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

**Saídas:**

- **R.F. 05 - Nome do requisito funcional:** descrição do requisito. 
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

- **R.F. 06 - Nome do requisito funcional:** descrição do requisito. 
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

#

## Requisitos Funcionais

**Entradas:**

- **R.F. 01 - Sistema de Cliente Visitante:** O sistema deve ter um usuário visitante para clientes onde ele poderá emitir sua comanda e fazer seu pedido.
  - **Dados necessários:** NúmeRo de identificação, 
  - **Usuários:** Cliente.

- **R.F. 02 - Sistema de Cliente Cadastrado:** O sistema deverá permitir que o cliente possa se cadastrar e ter acesso a seu histórico de compra, seu perfil e seus cupons. 
  - **Dados necessários:** NúmeRo de identificação, login/email, senha.
  - **Usuários:** Cliente.

**Processamento:**

- **R.F. 03 - Nome do requisito funcional:** descrição do requisito. 
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

- **R.F. 04 - Nome do requisito funcional:** descrição do requisito. 
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

**Saídas:**

- **R.F. 05 - Nome do requisito funcional:** descrição do requisito. 
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

- **R.F. 06 - Nome do requisito funcional:** descrição do requisito. 
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.


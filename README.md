# Documento de Visão - IlhaGo 🏝️🍔🏍️
## 1. Introdução
### 1.1 Objetivo do documento
Este documento descreve a visão do **IlhaGo**, um aplicativo de entregas focado em proporcionar uma experiência de compra mais segura para moradores de áreas pequenas, para que eles recebam seus produtos de forma garantida, eficiente e simples.

---

### 1.2 Público-alvo
O IlhaGo será um aplicativo voltado para comunidades que moram em locais mais isolados e que possuem dificuldades em receber seus produtos.

---

### 1.3 Escopo do sistema
O IlhaGo estará disponível para as plataformas Android e IOS, permitindo com que o usuário navegue pelos produtos, filtre resultados de busca, adicione itens ao carrinho e escolha o modo de pagamento e entrega, podendo também acompanhá-la.



## 2. Posicionamento
### 2.1 Oportunidade de mercado
Grandes aplicativos de delivery nem sempre possuem boa cobertura em comunidades pequenas ou regiões mais isoladas. Dessa forma, existe uma oportunidade de criar uma solução voltada especificamente para essas localidades, conectando moradores, comerciantes e entregadores locais.

---

### 2.2 Problema a ser resolvido
Moradores de pequenas comunidades podem encontrar dificuldades para receber produtos em casa, seja pela falta de serviços de entrega, pelos altos custos ou pela pouca disponibilidade de entregadores na região. Além disso, pessoas com mobilidade reduzida podem enfrentar ainda mais dificuldades para se deslocar até os estabelecimentos.

---

### 2.3 Proposta de solução
A proposta é criar um aplicativo de entregas voltado para pequenas comunidades, como ilhas, permitindo que moradores realizem pedidos em estabelecimentos locais e recebam os produtos por meio de entregadores da própria região. A solução busca facilitar o acesso a produtos e serviços, apoiar o comércio local e proporcionar maior comodidade aos moradores.

## 3. Stakeholders & Usuários
### 3.1 Quem são os envolvidos?
Os principais stakeholders do projeto seriam os ***usuários (moradores)***, os ***comércios locais***, os ***funcionários (entregadores)*** e o ***orientador do projeto (professor)***.

Os usuários são, em parte, os próprios stakeholders deste projeto. Eles podem ser definidos por:

- **Morador:** Pessoa que deseja realizar um pedido pelo aplicativo.

- **Comércio:** Dono ou funcionário de um estabelecimento cadastrado no aplicativo.

- **Entregador:** Pessoa responsável por transportar o pedido do comércio até o morador.

---

### 3.2 Necessidades & Expectativas
Diante do projeto cada um possui necessidades e expectativas próprias, como apresentado na tabela abaixo:

| Stakeholder | Necessidades | Expectativas |
|---|---|---|
| **Moradores da Ilha** | Fazer pedidos para serem entregues direto em suas residências de forma rápida e prática, sem se preocuparem com o deslocamento pela ilha. | Conveniência, praticidade e previsibilidade.
| **Comércios & Restauranres** | Aumentar a quantidade de vendas, expandindo seu comércio e abrangendo moradores de todas as partes da ilha sem precisar de um sistema de entregas próprio.  | Aumento de alcance e da margem de lucro. Interação mais prática entre comércio-cliente. |
| **Entregadores** | Encontrar oportunidades de trabalho por meio de entregas. | Obter um fluxo considerável de entregas. Otimização de tempo e rotas. Remuneração adequada. |
| **Professor** | Avaliar o desempenho dos alunos na disciplina do projeto. | Um projeto estruturado, coerente e documentado. |

## 4. Visão Geral do Produto
### 4.1 Visão Geral
O IlhaGo é um aplicativo de entregas criado especialmente para comunidades que ficam em áreas pequenas e isoladas, como ilhas. A ideia é conectar moradores, comércios locais e pessoas que querem fazer entregas, tudo de forma simples e rápida.

Diferente dos aplicativos grandes de entrega, o IlhaGo foi pensado para funcionar em um espaço geográfico limitado, onde as distâncias são menores e o deslocamento é mais fácil. O foco principal é atender a necessidade real das pessoas que moram nesses lugares e têm dificuldade de receber ou enviar produtos no dia a dia.

---

### 4.2 Principais Funcionalidades
- Cadastro de usuários (moradores e entregadores)
- Cadastro de comércios locais
- Acompanhamento do status da entrega
- Chat simples entre quem pediu e quem está entregando
- Avaliação da entrega (nota e comentário)
- Histórico de pedidos
- Notificações de mudança de status
- Opção de pagamento via Pix, dinheiro ou cartão de crédito/débito

---

### 4.3 Diferenciais
O principal diferencial do IlhaGo é ser feito sob medida para uma área pequena. Isso permite:

- Entregas mais rápidas e com frete mais barato
- Uso de entregadores da própria comunidade
- Foco total no comércio local
- Interface simples, sem excesso de opções
- Funcionamento pensado para situações de internet instável

Além disso, o aplicativo prioriza a praticidade. A ideia não é competir com iFood ou Rappi em grandes cidades, e sim resolver um problema real de quem mora em regiões isoladas.

## 5. Requisitos de Alto Nível
### 5.1 Requisitos Funcionais
Definem as principais funcionalidades do aplicativo, como apresentado a seguir:

**Cadastro de usuário:** 
Moradores devem poder se cadastrar com nome, e-mail, senha e endereço.

**Endereço e localização:** 
O endereço deve permitir complemento e ponto de referência, considerando a falta de padronização dos endereços na comunidade.

**Autenticação:** 
O login deve ser realizado com e-mail e senha.

**Busca e produtos:** 
O usuário deve poder buscar, filtrar e visualizar produtos dos estabelecimentos cadastrados.

**Rastreamento de pedidos:**
O status do pedido é atualizado em tempo real (em preparo, saiu para entrega, entregue) com previsão de chegada.

**Processamento de pagamentos:** O aplicativo deve permitir pagamentos por cartão de crédito, débito, Pix ou dinheiro, pelo aplicativo ou na entrega.

**Avaliação do serviço:** 
Depois da entrega, o usuário deve poder avaliar o entregador, o pedido e reportar algum problema em “como foi sua experiência?”.

**Suporte:** 
O aplicativo deve conter um suporte ao cliente em casos de pedido não entregue e pedido estragado. Oferecendo canais de atendimento como um chat ou WhatsApp.

---

### 5.2 Requisitos Não-Funcionais
Descrevem de que forma o aplicativo deve operar, focando na qualidade do software e nas suas restrições, como apresentado a seguir: 

**Capacidade:** 
O aplicativo deve suportar inicialmente até 150 usuários simultâneos.

**Disponibilidade:** 
O aplicativo deve estar sempre acessível ao usuário, independente do horário dos estabelecimentos.

**Compatibilidade:**
O aplicativo deve funcionar em dispositivos iOS e Android.

**Baixo consumo de dados:** 
O aplicativo deve funcionar com eficiência em conexões lentas e instáveis, que é comum em ilhas.

## 6. Restrições & Premissas
### 6.1 Restrições
- O aplicativo só vai funcionar dentro da área geográfica definida (ilha ou comunidade pequena)
- No primeiro momento, não haverá entrega para fora dessa área
- Depende de conexão com a internet para funcionar
- A quantidade de entregadores no começo pode ser limitada

---

### 6.2 Premissas
- A maioria das pessoas da comunidade tem acesso a smartphone ou computador
- Existem comércios locais interessados em usar a plataforma
- Há pessoas dispostas a fazer entregas dentro da comunidade
- A área é pequena o suficiente para que as entregas sejam feitas em pouco tempo
- Os usuários vão preferir uma solução local em vez de aplicativos grandes
- O aplicativo será usado principalmente por moradores fixos da região

## 7. Riscos & Dependências
### 7.1 Riscos 
Riscos são situações que tem uma chance de acontecerem e podem prejudicar o projeto. São alguns deles:

- Poucos clientes
- Poucos comércios cadastrados
- Poucos entregadores disponíveis
- Pouca demanda
- Problemas de internet na ilha

---

### 7.2 Dependências
Depêndencias são fatores importantes para o avanço do projeto, podendo ser definidas entre  Internas e Externas:
#### Internas:
- Definição dos requisitos do sistema
- Desenvolvimento do banco de dados
- Desenvolvimento das interfaces
- Integração entre cliente, comerciante e entregador
#### Externas: 
- Conexão estável com a internet
- Serviço de mapas
- Serviços de hospedagem/nuvem
- Disponibilidade de clientes, comércios e entregadores

---

### 7.3 Sucesso do Aplicativo
Quais os pontos mais importantes a serem considerados para o sucesso do projeto?

**1.** Adesão dos usuários em geral (clientes, comércios e entregadores)

**2.** Eficiência das entregas

**3.** Aplicativo intuitivo e de fácil uso

**4.** Confiabilidade dos usuários

**5.** Viabilidade econômica para todos os envolvidos

**6.** Conectividade

# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Neste capítulo será detalhado o escopo e os pontos mais relevantes a serem tratados neste projeto.  Para isso, foi realizado pela equipe do projeto um trabalho de imersão junto aos usuários por meio de conversas e entrevistas. Os dados obtidos foram analisados e consolidados na forma de personas e histórias de usuário. (Pontifícia Universidade Católica de Minas Gerais, 2021, p.6)

## Personas

(imgs)


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|SOS Bichos Protetor |Mecanismo para ajudar a divulgar animais para adoção. | Para realizar um processo de adoção de animais mais seguro. |
|SOS Bichos Protetor |Um local para postar as fotos e vídeos dos animais disponíveis para adoção. | Para melhorar a divulgação dos animais que estão sem lar definitivo e precisam ser adotados. |
|SOS Bichos Protetor |Para ajudar no processo de adoção. | Para diminuir o número de animais em abrigos. |
|Adotante |Uma plataforma que possibilite a visualização dos animais em adoção | Para facilitar a localização do animal. |


## Requisitos

Os requisitos funcionais e não funcionais têm por objetivo descrever as possibilidades de interação dos usuários e os aspectos gerais do sistema. (Pontifícia Universidade Católica de Minas Gerais, 2021, p.7)

### Requisitos Funcionais

A partir das histórias de usuário criadas, foram definidos os seguintes requisitos funcionais e não funcionais do projeto.

|ID     | Descrição do Requisito  | Prioridade |
|-------|-----------------------------------------|----|
|RF-001 | O site deve apresentar na página inicial um menu com os seguintes submenus: quero adotar, cadastrar animais para  adoção, quem somos. | ALTA | 
|RF-002 | O site deve apresentar imagens dos animais disponíveis para adoção. | ALTA |
|RF-003 | Quando o usuário clicar na foto do animal disponível para adoção, o site deve redirecioná-lo para uma tela com as informações do animal. | ALTA |
|RF-004 | O site deve ter um formulário para preenchimento do usuário quando ele desejar se cadastrar e após ele realizar o cadastro deverá ser disponibilizado um login e senha para acesso ao site. | ALTA |
|RF-005| O site deve conter no espaço do cadastro de animais, a opção de excluir/editar os dados dos animais disponíveis ou adotados. | MÉDIA |
|RF-006 |O site deve apresentar para o usuário uma página com as informações de “quem somos”. | MÉDIA |
|RF-007 | O site deve apresentar botão de login na página inicial, para o usuário poder entrar numa conta já registrada ou realizar seu cadastro. | ALTA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O site deve ser publicado em um ambiente acessível pela Internet| ALTA | 
|RNF-002|Deverá ser possível acessar o site de qualquer navegador (Google Chrome, Safari, etc) |  ALTA | 
|RNF-002| O site deve ter validações de segurança como captcha |  ALTA | 
|RNF-002| O site deverá ser responsivo |  MÉDIA | 



## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| A data limite para entrega deste projeto é curta |
|02| O site não se responsabiliza pela intermediação entre o tutor e adotante |



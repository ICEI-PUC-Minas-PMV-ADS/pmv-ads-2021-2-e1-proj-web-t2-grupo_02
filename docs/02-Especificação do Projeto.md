# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Neste capítulo será detalhado o escopo e os pontos mais relevantes a serem tratados neste projeto.  Para isso, foi realizado pela equipe do projeto um trabalho de imersão junto aos usuários por meio de conversas e entrevistas. Os dados obtidos foram analisados e consolidados na forma de personas e histórias de usuário. (Pontifícia Universidade Católica de Minas Gerais, 2021, p.6)

## Personas

(imgs)


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|SOS Bichos Protetor |Mecanismo para ajudar na procura de pessoas responsáveis para adotar os animais. | Para realizar um processo de adoção de animais mais seguro. |
|SOS Bichos Protetor |Um local para postar as fotos e vídeos dos animais disponíveis para adoção. | Para melhorar a divulgação dos animais que estão sem lar definitivo e precisam ser adotados. |
|SOS Bichos Protetor |Ter um local para realizar o contato com as pessoas adotantes.| Para melhor acompanhar o processo pós adoção.|
|SOS Bichos Protetor |Encontrar pessoas que possam oferecer um lar temporário.| Para ajudar no processo de adoção e diminuir o número de animais nos abrigos.|
|SOS Bichos Protetor |Eu quero visualizar as informações do adotante/tutor temporário de forma fácil em uma plataforma. | Para a garantir a segurança do anila após o processo de adoção |
|SOS Bichos Protetor |Quero poder receber doações através de uma plataforma de adoção.| Para garantir os cuidados com o animal e alimentação. |
|Adotante |Uma plataforma que possibilite a visualização dos animais em adoção | Para facilitar a localização do animal que mais se enquadra com meu perfil. |
|Adotante |Informações sobre como funciona o processo de adoção e como adaptar o animal em seu novo lar | Para auxiliar no processo de adoção. |
|Adotante |Eu quero receber sugestões de animais de estimação que combinem com o meu perfil | Para facilitar a busca por um animal que tenha o meu perfil. |
|Adotante |Eu quero poder interagir com o protetor/ONG durante e após o processo de adoção | Para tirar dúvidas, receber feedback do animal e solicitar auxílio se necessário. |


## Requisitos

Os requisitos funcionais e não funcionais têm por objetivo descrever as possibilidades de interação dos usuários e os aspectos gerais do sistema. (Pontifícia Universidade Católica de Minas Gerais, 2021, p.7)

### Requisitos Funcionais

A partir das histórias de usuário criadas, foram definidos os seguintes requisitos funcionais e não funcionais do projeto.

|ID     | Descrição do Requisito  | Prioridade |
|-------|-----------------------------------------|----|
|RF-001 | O site deve apresentar na página inicial um menu com os seguintes submenus: nossa história, quero adotar, quero ser lar temporário, quero cadastrar animais para  adoção, informações. | ALTA | 
|RF-002 | O site deve apresentar na página inicial um campo de pesquisa para busca dentro do site. | ALTA |
|RF-003 | O site deve apresentar imagens dos animais disponíveis para adoção. | ALTA |
|RF-004 | Quando o usuário clicar na foto do animal disponível para adoção, o site deve redirecioná-lo para uma tela com as informações do animal. | ALTA |
|RF-005 | O site deve apresentar os usuários que estão interessados em adotar. Essa opção só deverá ficar disponível para as ONGs e protetores que realizarem o cadastro no site. | ALTA |
|RF-006 | Quando o usuário clicar na foto de uma pessoa que quer adotar, o site deve redirecioná-lo para uma tela com as informações do adotante. | ALTA |
|RF-007 | O site deve ter um botão com a opção para o usuário realizar o seu cadastro. | ALTA |
|RF-008 | O site deve ter um formulário para preenchimento do usuário quando ele desejar se cadastrar e após ele realizar o cadastro deverá ser disponibilizado um login e senha para acesso ao site. | ALTA |
|RF-009 | O site deve realizar o cruzamento entre as informações do cadastro do adotante e os dados dos animais disponíveis e apresentar para o usuário quando ele estiver logado no site os animais que mais combinam com o seu perfil. | ALTA |
|RF-010 | O site deve ter informações para o usuário sobre o processo de adoção, termo de adoção e guarda responsável e orientações sobre como adaptar o animal no novo lar. | ALTA |
|RF-011 |O site deve apresentar para o usuário uma página com as informações de “quem somos”. | MÉDIA |
|RF-012 | O site deve apresentar na página inicial um campo Fale Conosco contendo as informações para contato. | BAIXA |




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



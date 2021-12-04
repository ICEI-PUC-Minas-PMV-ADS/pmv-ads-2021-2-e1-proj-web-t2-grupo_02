# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Neste capítulo será detalhado o escopo e os pontos mais relevantes a serem tratados neste projeto.  Para isso, foi realizado pela equipe do projeto um trabalho de imersão junto aos usuários por meio de conversas e entrevistas. Os dados obtidos foram analisados e consolidados na forma de personas e histórias de usuário. (Pontifícia Universidade Católica de Minas Gerais, 2021, p.6)

## Personas

### Thamara Machado Rocha

#### Descrição

* Idade: 29 anos
* Estado Civil: Casada
* Naturalidade: Belo Horizonte, MG
* Formação: Gradruação em andamento em Análise e Desenvolvimento de Sistemas, e Economia.

#### Ativadades:
* Ocupação: Analista de projeto
* Redes sociais: Instagram, Linkedin, Whatsapp.
* Hobbies: Viajar, andar de bicicleta, fazer trilha, cachoeira, cinema, sair pra comer.

#### Motivação:
* Empatia e compaixão em relação aos aniamis abandonados e maltratados.
* Adora animais.
* Defensora da causa animais.
* Ama gatos.

#### Frustações:
* Dificuldades de encontrar adotantes, especialmente para gatos.
* Difciuldade de acolher os animais no ato de resgate.
* Dificuldade na captação e recursos financeiros para saúde e alimentação dos animais.
* Acompanhamento no pós adoção.

### Alisson Santos Guedes

#### Descrição
* Idade: 27 anos
* Estado civil: casado
* Naturalidade: Belo Horizonte, MG
* Formação: Graduação Licenciatura Física

#### Atividades:
* Ocupação: Product Owner (Dono do produto)
* Redes sociais: Instagram, Twitter, Linkedin, Whatsapp, Facebook.
* Hobbies: Jogar video-games, ler mangás, andar de bicleta, fazer trilha e cachoeira.

#### Motivação:
* Considera os aniamis de estimação parte integrante do grupo familiar.
* Gosta muito de animais, especialmente gatos.
* Considera os animais divertidos.
* Empatia pelos animais

#### Frustações:
* Dificuldade em adaptação do animal
* Custos altos
* Cuidados diários com o animal (saúde, alimentação).


### Iris Midlej

#### Descrição
* Idade: 22 anos
* Estado civil: Solteira
* Naturalidade: Rio de Janeiro, RJ
Formação: Graduação em andamento em Museologia

#### Atividades
* Redes sociais: Instagram, Twitter, Whatsapp
* Hobbies: Pintar, ler e estudar

#### Motivações:
* Quer adotar um animal que combine com sua rotina calma

#### Frustações:
* Nunca são claros sobre a personalidade do animal
* Tem dificuldade de encontrar um animal que tenha um perfil compatível com sua rotina.


### SOS BICHOS

#### Descrição
* Tempo de atuação: 18 anos
* História: organicação sem fins lucrativos, atuante em Belo Horizonte e região. Foi fundada em 2003 por duas amigas, Mariana e Isabela. Conta com uma rede de apoio formada por empresas parceiras, como clínicas veterinárias, estações de rádio e marcas de ração animal.

#### Atividades
* Redes sociais: Blog, Instagram e Facebook
* Atuação: resgate de animais abandonados, cuidados gerais dos animais, busca de adotantes, auxílio na divulgação de animais disponíveis para adoção que não estão sob tutela da ONG e ações para a divulgação dos direitos animais.

#### Motivação:
* Esclarescer a sociedade sobre a importância da adoção e suas responsabilidades
* Divulgar a causa animail para que seus direitos sejam reconhecidos e valorizados, baseados na importante declaração universal dos direitos dos animais
* Assegurar o direito a vida e proteger os animais contra maus tratos e outros atos cruéis.
* Retorno positivos das adoções realizadas

#### Frustações:
* O descaso e despreparo dos órgãos públicos principalmente no momentos de abrigar ou prestar atendimento médico aos animais resgatados
* Encontrar animais vítimas de instrumentalização e escravidão
* Famílias que adotam ou que acolhem o animal e devolvem em um período muito curto de tempo
* Escassez de recursos financeiros 
* Dificuldade de conseguir doações, voluntários e empresas parceiras.
* Retaliação por parte da poupulação pelo trabalho executado
* Ausência de companhas de adoção





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
|RF-001 | O site deve apresentar na página inicial um menu com os seguintes submenus: quero adotar, cadastrar animais para adoção, quem somos. | ALTA | 
|RF-002 | Quando o usuário clicar no submenu Quero Adotar, ele deverá ser redirecionado para uma tela onde deverá ser apresetando as imagens dos animais disponíveis para adoção. | ALTA |
|RF-003 | Quando o usuário clicar na foto do animal disponível para adoção, o site deve redirecioná-lo para uma tela com as informações do animal. | ALTA |
|RF-004 | Quando o usuário clicar no submenu Cadastrar, ele deverá ser redirecionado para uma tela para realização do cadastro no site. A tela deverá conter um formulário para preenchimento do usuário com os seguintes campos: nome, telefone, data de nascimento, e-mail, endereço, gênero, complemento, ocupação e senha. E após o cadastro deverá ser disponibilizado para o usuário a informação do login para acesso ao site. | ALTA |
|RF-005| O site deve ter a opção de excluir os dados dos animais cadastrados no site. | MÉDIA |
|RF-006 | Quando o usuário clicar no submenu Quem Somos, ele deverá ser redirecionado para uma página contendo algumas informações instituições da empresa criadora e mantedora do site. | MÉDIA |
|RF-007 | O site deve apresentar botão de login na página inicial, para o usuário poder entrar numa conta já registrada no site. | ALTA |
|RF-008 | Quando o usuário estiver logado no site, deverá ser apresentado para ele a opção de Cadastrar Pet. E quando o usuário clciar nesta opção, ele deverá ser redirecionado para uma tela contendo um formulário com os seguintes campos: nome, gênero do animal, descrição do animal, tipo, situação, peso, campo para upload da imagem do animal. | ALTA |
|RF-009 | O site deverá ter um campo para que o usuário possa pesquisar uma determinada palavra ou conteúdo no site. | MÉDIA |
|RF-010 | O site deverá ter um atalho para acesso as redes sociais twitter, instragram e facebook do site. | MÉDIA |
|RF-011 | O site deverá conter um campo para cadastro para recebimento da  newsletter. | MÉDIA |

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



# Plano de Testes de Software

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>

Apresente os cenários de testes utilizados na realização dos testes da sua aplicação. Escolha cenários de testes que demonstrem os requisitos sendo satisfeitos.

Enumere quais cenários de testes foram selecionados para teste. Neste tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo de usuários que foi escolhido para participar do teste e as ferramentas utilizadas.
 
### Caso de Teste	CT-01 Apresentar menu principal	
Requisitos Associados: RF-001 O site deve apresentar na página inicial um menu com os seguintes submenus: quero adotar, cadastrar animais para adoção, quem somos.	
Objetivo do Teste	Validar que o menu principal e os submenus são exibidos corretamente na página principal do site 	
Passos
- 1°) Acessar o navegador
- 2°) Inserir o endereço do site 
- 3°) Visualizar a página inicial do site 
- 4°) Clicar no botão de menu do site  <br>
Critérios de Êxito : 	Ao clicar no botão do menu principal, deverão ser habilitados os seguintes submenus: quem somos, quero adotar e cadastrar. <br>
Registro de Execucação:	Teste executado com sucesso 	
		
### Caso de Teste	CT-02 Visualizar as imagens dos animais disponíveis para adoção	
Requisitos Associados	"RF-002 Quando o usuário clicar no submenu Quero Adotar, ele deverá ser redirecionado para uma tela onde deverá ser apresetando as imagens dos animais disponíveis para adoção."	<br>	
Objetivo do Test : Validar que ao clicar no submenu Quero Adotar, o usuário é redirecionado para uma tela onde ele consegui visualizar os animais disponíveis para adoção	
Passos	
- 1°) Acessar o navegador
- 2°) Inserir o endereço do site 
- 3°) Visualizar a página inicial do site 
- 4°) Clicar no botão de menu do site 
- 5°) Clicar no submenu Quero Adotar"	<br>
Critérios de Êxito :	"Ao clicar no botão do menu principal deverá ser habilitado o submenu Quero Adotar 
Ao selecionar o submenu Quero Adotar o usuário deverá ser redirecionado para uma tela contendo as imagens dos animais "	<br>
Registro de Execucação:	Teste executado com sucesso <br>	
		
### Caso de Teste	CT-03 Visualizar as informações do animal disponível para adoção	
Requisitos Associados	RF-003 Quando o usuário clicar na foto do animal disponível para adoção, o site deve redirecioná-lo para uma tela com as informações do animal.	
Objetivo do Teste	Validar que ao clicar na foto do animal disponível para adoção, o usuário é redirecionado para uma tela contendo as informações do animal	
Passos	
- 1°) Acessar o navegador
- 2°) Inserir o endereço do site 
- 3°) Visualizar a página inicial do site 
- 4°) Clicar no botão de menu do site 
- 5°) Clicar no submenu Quero Adotar
- 6°) Clicar na foto do animal disponível para adoção"	<br>
Critérios de Êxito :	"Ao clicar no botão do menu principal deverá ser habilitado o submenu Quero Adotar
Ao selecionar o submenu Quero Adotar o usuário deverá ser redirecionado para uma tela contendo as imagens dos animais 
Ao cicar na foto do animal o usuário deverá ser redirecionado para uma tela contendo a imagem, a histórias e as informações de contato para adoção do animal"	<br>
Registro de Execucação:	Teste executado com sucesso 	
		
### Caso de Teste	CT-04  Realizar o cadastro no site	
Requisitos Associados	RF-004 Quando o usuário clicar no submenu Cadastrar, ele deverá ser redirecionado para uma tela para realização do cadastro no site. A tela deverá conter um formulário para preenchimento do usuário com os seguintes campos: nome, telefone, data de nascimento, e-mail, endereço, gênero, complemento, ocupação e senha. E após o cadastro deverá ser disponibilizado para o usuário a informação do login para acesso ao site.	
Objetivo do Teste	Validar que ao clicar no menu de Cadastro o usuário é redirecionado para uma tela onde deverá preencher os seus dados para realização do seu cadastro no site 	
Passos	
- 1°) Acessar o navegador
- 2°) Inserir o endereço do site 
- 3°) Visualizar a página inicial do site 
- 4°) Clicar no botão de menu do site 
- 5°) Clicar no submenu Cadastrar
- 6°) Preencher o formulário"	<br>
Critérios de Êxito :	"Ao clicar no botão do menu principal deverá ser habilitado o submenu Cadastrar
Ao selecionar o submenu Cadastrar o usuário deverá ser redirecionado para uma tela contendo os seguintes campos para preenchimento: nome, telefone, data de nascimento, e-mail, endeereço, gênero, complemento, ocupação e senha.
O usuário não deverá conseguir prosseguir com o cadastro no site se um dos campos do formulário não for preenchido
Após o preenchimento do formulário o usuário deverá receber a informação do login para acesso ao site
"	<br>
Registro de Execucação:	Falha no teste: a informação do login não foi disponibilizada para o usuário 	
		
### Caso de Teste	CT-05  Exluir os dados de um animal cadastrado no site	
Requisitos Associados	RF - 005 O site deve ter a opção de excluir/editar os dados dos animais cadastrados no site	
Objetivo do Teste	Validar que é possível excluir  os dados de um animal que esteja cadastrado no site 	
Passos	
- 1°) Acessar o navegador
- 2°) Inserir o endereço do site 
- 3°) Visualizar a página inicial do site 
- 4°) Realizar o login no site 
- 5°) Clicar na opção excluir na foto do animal desejado" <br>	
Critérios de Êxito 	"O  usuário deve conseguir realizar o login com o usuário e senha criados no momento do cadastro do site
Ao realizar o login no site o usuário deverá visualizar as fotos dos animais que foram cadastrados por ele no site 
Ao realizar o login no site o usuário deverá ter a opção de excluir os dados de um animal cadastrado por ele no site "	<br>
Registro de Execucação:	Falha no teste: ao clicar na opção de excluir a foto do animal não é excluida 	<br>
		
### Caso de Teste	CT-06  Editar os dados de um animal cadastrado no site	
Requisitos Associados	RF - 005 O site deve ter a opção de excluir/editar os dados dos animais cadastrados no site	
Objetivo do Teste	Validar que é possível editar os dados de um animal que esteja cadastrado no site 	
Passos	
- 1°) Acessar o navegador
- 2°) Inserir o endereço do site 
- 3°) Visualizar a página inicial do site 
- 4°) Realizar o login no site 
- 5°) Clicar na foto do animal que deseja editar os dados 
- 6°) Preencher o formulário com os novos dados "	<br>
Critérios de Êxito 	"O  usuário deve conseguir realizar o login com o usuário e senha criados no momento do cadastro do site
Ao realizar o login no site usuário deverá visualizar as fotos dos animais que foram cadastrados por ele no site 
Ao realizar o login no site o usuário deverá ter a opção de editar os dados de um animal cadastrado por ele no site "	<br>
Registro de Execucação:	Falha no teste: ao clicar na imagem do animal o usuário não foi redirecionado para a tela de edição dos dados do animal	
		
### Caso de Teste	CT-07  Visualizar as informações institucionais do site 	
Requisitos Associados	RF - 006 Quando o usuário clicar no submenu Quem Somos, ele deverá ser redirecionado para uma página contendo algumas informações instituições da empresa criadora e mantedora do site 	
Objetivo do Teste	Validar que ao clicar no submenu Quem Somos o usuário é redirecionado para uma tela contendo as informações institucionais do site 	
Passos	
- 1°) Acessar o navegador
- 2°) Inserir o endereço do site 
- 3°) Visualizar a página inicial do site 
- 4°) Clicar no botão de menu do site
- 5°) Clicar no submenu Quem Somos"	<br>
Critérios de Êxito :	"Ao clicar no menu principal deverá ser habilitado o submenu Quem Somos
Ao clicar no submenu Quem Somos o usuário deverá ser redirecionado para uma tela com as informações institucionais do site "	<br>
Registro de Execucação:	Teste executado com sucesso	
		
### Caso de Teste	CT-08  Realizar login no site 	
Requisitos Associados	RF - 007 O site deve apresentar botão de login na página inicial, para o usuário poder entrar numa conta já registrada no site	
Objetivo do Teste	Validar que um usuário já cadastrado no site consegue realizar o login no site 	
Passos	
- 1°) Acessar o navegador
- 2°) Inserir o endereço do site 
- 3°) Visualizar a página inicial do site 
- 4°) Clicar no botão de login
- 5°) Digitar usuário e senha de senha criados no momento do cadastro no site "	<br>
Critérios de Êxito :	"O botão de login deverá estar disponível no site 
O  usuário deve conseguir realizar o login com o usuário e senha criados no momento do cadastro do site"<br>	
Registro de Execucação:	Teste executado com sucesso	
		
### Caso de Teste	CT-09 Cadastrar animal no site 	
Requisitos Associados	RF - 008 Quando o usuário estiver logado no site, deverá ser apresentado para ele a opção de Cadastrar Pet. E quando o usuário clciar nesta opção, ele deverá ser redirecionado para uma tela contendo um formulário com os seguintes campos: nome, gênero do animal, descrição do animal, tipo, situação, peso, campo para upload da imagem do animal. 	
Objetivo do Teste	Validar que ao logar no site é possível realizar o cadastro de um animal 	
Passos	
- 1°) Acessar o navegador
- 2°) Inserir o endereço do site 
- 3°) Visualizar a página inicial do site 
- 4°) Clicar no botão de login
- 5°) Digitar usuário e senha de senha criados no momento do cadastro no site 
- 6°) Clicar na opção Cadastrar Pet
- 7°) Preencher o formulário com os dados e imagem do animal"	<br>
Critérios de Êxito 	:"O botão de login deverá estar disponível no site 
O  usuário deve conseguir realizar o login com o usuário e senha criados no momento do cadastro do site
Após o login no site, deverá ser habilitado para o usuário a opção de Cadastrar Pet
Ao clicar na opção Cadastrar Pet, o usuário deverá ser redirecionado para uma tela contendo os seguintes campos: nome, gênero do animal, descrição do animal, tipo, situação, peso, situação e campo para upload da imagem do animal.
Todos os campos do formulário deverão ser de preenchimento obrigatório"	<br>
Registro de Execucação:	Teste executado com sucesso	
		
### Caso de Teste	CT-10 Realizar uma pesquisa no site 	
Requisitos Associados	RF - 009 O site deverá ter um campo para que o usuário possa pesquisar uma determinada palavra ou conteúdo no site	
Objetivo do Teste	Validar que o site possui um campo de pesquisa e que ao digitar uma palavra ou conteúdo neste campo é feita uma busca dentro do site 	
Passos	
- 1°) Acessar o navegador
- 2°) Inserir o endereço do site 
- 3°) Visualizar a página inicial do site 
- 4°) Digitar uma palavra ou conteúdo no campo Pesquisar do site "	<br>
Critérios de Êxito 	:"Na página inicial do site deverá constar o botão de pesquisar
Ao digitar uma palavra ou conteúdo no campo de pesquisar o site deverá redirecionar o usuário para uma tela contendo o resultado da busca pela palavra ou contéudo digitado"	<br>
Registro de Execucação:	Falha no teste: ao buscar uma palavra o usuário não foi redirecionado para uma tela com o resultado da pesquisa	
		
		
### Caso de Teste	CT-11 Acessar as redes sociais instagram, twitter e facebook do site 	
Requisitos Associados	RF - 010 O site deverá ter um atalho para acesso as redes sociais twitter, instragram e facebook do site	
Objetivo do Teste	Validar que o site possui um atalho para acesso ao twitter, instagram e facebook e que ao clicar no atalho o usuário é redirecionado para a rede social corretamente 	
Passos	
- 1°) Acessar o navegador
- 2°) Inserir o endereço do site 
- 3°) Visualizar a página inicial do site 
- 4°) Clicar no atalho para acesso ao instagram 
- 5°) Clicar no atalho para acesso ao facebook
- 6°) Clicar no atalho para acesso ao twitter"	<br>
Critérios de Êxito :	"O site deverá conter os atalhos para acesso ao instagram, facebook e twitter
Ao clicar no ícone de atalho para o instagram, o usuário deverá ser redirecionado para a página do instagram do site <br>
Ao clicar no ícone de atalho para o twitter, o usuário deverá ser redirecionado para a página do twitter do site <br>
Ao clicar no ícone de atalho para o facebook, o usuário deverá ser redirecionado para a página do facebook do site"	<br>
Registro de Execucação:	Teste executado com sucesso 	
		
### Caso de Teste	CT-12 Cadastro para recebimento da Newsletter	
Requisitos Associados	RF - 011 O site deverá conter um campo para cadastro para recebimento da  newsletter	
Objetivo do Teste	Validar que o site possui um campo para cadastro para recebimento da newsletter	
Passos	
- 1°) Acessar o navegador
- 2°) Inserir o endereço do site 
- 3°) Visualizar a página inicial do site 
- 4°) Realizar o cadastro para recebimento da newsletter"	<br>
Critérios de Êxito :	"O site deverá conter um campo para cadastramento da newsletter
Deverá ser feita a validação se o e-mail digitado para cadastro da newsletter é um e-mail válido"	<br>
Registro de Execucação:	Teste executado com sucesso 	
		


# Projeto de Interface

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Documentação de Especificação</a></span>
## User Flow

Estes são os possíveis caminhos que diferentes tipos de usuários podem fazer em nossa plataforma.

A imagem a seguir é um exemplo de fluxo do usuário (lar temporário).


![Flowchart (2)](https://user-images.githubusercontent.com/83349744/135725610-5cb215b9-e17b-49f3-a93a-8f659a3e716a.jpg)


Neste link poderá ver as telas e seguir os fluxos - https://xd.adobe.com/view/27ec903f-3ac1-4336-b7ef-4f33df1a608c-72bf/ -

<h3>CASO O USUÁRIO QUEIRA ADOTAR: </h3>
Assim que entra na plataforma, ele é apresentado à <b> tela inicial </b> .
(Tela 1) que possui as opções de <b> Login, Pesquisar, Menu, Newsletter </b> e nossas <b> redes sociais </b> além de um <b> "Fale conosco"</b> .

Caso ele opte por seguir pelo primeiro caminho <b>(Login)</b>, ele é
redirecionado para a tela de Login (Tela 2), onde pode
se cadastrar ou seguir adiante com o Login. Nessa tela caso ele clique em <b>Cadastrar</b>, ele é enviado para o nosso formulário (Tela 3) onde deverá preencher. 
Ele registra seu nome, sexo, endereço, idade e ocupação, seguindo da espécie que deseja adotar. Quando clica em enviar é redirecionado para a tela que mostrará alguns matches (Tela 4).

Escolhendo o seu pet ideal e selecionando-o, será levado para sua história (Tela 5), onde poderá seguir dois caminhos.
O primeiro seria dar <b>petmatch</b> (Botão Match!) que levará para a tela de <b>ficha de adoção</b>, onde terá os termos e a declaração de que concorda com eles. Enviando a ficha, será redirecionado para a Tela 6, onde avisará que sua ficha foi enviada ao tutor do animal e que em breve será respondido.
Caso o usuário clique na foto do animal, o status do processo será revelado na tela. (Tela 7)
E se clicar em <b>"Entrar em contato"</b>, mostrará as informações da ong, lar temporário ou do tutor (no momento) do animal.

Voltando a Tela 5, o segundo caminho seria "Entrar em contato" direto. 


<b>OBS:</b> Caso o usuário clicasse em "Quero adotar" no MENU ele seria redirecionado para a Tela 8 onde mostrará vários pets registrados na plataforma. Ele poderá tanto escolher um pet, onde será encaminhado para a tela 5, dando continuidade para a rota, assim como poderá escolher se cadastrar (Tela 2) ou seguir seu Login.



<h3>CASO O USUÁRIO QUEIRA SER LAR TEMPORÁRIO: </h3>

Assim que entra na plataforma, ele é apresentado à tela inicial (Tela 1). Considerando que o usuário entrou na plataforma com objetivo de ser lar temporário, ele clicará em Menu onde mostrará várias opções para seguir (Tela 8).
Clicando em <b>"Lar temporário"</b> será levado para tela do nosso <b>formulário de lar temporário</b>(tela 9 e tela 10). Finalizando ele receberá um aviso de que foi enviado um email, seguido do botão de "Início" onde poderá retornar a Tela inicial (tela 1).


<h3> CASO O USUÁRIO QUEIRA DOAR UM ANIMAL: </h3>
Escolhendo em nosso MENU (tela 8) a opção de <b>"Cadastrar animais"</b>, ele será enviado para nosso formulário para Cadastro de Animais (tela 11). Preenchendo as suas informações e do animal, poderá enviar para nossa plataforma.  Em seguida, o usuário é redirecionado a página inicial.


<h3> CASO O USUÁRIO QUEIRA VIZUALIZAR NOSSA HISTÓRIA: </h3>
Entrando na plataforma vizualizará a tela inicial (tela 1). Clicando em Menu (tela 8) ele verá as opções. Optando por <b>"Nossa História"</b> a tela descrevendo a história de como a idéia da plataforma foi criada será gerada (tela 12).


<h3> CASO O USUÁRIO QUEIRA VER INFORMAÇÕES: </h3>

Entrando na plataforma vizualizará a tela inicial (tela 1). Clicando em Menu (tela 8) ele verá as opções. Optando por <b>"Informações"</b> ele será redirecionado a uma tela com informações a mais sobre o site (tela 13).



## Wireframes

Conforme fluxo de telas do projeto, apresentado no item anterior, as telas do sistema são apresentadas em detalhes nos itens que se seguem. As telas do sistema apresentam uma estrutura comum que é apresentada na Figura X. Nesta estrutura, existem 3 grandes blocos, descritos a seguir. São eles:
Cabeçalho - local onde são dispostos o logo, login e navegação principal do site (menu da aplicação) e a barra de pesquisa;
Conteúdo - apresenta o conteúdo da tela em questão;
Rodapé - apresenta nossas redes sociais, fale conosco e opção de newleaster.

### Tela - Inicial ou Home-page
A tela de home-page mostra a imagem de um animal. Apresenta um componente de pesquisa que permite substituir o conteúdo da página com o resultado da busca solicitada pelo usuário;
Um menu pra que vá direto ao objetivo do usuário em questão;
Componente de Login para caso queira entrar em sua conta já registrada ou se registrar em nosso site.
O rodapé é padronizado, contendo nossas redes sociais, fale conosco e newsletter.

![TELA INICIAL](https://user-images.githubusercontent.com/83349744/135902314-0bb83376-9e61-4da8-aea0-4451e732c22c.png)


### Tela - Login
A tela possui componentes que permitem que o usuário cadastre-se no site ou entre em uma conta já existente. Um campo de "Usuário" e "Senha" onde pressionando em "Entrar" fará Login em sua conta, um texto explicando o que nossa plataforma pode, em uma de suas funcionalidades, proporcional caso se cadastre seguido de um botão de "Cadastrar".

![LOGIN](https://user-images.githubusercontent.com/83349744/135903337-4eaf2079-b14f-4d6d-9d93-f07de299aed8.png)

### Tela - Cadastro
A tela de Cadastro apresenta os campos a serem preenchidos para ser registrado na plataforma e conseguir encontrar seu pet ideal. Esses campos contam com "Nome", "Idade", "Sexo", "Endereço", "Ocupação", "Espécie". Quando completado, deve enviar o formulário.

![CADASTRO](https://user-images.githubusercontent.com/83349744/135903984-a41d42a9-aa42-425b-85fb-db72c733f61c.png)

### Tela - Match!
Quando enviado seu cadastro, ou já registrado na plataforma, encontramos pets que possuem compatibilidade com o seu perfil, e na tela fica disposto um campo com algumas imagens dos pets compatíveis. Clicando em uma delas, você é redirecionado.

![PERFIL MATCH](https://user-images.githubusercontent.com/83349744/135921016-6e30fc1b-945b-4159-870c-b040249ae0fc.png)

Esta é uma variação da tela de Match, onde apenas o botão de "entrar em contato" não aparece. Ele é apresentado quando um tutor ou ONG não quer expor seu endereço (da ong ou pessoal). Porém a ONG (ou tutor) ainda sim entrará em contato pela plataforma, email ou celular caso siga em processo de adoção. (OBS: Alguns lugares evitam se expor para não acontecer infortúnios como pessoas abandonando animais em frente de suas portas)

![PET MATCH](https://user-images.githubusercontent.com/83349744/135914088-15d7041f-c46e-4120-b95a-1b68f0f2c1fb.png)

### Tela - História do Pet

Nesta tela a história do resgate do pet e de sua personalidade são apresentadas. Caso o usuário goste do pet ele possui duas opções: clicar em "Match!" seguindo assim para o processo de adoção, ou clicar em "Entrar em Contato" onde o usuário terá as informações da ONG (ou tutor) caso queira ligar ou fazer uma visita por exemplo.

![HIST PET](https://user-images.githubusercontent.com/83349744/135906373-4cbd4d47-254c-4086-9f80-04fe0b0bba28.png)

### Tela - Entrar em contato
Esta é a tela onde as informações da ONG (ou tutor) aparecem.

![ENTRAR EM CONT](https://user-images.githubusercontent.com/83349744/135906716-702eab09-7ee8-44dc-9cf1-c08972501e11.png)


### Tela - Ficha de Adoção
Caso o usuário tenha dado "Match!" no animal, ele será redirecionado a tela de ficha de adoção. Nesta tela existirá um termo de adoção, onde o usuário poderá ler o termo e terá de declarar que está de acordo com estes, seguindo com o processo de adoção, onde assim terá de esperar a resposta do responsável pelo pet.

![FICHA DE ADOÇÃO](https://user-images.githubusercontent.com/83349744/135920827-31be4db9-dca1-4721-82ba-85bfdf065f7c.png)


### Tela - Parabéns
A tela de parabéns aparece ao enviar sua ficha de adoção. Nela vai conter a explicação do processo de adoção e onde poderá encontrar o seguimento do processo.

![PARABENS](https://user-images.githubusercontent.com/83349744/135909041-15899eee-3857-4bee-9689-bc05e980bca6.png)

### Tela - Status de adoção
Ao clicar na foto do animal poderá ver o andamento de seu processo de adoção. Terá a opção de entrar em contato na tela, para caso tenha alguma dúvida ou problema, poderá contatar a ONG (ou tutor) em questão.

![STATUS](https://user-images.githubusercontent.com/83349744/135909436-6a21eb2e-a150-4cbb-9228-0c0a804df2bc.png)

### Tela - Quero adotar
Se o usuário decidir ir direto em Quero Adotar, esta tela será apresentada. Ela pedirá que se cadastre no site, logo o botão de Cadastrar estará na tela. É necessário que o usuário seja cadastrado para dar continuidade ao processo de adoção, que foi apresentado nas telas anteriores e no fluxo de usuário.

![QUERO ADOTAR](https://user-images.githubusercontent.com/83349744/135913470-e65f3c38-a840-4dba-a8f1-a1b54efe483c.png)

### Tela - Cadastrar animais
Ao escolher a categoria "Cadastrar animais" no Menu, será enviado a este formulário em nossa plataforma, onde poderá preencher com as informações do animal em questão. 

![CADASTRAR ANIMAIS](https://user-images.githubusercontent.com/83349744/135910789-25061f4d-27c6-4a9f-8797-63894d464f49.png)

### Tela - Forneça um Lar temporário
Esta seção contém um formulário para ser preenchido caso o usuário queira dar lar temporário aos animais da plataforma. Neste caso, possui duas telas pois uma é continuidade do formulário da anterior. É importante preencher estes campos para ser qualificado como um protetor apto à lar temporário.

![LAR TEMP](https://user-images.githubusercontent.com/83349744/135911762-312d152e-c793-4397-a33f-d863e2ea5aef.png)

![LAR TEMP2](https://user-images.githubusercontent.com/83349744/135912254-37c8b89f-40e9-43d4-a1bc-6ab9caead752.png)

### Tela - Parabéns (Lar temporário)
Esta tela aparece ao final do preenchimento do cadastro de lar temporário. Com ele um aviso de que recebrá um email de confirmação, e com instruções para os próximos passos caso esteja apto. Na sequência, um botão para voltar a Tela inicial.

![LAR TEMP3](https://user-images.githubusercontent.com/83349744/135912793-665910a3-d905-4711-9db4-30b83a7d9194.png)

### Tela - Informações 
Quando selecionada a opção no menu de "Informações", uma tela será apresentada onde contém uma imagem de um pet (não necessariamente em adoção na plataforma) e informações a mais sobre a plataforma PetMatch.

![INFORMAÇÕES](https://user-images.githubusercontent.com/83349744/135914453-f15688d6-5d77-47e2-9468-d9020c876121.png)

### Tela - Nossa história
Ao clicar em "Nossa história" no Menu, será redirecionado a uma tela contando a história de como a idéia surgiu e o objetivo da plataforma. Também conterá a imagem de um pet (não necessariamente em adoção na plataforma).

![NOSSA HISTORIA](https://user-images.githubusercontent.com/83349744/135914825-dbdaf354-2a59-4578-843a-96f6d4ca57cb.png)



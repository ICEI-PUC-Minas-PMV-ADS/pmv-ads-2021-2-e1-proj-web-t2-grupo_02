
# Projeto de Interface

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Documentação de Especificação</a></span>

A identidade visual do projeto é padronizada e minimalista, para que se torne simples de usar 
## User Flow

Estes são os possíveis caminhos que diferentes tipos de usuários podem fazer em nossa plataforma.

<h3>CASO O USUÁRIO QUEIRA ADOTAR: </h3>
Assim que entra na plataforma, ele é apresentado à <b> tela inicial </b> .
(Tela 1) que possui as opções de <b> Login, Pesquisar, Menu, Newleaster </b> e nossas <b> redes sociais </b> além de um <b> "Fale conosco"</b> .

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

A imagem a seguir é um exemplo de fluxo do usuário (lar temporário).


![Flowchart (2)](https://user-images.githubusercontent.com/83349744/135725610-5cb215b9-e17b-49f3-a93a-8f659a3e716a.jpg)

Neste link poderá ver as telas e seguir os fluxos - https://xd.adobe.com/view/27ec903f-3ac1-4336-b7ef-4f33df1a608c-72bf/ -



## Wireframes

Conforme fluxo de telas do projeto, apresentado no item anterior, as telas do sistema são apresentadas em detalhes nos itens que se seguem. As telas do sistema apresentam uma estrutura comum que é apresentada na Figura X. Nesta estrutura, existem 3 grandes blocos, descritos a seguir. São eles:
Cabeçalho - local onde são dispostos o logo, login e navegação principal do site (menu da aplicação) e a barra de pesquisa;
Conteúdo - apresenta o conteúdo da tela em questão;
Rodapé - apresenta nossas redes sociais, fale conosco e opção de newleaster.

Tela - Tela Inicial ou Home-page
A tela de home-page mostra a imagem de um animal. Apresenta um componente de pesquisa que permite substituir o conteúdo da página com o resultado da busca solicitada pelo usuário;
Um menu pra que vá direto ao objetivo do usuário em questão;
Componente de Login para caso queira entrar em sua conta já registrada ou se registrar em nosso site.
O rodapé é padronizado, contendo nossas redes sociais, fale conosco e newleaster.

![TELA INICIAL](https://user-images.githubusercontent.com/83349744/135902314-0bb83376-9e61-4da8-aea0-4451e732c22c.png)


Tela - Login
A tela possui componentes que permitem que o usuário cadastre-se no site ou entre em uma conta já existente. Um campo de "Usuário" e "Senha" onde pressionando em "Entrar" fará Login em sua conta, um texto explicando o que nossa plataforma pode, em uma de suas funcionalidades, proporcional caso se cadastre seguido de um botão de "Cadastrar".

![LOGIN](https://user-images.githubusercontent.com/83349744/135903337-4eaf2079-b14f-4d6d-9d93-f07de299aed8.png)

Tela - Cadastro
A tela de Leitura de Notícia apresenta, no Bloco de Conteúdo, uma notícia específica. O Bloco de Barra Lateral apresenta os mesmos elementos da Home-Page. 


Figura X - Tela de Leitura de Notícia
Tela - Salvar Notícias Preferidas
A tela que permite o salvamento de notícias preferidas é uma janela modal (surge sobre outras janelas) quando o usuário pressiona o ícone coração na tela de Leitura de Notícia. Nesta tela, a notícia a ser salva é visualizada e o usuário pode informar um tópico ou escolher entre os já cadastrados. Em seguida deve confirmar ou cancelar o salvamento. Na sequência, a tela é fechada voltando para o ambiente anterior.


Figura X - Salvar notícias preferidas

Tela - Notícias Preferidas
A tela de Notícias Preferidas apresenta a relação de notícias salvas pelo usuário. Nesta tela, as notícias são separadas pelo Tópico informado pelo usuário. Os tópicos servem como uma identificação de agrupamento das notícias salvas. Ao clicar em uma notícia é disparada a tela de visualização de notícia. O Bloco de Barra Lateral apresenta os mesmos elementos da Home-Page. 


Figura X - Tela de Notícias Preferidas


Tela - Comentários
Na tela que permite ao usuário comentar uma notícia, deve-se informar o nome de quem está comentando e o texto do comentário. Esta tela é exibida na forma de uma janela modal. Em seguida, deve-se confirmar ou cancelar o salvamento do comentário. Na sequência, a tela é fechada voltando para o ambiente anterior.


Figura X - Tela de inclusão de comentários





 
> **Links Úteis**:
> - [Protótipos vs Wireframes](https://www.nngroup.com/videos/prototypes-vs-wireframes-ux-projects/)
> - [Ferramentas de Wireframes](https://rockcontent.com/blog/wireframes/)
> - [MarvelApp](https://marvelapp.com/developers/documentation/tutorials/)
> - [Figma](https://www.figma.com/)
> - [Adobe XD](https://www.adobe.com/br/products/xd.html#scroll)
> - [Axure](https://www.axure.com/edu) (Licença Educacional)
> - [InvisionApp](https://www.invisionapp.com/) (Licença Educacional)

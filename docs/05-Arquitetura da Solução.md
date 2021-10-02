# Arquitetura da Solução

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>

Definição de como o software é estruturado em termos dos componentes que fazem parte da solução e do ambiente de hospedagem da aplicação.

## Diagrama de componentes

Os componentes que fazem parte da solução são apresentados na Figura que se segue.

![My First Board (3)](https://user-images.githubusercontent.com/83349744/135545219-b9562b7a-7224-4cfc-b47d-d437e603d634.jpg)

<center>Figura 1 - Arquitetura da Solução</center>



A solução implementada deverá conter os seguintes módulos:
<ul>
  <li>Navegador</li>  Interface básica do sistema 
  <li>Páginas Web</li>  Conjunto de arquivos HTML, CSS, JavaScript e imagens que implementam as funcionalidades do sistema.
  <li>Local Storage</li>  Armazenamento mantido no Navegador, onde são implementados bancos de dados baseados em JSON. São eles: 
  <li>Hospedagem</li>  Local na Internet onde as páginas são mantidas e acessadas pelo navegador. 
  </ul>


Inclua um diagrama da solução e descreva os módulos e as tecnologias que fazem parte da solução. Discorra sobre o diagrama.

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
Escolhendo em nosso MENU (tela 8) a opção de <b>"Cadastrar animais"</b>, ele será enviado para nosso formulário para Cadastro de Animais (tela 11). Preenchendo as suas informações e do animal, poderá enviar para nossa plataforma.  **


<h3> CASO O USUÁRIO QUEIRA VIZUALIZAR NOSSA HISTÓRIA: </h3>
Entrando na plataforma vizualizará a tela inicial (tela 1). Clicando em Menu (tela 8) ele verá as opções. Optando por <b>"Nossa História"</b> a tela descrevendo a história de como a idéia da plataforma foi criada será gerada (tela 12).


<h3> CASO O USUÁRIO QUEIRA VER INFORMAÇÕES: </h3>

Entrando na plataforma vizualizará a tela inicial (tela 1). Clicando em Menu (tela 8) ele verá as opções. Optando por <b>"Informações"</b> ele será redirecionado a uma tela com informações a mais sobre o site (tela 13).

A imagem a seguir é um exemplo de fluxo do usuário (lar temporário).

![Exemplo de UserFlow](img/userflow.jpg)


## Tecnologias Utilizadas

Descreva aqui qual(is) tecnologias você vai usar para resolver o seu problema, ou seja, implementar a sua solução. Liste todas as tecnologias envolvidas, linguagens a serem utilizadas, serviços web, frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.

Apresente também uma figura explicando como as tecnologias estão relacionadas ou como uma interação do usuário com o sistema vai ser conduzida, por onde ela passa até retornar uma resposta ao usuário.


## Hospedagem 
O site utiliza a plataforma do Heroku como ambiente de hospedagem do site do projeto.*  
A publicação do site no Heroku é feita por meio de uma submissão do projeto* (push) via git para o repositório remoto que se encontra no endereço: 
https://git.heroku.com/link_exemplo.git

*O URL do site será definido futuramente, logo a hospedagem também.

> **Links Úteis**:
>
> - [Website com GitHub Pages](https://pages.github.com/)
> - [Programação colaborativa com Repl.it](https://repl.it/)
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Publicando Seu Site No Heroku](http://pythonclub.com.br/publicando-seu-hello-world-no-heroku.html)

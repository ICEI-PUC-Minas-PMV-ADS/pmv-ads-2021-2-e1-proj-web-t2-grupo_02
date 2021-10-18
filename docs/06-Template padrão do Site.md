# Template padrão do site

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>, <a href="4-Metodologia.md"> Metodologia</a>

Layout padrão do site (HTML e CSS) que será utilizado em todas as páginas com a definição de identidade visual, aspectos de responsividade e iconografia.

> **Links Úteis**:
>
> - [CSS Website Layout (W3Schools)](https://www.w3schools.com/css/css_website_layout.asp)
> - [Website Page Layouts](http://www.cellbiol.com/bioinformatics_web_development/chapter-3-your-first-web-page-learning-html-and-css/website-page-layouts/)
> - [Perfect Liquid Layout](https://matthewjamestaylor.com/perfect-liquid-layouts)
> - [How and Why Icons Improve Your Web Design](https://usabilla.com/blog/how-and-why-icons-improve-you-web-design/)


Código:
<!--HTML-->
<html>
    <head>
        <link rel="stylesheet" type="text/css" href="./main.css">
        <title>PetMatch </title>


   </head>
         <body>
                <div class="hero">
                    <div class="row"> 
                        <div class="col1">
                            <h1>Olá Maria!</h1>
                            <p> Cruzamos os seus dados e identificamos alguns animais que têm compatibilidade com o seu perfil.</p>
                        </div>
                        
                        <div class="col2">
                            <img src="./img/cat1.jpg">
                        </div>
                    </div>  
                </div>
           
            <footer> 
                <div>
                    <ul>
                        <li>kkk</li>
                        <li>kkk</li>
                        <li><kkk/li>
                        <li>kkk</li>
                    </ul>
                </div>
            </footer>
         </body>
</html>
  
  
  <!--CSS-->
  @import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro&display=swap')

*{
    margin: 0;
    padding: 0;
    font-family: 'Source Sans Pro', sans-serif;
}

body{
    margin:0;
    padding: 0;
    background: #fff;
    font-family: 'Source Sans Pro', sans-serif;
    box-sizing: border-box;
}


.hero {
    width: 100%;
    min-height: 100vh;
    text-align: left;
    background: #fff;
}

.row {
    display: flex;
    width: 100%;
    background: #0040FF;
    overflow: hidden;
}

.col1, .col2 {
    flex-basis:50%;
    overflow: hidden;
}

.col2 img{
    width: 100%;
}

#footer{
    width: 100%;

}

footer ul li {
    background-color:#FDAC1D ;
    color: white;
    text-align: left;
    font-size: 15px;
    padding: 0px;
    margin:0px;
    width: 100%;
}

footer a {
color: white;
text-decoration: none;
}

footer a:hover {
text-decoration: underline;
}

#FD4073; 
<!--COR ROSA  #FD4073; -->
  

# Cursos de introdução a programação HTML5 e CSS3
<ul>
<li><h3>Objetivos</h3></li>
<ul type="circle">
<li><p>Aprender a utilizar o HTML5;</p></li>
<li><p>Aprender a utilizar o CSS3;</p></li>
<li><p>Construir uma página com HTML5 e CSS3.</p></li>
</ul>
</ul>
<br>    
<ul>
<li><h3>Requisitos básicos<h3></li>
<ul type="circle">
<li><p>Windows, Linux ou OSX;</p></li>
<li><p>Editor de código fonte;</p></li>
<li><p>GitHub.</p></li>
</ul>
</ul>

# Ínicio
<ul>
<li><h3>Sobre o HTML5</h3></li>
<ul type="circle">
<li><p>HTML (Hypertext Markup Language) é uma linguagem de marcação utilizada para criação de páginas web;</p></li>
<li><p>HTML5 é o padrão mais novo;</p></li>
<li><p>No HTML5 foram introduzidos novos elementos que proporcionam suporte a maior interatividade com o usuário.</p></li>
</ul>
</ul>
<br>
<ul>    
<li><h3>Na prática</h3></li>
<ul type="circle">
<li><p>Instalei o editor de código fonte "<a href="https://code.visualstudio.com/" target="_blank">Microsoft Visual Studio Code"</a> para desenvolver minha primeira página.</p></li>
</ul>
</ul>
<br>
<ul>
<li><h3>Estrutura básica de página em HTML e principais tags para iniciar um projeto</h3></li>
<ul type="circle">
<li><p><strong>tags: </strong>As tags são usadas para informar ao navegador a estrutura do site. Ele interpreta e produz a estrutura e o conteúdo visual da página.<br><br>
A principal característica das tags é estarem sempre dentro dos sinais de chevron (sinal de "maior que" e "menor que"), ou seja> <>.<br><br>
Elas são divididas em dois tipos: As que precisam de fechamento e as que não precisam de fechamento. As tags que precisam de fechamento possuem a sintaxe < exemplo> < exemplo/>, já as que não precisam de fechamento possuem como estrutura < exemplo/>.</p>
<li><p><strong>Atributos: </strong>Uma mesma tag pode receber um ou mais atributos, que possuirá um valor que modifica sua estrutura ou funcionalidade.<br><br>
A aioria das tags tem seus próprios atributos. Contudo, existem alguns atributos genéricos que podem ser utilizados na maioria das tags HTML, vamos estudá-los:<br>
<b>class=”…“ – </b>Atribui uma classe ao elemento (uma classe pode ser utilizada para um ou mais elementos);<br>
<b>id=”…“ – </b>Atribui um id ao elemento (um id deve ser único, ou seja atribuído a um único elemento);<br>
<b>style=”…” – </b>Permite incluir elementos CSS (estilos) dentro da tag;<br>
<b>lang=”…” – </b>Define o idioma principal do elemento;<br>
<b>title=”…” – </b>Define o título do elemento;<br>
<b>alt=”…” – </b>Define um texto alternativo e, por isso, é muito utilizado em imagens, auxilia nas práticas de SEO;<br>
<b>hidden – </b>Oculta o elemento;<br>
<b>align=”…” – </b>Permite definir o padrão de alinhamento desse elemento, como por exemplo: right, center, left e justify;<br>
<b>width=”…” – </b>Define uma largura para o elemento;<br>
<b>height=”…” – </b>Define uma altura para o elemento.<br><br>
Esses são os principais atributos, porém existem diversos outros que devem ser estudados e podem ser utilizados no código.</p></li>
<li><p>Estrutura básica de uma página HTML<br><br>

    <!DOCTYPE html>
    <html lang="pt-br">

        <head>
            <meta charset="utf-8">
            <title>Título da página</title>
        </head>

        <body>
        <!-- Comentário: Conteúdo da página -->
            <header>
                <h1>Título</h1>
                <p>parágrafo</p>
            </header>

            <footer>
                <p>Rodapé</p>
            </footer>
        </body>
    </html>
</p></li>
</ul>
</ul>
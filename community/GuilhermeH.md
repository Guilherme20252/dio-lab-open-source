<!DOCTYPE html>

<html>

    <head>
        <title>Quiz para programadores</title>
        <meta name="description" content="Um quiz interativo para testar seus conhecimentos">
        <link rel="stylesheet" href="style.css">
    </head>

    <Body>
    <header>
      <h1>Quiz interativo para programadores</h1>
      <p>Teste seus conhecimentos em programação e veja sua pontuação!</p>  

    </header>
    <main>
        <!--introdução-->
    <section>
        <h2>Sobre este quiz</h2>
        <p><strong>Este quiz</strong> foi desenvolvido para testar seus conhecimentos em programação, como linguagens de programação, conceitos básicos e mais</p>
        <p>Você encontrará diferentes tipos de perguntas, incluindo múltipla escolhas, textos e perguntas de datas. Desafie-se com esse quiz!</p>
        <p>Você poderá encontar alguns acrônimos como <abbr title="HiperText Markup Language"> HTML </abbr> e <abbr title="Cascading Style Sheets"> CSS </abbr>, que são comumente usados em questões relacionada ao desenvolvimento web.</p>
    </section>
    <!--pergunta 1: múltipla escolha-->
    <section>
<h2>Pergunta 1: Qual linguagem é usada para estruturar páginas web?</h2>

<form>
<input type="radio" value="python" id="p1a" name="pergunta1">
<label for="p1a">Python</label> <br>

<input type="radio" value="HTML" id="p1b" name="pergunta1">
<label for="p1b">HTML</label> <br>

<input type="radio" value="Javascript" id="p1c" name="pergunta1">
<label for="p1c">Javascript</label> <br>

<input type="radio" value="Ruby" id="p1d" name="pergunta1">
<label for="p1d">Ruby</label> <br>

</form>

    </section>

    <!--pergunta 2: texto-->
    <section>
        <h2>Pergunta 2: Na URL https://www.google.com o trecho "google.com" é o _____</h2>

    <form>
        <input type="text" id="p2" name="pergunta2" placeholder="digite sua resposta...">
    </form>

    </section>

    <!--pergunta 3: senha-->
    <section>
    <h2>Pergunta 3: Escreva um exemplo de senha forte</h2>

    <form>
<input type="password" id="p3" name= "pergunta 3" placeholder= "digite uma senha...">

    </form>

    </section>

    <!--pergunta 4: data-->
    <section>
    <h2>Pergunta 4: Em que ano o HTML lançou a sua primeira versão?</h2>

    <form>
<input type="date" id="p4" name="pergunta 4">

    </form>


    </section>

    <!--pergunta 5: seleção múltipla-->
    <section>
<h2>Pergunta 5: Quais dessas tecnologias são consideradas linguagens de programação?</h2>
    <form>
    <input type="checkbox" id="p5a" name="pergunta5" value="Javascript">
    <label for="p5a">Javascript</label>

    <input type="checkbox" id="p5b" name="pergunta5" value="HTML">
    <label for="p5b">HTML</label>

    <input type="checkbox" id="p5c" name="pergunta5" value="Java">
    <label for="p5c">Java</label>

    <input type="checkbox" id="p5d" name="pergunta5" value="CSS">
    <label for="p5c">CSS</label>
    </form>


    </section>

    <!--pergunta 6: upload de arquivo-->
    <section>
    <h2>Pergunta 6: Faça um upload de um arquivo contendo código HTML</h2>
    <form>
<input type="file" id="p6" name="pergunta 6">


    </form>


    </section>

    <!--pergunta 7: menu suspenso-->
    <section>
<h2>Pergunta 7: Selecione o atributo do input que define o seu tipo: </h2>
    <form>
<select name="p7" id="pergunta 7">
    <option value="id">id</option>
    <option value="type">type</option>
    <option value="placeholder">placeholder</option>

</select>

    </form>

    </section>

    <!--pergunta 8: imagem -->
    <section>
<h2>Pergunta 8: Qual linguagem de programação é representada pelo logotipo abaixo:</h2>
<figure>
    <img src="226777.png" alt="Logotipo de uma linguagem de programação"><br>
    <figcaption>Figura 1: imagem de um logotipo de uma linguagem de programação</figcaption>
    <input type="text" id="p8" name="pergunta 8" placeholder="Digite a sua resposta...">

</figure>
    </section>

    <!--tabela de pontuação-->
    <section>
<h2>Tabela de pontuação</h2>
    <table border="1">
    <thead>

<tr>
<th>Pontuação</th>
<th>Avaliação</th>

</tr>

    </thead>
    <tbody>
    

    <tr>
        <td>0 - 2</td>
        <td> Não foi dessa vez! </td>
        
    </tr>

    <tr>
        <td>3 - 4</td>
        <td> pratique mais! </td>
        
    </tr>

    <tr>
        <td>4 - 5</td>
        <td> Boa! </td>
        
    </tr>

    <tr>
        <td>5 - 7</td>
        <td> mandou bem! </td>
        
    </tr>

    <tr>
        <td>8</td>
        <td> parabéns, você é o melhor! </td>
        
    </tr>

</tbody>
<tfoot>
<tr>
<td colspan="2">Boa sorte!!!</td>


</tr>

</tfoot>
    </table>


    </section>

    <!--lista-->

    <section>

        <h2>Verifique suas respostas</h2>
        <details>
            <summary>Clique aqui para conferir as respostas corretas</summary>
        <ol>

    <li>HTML</li>
    <li>Domínio</li>
    <li>ABC123abc..</li>
    <li>1991</li>
    <li>JavaScript, Java</li>
    <li>Arquivo deve conter extensão .html</li>
    <li>Type</li>
    <li>Java</li>

        </ol>
        </details>

    </section>

    </main>
    <footer></footer>

    </Body>

</html>

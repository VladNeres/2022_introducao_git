<h1> Introdução ao Git e codigod utilizados diariamente.</h1>

       <h1>Como Configurar login e email do  Git ?<h1>

        <strong> login: </strong> $ git config --global user.name "Fulano de Tal" 
        <strong> Email: </strong> $ git config --global user.email fulanodetal@exemplo.br 



        <h2> 2°Comandos para inciar o git e comandos iniciais </h2>

        para iniciar o git , crie uma pasta onde voce irá deixar seu arquivo, documento de texto ou programa, dentro da pasta abra o Git Bash e digite 
             <ul>
                <li> 1- git init                             <- esse comando iniciará o git no seu projeto. </li>
                <li> 2- git branch -m main                   <- comando que altera da branch master para main. </li>
                <li> 3- git status -s                        <- esse comando mostra os arquivos que foram adicionados, modificados ou escluidos do seu projeto. </li>
                <li> 4- git add nomeDoArquivo                <- esse comando é responsável por colocar o seu arquivo no modo "tracked". </li>
                <li>4.1- git add .                          <-esse comando  faz a adicão de todos os arquivos que foram modificados ou inseridos. </li>
                <li>5- git commit -m "Mensagem desejada"    <- esse comando é responsavel por "Salvar" as suas modificaçoes, mas para realmente salva-las envie para o seu repositorio remoto. </li>
                <li>6- git push origin  main <- NomeDaBranch <- esse comando envia seus arquivos e modificações para seu repositorio remoto. </li>
               </ul>



<h2> 3° REMOÇÂO STAGIN AREA </h2>
 
 <ol>
 <li>  git reset Head NomeDoArquivo        <- esse comando remove o aquivo remove o arquivo que voce colocou o nome da staging area </li>
 <li>  git reset Head                   <- esse comando remove todos os arquivos que estão na staging area </li> 
</ol>

        <h2> 4° COMO Iniciar e clonar um Repositorio Remoto </h2>

        1- Va no GitHub, na pagina inicial clique em Repositorios.
        2- Clique em (New) botãozinho verde localizado a direita.
        3-Coloque o nome do seu repositorio e la em baixo na ultima linha clique em criar repositório.
        3.1- Na pasta que abriu copie o link do HTTP.
        4- Va no explorador de arquivos do seu computador (onde fica as pastinhas e documentos).
        5- abra o Git Bash
        6- digite o comando git clone e cole o link que voce copiou.
        7- Agora voce pode colocar seus arquivos dentro dessa pasta que voce acabou de clonar.
        8- siga os passos da 2° seção -> (Comandos para inciar o git e comandos iniciais).


<div class="5° Como linkar um arquivo local ao remoto">
        <h2> 5° Como linkar um arquivo local ao remoto </h2>
    1- Siga os passos do item 4°(COMO Iniciar e clonar um Repositorio Remoto)

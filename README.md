<h1> Introdução ao Git e codigod utilizados diariamente.</h1>

<div class="email">
<h2> Como Configurar login e email do  Git ? </h2>
<strong> login: </strong> $ git config --global user.name "Fulano de Tal" <br>
<strong> Email: </strong> $ git config --global user.email fulanodetal@exemplo.br 
</div>

<div class="Comandos-Iniciais">
 <h2> 2°Comandos para inciar o git e comandos iniciais </h2>
 para iniciar o git , crie uma pasta onde voce irá deixar seu arquivo, documento de texto ou programa, dentro da pasta abra o Git Bash e digite 
 <ol>
    <li>  <strong>git init   </strong>                         <i> -> esse comando iniciará o git no seu projeto.</i> </li>
    <li>  <strong>git branch -m main </strong>                 <i> -> comando que altera da branch master para main.</i> </li>
    <li>  <strong>git status -s </strong>              <i>-> esse comando mostra os arquivos que foram adicionados, modificados ou escluidos do seu projeto.</i> </li>
    <li>  <strong>git add nomeDoArquivo </strong>              <i> -> esse comando é responsável por colocar o seu arquivo no modo "tracked".</i> </li>
    <li> <strong>git add . </strong>                           <i>->esse comando  faz a adicão de todos os arquivos que foram modificados ou inseridos.</i> </li>
    <li> <strong>git commit -m "Mensagem desejada"</strong>    <i>-> esse comando é responsavel por "Salvar" as suas modificaçoes, mas para realmente salva-las envie       para o seu repositorio remoto.</i> </li>
   <li> <strong>git push origin  main (NomeDaBranch)</strong> -><i> esse comando envia seus arquivos e modificações para seu repositorio remoto.</i> </li>
 </ol>
    </div>


<h2> 3° REMOÇÂO STAGIN AREA </h2>
 
 <ol>
 <li>  git reset Head NomeDoArquivo        <- esse comando remove o aquivo remove o arquivo que voce colocou o nome da staging area </li>
 <li>  git reset Head                   <- esse comando remove todos os arquivos que estão na staging area </li> 
</ol>

<div class="clonar-um-Repositorio-Remoto">
  <h2> 4° COMO Iniciar e clonar um Repositorio Remoto </h2>

   Va no GitHub, na pagina inicial clique em Repositorios.
   <ol>
    <li>Clique em (New) botãozinho verde localizado a direita.</li>
    <li>Coloque o nome do seu repositorio e la em baixo na ultima linha clique em criar repositório.</li>
    <li>Na pasta que abriu copie o link do HTTP.</li>
    <li>Va no explorador de arquivos do seu computador (onde fica as pastinhas e documentos).</li>
    <li>abra o Git Bash</li>
    <li>digite o comando git clone e cole o link que voce copiou.</li>
    <li>Agora voce pode colocar seus arquivos dentro dessa pasta que voce acabou de clonar. </li>
    <li>siga os passos da <a href="Comandos-Iniciais">2° seção <a/> -> (Comandos para inciar o git e comandos iniciais).</li>
  </ol>
</div>

<div class="5° Como linkar um arquivo local ao remoto">
        <h2> 5° Como linkar um arquivo local ao remoto </h2>
  <ol>  
    <li>Siga os passos do <a href="clonar-um-Repositorio-Remoto"> item 4° </a> até o passo 3 (COMO Iniciar e clonar um Repositorio Remoto).</li>
    <li>Abra a pasta do seu arquivo local e dentro da pasta abra o git bash.</li>
    <li>Digite o comando <strong> $ git remote add origin ColeOLink.</strong>.   
  </ol>
</div>
  
  <h2> Como remover o Link remoto </h2>
  <ol>
    <li> Va na sua pasta local onde voce deixou o arquivo que esta linkado com o repositório remoto</li>
  <li> digite o comando: <strong> git remote -v </strong> -> esse comando irá possibilitar voce verificar o link do seu repositorio remoto.</li>
  <li> git remote rm linkDoRepositorio -> esse comando remove o vinculo do repositorio Local com o repositorio remoto. </li>

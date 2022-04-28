<!DOCTYPE html>

<html lang="pt-BR">
<head>
<title>C.E.S.P.E.R</title>

<meta name="keywords" content="persianas, cortinas, envidraçamento, sacada">
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<!-- CSS only -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
<!-- JavaScript Bundle with Popper -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

<link rel="stylesheet" href="estilo.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

</head>
  <head>
  <link rel="stylesheet" href="caixa1.css">
  <title>Contato</title>
  <link rel="stylesheet" type="text/css" href="fundo.css">
  </head>

  <div class="container mt-3"> <!--vai de 1 a 5-->
   <ul class="nav justify-content-center">
   <li class="nav-item">
   <a class="nav-link" href="index.html"><i class="fa fa-home w3-large"></i> Home</a>
   </li>

   <li class="nav-item">
   <a class="nav-link" href="empresa.html">Empresa</a>
   </li>

   <li class="nav-item dropdown">
   <a class="nav-link"  data-bs-toggle ="dropdown" href="produtos.html">Produtos</a>
   </li>

   <li class="nav-item dropdown">
   <a class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="serviços.html">Serviços</a>
   <ul class="dropdown-menu">
   <li><a class="dropdown-item" href="#">Envidraçamento de Sacadas</a></li>
   </ul>
   </li>

   <li class="nav-item">
   <a class="nav-link" href="contato.html">Contato</a>
   </li>
   </ul>
   </div>
   <body>
   </br>
   </br>
   </br> 

   <center>
   <div class="caixa2">
   <link rel="stylesheet" href="caixa2.css">
   <h2 style="color:black">Entre em contato com a gente</h2>
   </center>

   <div>
   <link rel="stylesheet" href="caixa3.css"> 
   <div class="caixa3">
   <center>
   <legend>Deixe aqui seus dados para que possamos entar em contato e oferecer o melhor orçamento.</legend>
   </center> 
   <legend>Dados Pessoais</legend>
   <label for="nome">Seu nome:</label>
   <br/>
   <input id="nome" type="text">
   <br/>

   <label for="email">E-mail:</label>
   <br/>
   <input id="email" type="email">
   <br/>
   <br/>
                    
   <legend>Dados do Produto</legend>
   <label>Que Produto/Serviço está buscando?</label>
   <br/>
   <input list="produtos">
   <datalist id="produtos">
   <option value="Persianas">
   <option value="Cortinas">
   <option value="Envidraçamento">
   <option value="Outro">
   </datalist>
   <br/>
   <label for="mensagem">Mensagem:</label><br/>
   <textarea id="mensagem" rows="5" cols="80"></textarea>
   <br/>
   <button type="reset">Limpar Formulário</button>
   <input id="botao" type="submit" value="Enviar">
   </form>
   </div>
   </div>
   </body>
</html>

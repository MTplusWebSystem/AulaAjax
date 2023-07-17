# AulaAjax
Primeiro criamos nossos arquivos são eles:
```
index.html
dados.json
```
<hr>
Logo após abrirmos nosso index.html e adicionamos a teg html:

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>
<body>
  
</body>
</html> 
```
## Importação Jquery🛰

Dentro da nossa teg `head` adicione:
```html 
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
```
E logo a baixo do nosso `Body` abrimos e  fechamos a teg ``` <script> ``` o código deve ficar assim:
```html 
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>


</head>
<body>

</body>

<script>

</script>

</html>
```

# Dados 🎲 JSON 

Agora vamos adicionar um item ao nosso arquivo `dados.json` abra o arquivo faça um código que se assimila com o meu:
```json
{
  "text":"Bem-vindo a arte de codar "
}
```
# criando div de apresentação e estilo
<br>

### DIV

<img src="https://i.imgur.com/1ptEeU5.png" height='250'>
<br>

### ESTILO

<img src="https://i.imgur.com/IqWOJ3R.png" height='250'>

<br>
Código final tem que ficar assim ou similar:
```html 
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
</head>

<style>
  
  #conteudo{
    margin: 50px;
  }
  #dados{
    margin-top:20px;
    border: 2px solid #ccc;
    padding: 10px;
  }
  
</style>

<body>

<div id="conteudo">
  <h2>AJAX tutorial</h2>
  <button id="btn-carregar">Carregar dados</button>
  <div id="dados"></div>
</div>

</body>
</html>
```

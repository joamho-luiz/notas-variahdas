# HTML

```html
<tag></tag>

<tag/>

<!-- comentário -->



* *  CSS  * *

    <link real href="#">

    <style></style> (em head)

    <div style=""></div>



* *  JS  * *

    <script src="#"></script>

    <script></script>

    <div onmouseover="chamar()"></div>



<a href="#" target="_blank"></a>

<iframe src="#"></iframe>
```

# JAVA SCRIPT

```js
// comentário

* *  SAÍDA * * 

    alert('')

    document.write('')


* *  ENTRADA * *

    confirm('') // retorna um boolean.

    prompt('') // retorna texto.


* *  MANIPULAÇÃO * *

    document.querySelector('tag#id')

    document.getElementBytagName('taguinha')


* *  CRIAÇÃO * * 

    var foto = document.createElement('img')
```

# PHP

```php
# comentário

<?php         ?>

$n + ... = 2;

if(){}elseif(){}

include nome-do-arquivo.php;
```
```html
* *  HTML  * *

    <form action="nome-do-arquivo.php" method="get">
```
```php
* *  PHP  * *

    $variahvel = $_GET["name"];

    $var = $_GET["name"]??"valor-padrão";

    $ano = isSet($_GET["name"]?$_GET["name"]:"0";
```
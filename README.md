<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Hello world!</title>

    <button id="button_one" onclick="change_text()">click here to change the text</button>
      <p id = "testparagraph">Glamrock Freddy est l'animatronique le plus sûr en cas de violation de la sécurité, il peut garder Gregory à l'abri des autres animatroniques dans sa cavité thoracique. il vous donnera également la montre faz qui s'obtient au début </p>

  </head>
  <body>

    <script> 
          var paragraph = document.getElementById("testparagraph");
            
            function change_text() {

          paragraph.innerHTML = "le pire animatronique du jeu est probablement monty car il est immunisé contre la faz cam au début mais après que gregory l'ait détruit il n'y est plus immunisé par la suite. au début, il est également immunisé contre le faz blaster";

            }
    </script>
  </body>
</html>

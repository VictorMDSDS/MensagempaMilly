<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Love Message</title>
</head>
<body>

<!-- Button that triggers the love message -->
<button onclick="showLoveMessage()">Clique aqui</button>

<!-- Element to display the love message -->
<p id="loveMessage" style="display:none; color:red; font-size:20px; font-weight:bold;">Eu te AMO!</p>

<!-- JavaScript to show the love message -->
<script>
  function showLoveMessage() {
    // Select the element by ID
    var loveMessageElement = document.getElementById("loveMessage");

    // Display the love message
    loveMessageElement.style.display = "block";
  }
</script>

</body>
</html>


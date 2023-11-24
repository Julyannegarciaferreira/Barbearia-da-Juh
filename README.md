# Barbearia

<!DOCTYPE html>
<html>
<head>
  <title>Contato</title>
  <style>
    body {
      font-family: Arial, sans-serif;
    }
    
    h1 {
      color: #333;
    }
    
    p {
      color: #666;
    }
    
    form {
      margin-bottom: 20px;
    }
    
    label {
      display: block;
      margin-bottom: 5px;
    }
    
    input[type="text"],
    input[type="email"],
    textarea {
      width: 300px;
      padding: 5px;
      margin-bottom: 10px;
    }
    
    input[type="submit"] {
      background-color: #333;
      color: #fff;
      padding: 10px 20px;
      border: none;
      cursor: pointer;
    }
    
    input[type="submit"]:hover {
      background-color: #555;
    }
  </style>
</head>
<body>
  <h1>Entre em Contato</h1>
  
  <form action="enviar.php" method="POST">
    <label for="nome">Nome:</label>
    <input type="text" id="nome" name="nome" required><br>
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required><br>
    
    <label for="mensagem">Mensagem:</label>
    <textarea id="mensagem" name="mensagem" required></textarea><br>
    
    <input type="submit" value="Enviar">
  </form>
</body>
</html>

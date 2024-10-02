[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&width=435&lines=ola+bem+vindo+ao+meu+github)](https://git.io/typing-svg)}

<!-- index.html -->

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Minhas Habilidades</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="skills-circle">
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
      <li>Python</li>
      <!-- Adicione suas habilidades aqui -->
    </ul>
  </div>
</body>
</html>

/* styles.css */

.skills-circle {
  width: 300px;
  height: 300px;
  border-radius: 50%;
  background-color: #f0f0f0;
  padding: 20px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.skills-circle ul {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.skills-circle li {
  margin: 10px;
  font-size: 18px;
  font-weight: bold;
  color: #333;
}

.skills-circle li::before {
  content: "•";
  font-size: 24px;
  color: #666;
  margin-right: 10px;
}

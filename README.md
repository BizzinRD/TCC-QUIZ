TEMA
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Escolha sua página</title>
  <link rel="stylesheet" href="tema.css" />
</head>
<body>

  <script src="tema.js"></script>
</body>
</html>

<div class="container">
  <h1>Escolha uma opção:</h1>
  <button onclick="navigateTo('futebol.html')">Esporte</button>
  <button onclick="navigateTo('TI.html')">Tecnologia</button>
  <button onclick="navigateTo('politica.html')">Política</button>
  <button onclick="navigateTo('geografia.html')">Geografia</button>
</div>

FUTEBOL
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Quiz Verdadeiro ou Falso</title>
  <link rel="stylesheet" href="futebol.css" />
</head>
<body>
  <div class="quiz-container">
    <h1>Quiz Verdadeiro ou Falso</h1>
    <img id="question-image" class="question-image" src="" alt="Imagem da pergunta" />
    <div id="question" class="question">Carregando pergunta...</div>
    <div class="buttons">
      <button id="true-btn" class="answer-btn">Verdade</button>
      <button id="false-btn" class="answer-btn">Falso</button>
    </div>
    <div id="feedback" class="feedback"></div>
    <div id="score" class="score"></div>

    <!-- Seção de Recordes adicionada aqui -->
    <div class="high-score-section">
      <h2>Recordes</h2>
      <ul id="high-scores">
        <!-- O JavaScript irá inserir os itens da lista aqui -->
      </ul>    
      <button id="clear-records-btn" class="answer-btn">Limpar</button>
    </div>
  </div>
  </div>

  <script src="futebol.js"></script>
</body>
</html>

GEOGRAFIA
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Quiz Verdadeiro ou Falso</title>
  <link rel="stylesheet" href="geografia.css" />
</head>
<body>
  <div class="quiz-container">
    <h1>Quiz Verdadeiro ou Falso</h1>
    <img id="question-image" class="question-image" src="" alt="Imagem da pergunta" />
    <div id="question" class="question">Carregando pergunta...</div>
    <div class="buttons">
      <button id="true-btn" class="answer-btn">Verdade</button>
      <button id="false-btn" class="answer-btn">Falso</button>
    </div>
    <div id="feedback" class="feedback"></div>
    <div id="score" class="score"></div>

    <!-- Seção de Recordes adicionada aqui -->
    <div class="high-score-section">
      <h2>Recordes</h2>
      <ul id="high-scores">
        <!-- O JavaScript irá inserir os itens da lista aqui -->
      </ul>
      <button id="clear-records-btn" class="answer-btn">Limpar</button>
    </div>
  </div>
  </div>

  <script src="geografia.js"></script>
</body>
</html>

POLITICA
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Quiz Verdadeiro ou Falso</title>
  <link rel="stylesheet" href="politica.css" />
</head>
<body>
  <div class="quiz-container">
    <h1>Quiz Verdadeiro ou Falso</h1>
    <img id="question-image" class="question-image" src="" alt="Imagem da pergunta" />
    <div id="question" class="question">Carregando pergunta...</div>
    <div class="buttons">
      <button id="true-btn" class="answer-btn">Verdade</button>
      <button id="false-btn" class="answer-btn">Falso</button>
    </div>
    <div id="feedback" class="feedback"></div>
    <div id="score" class="score"></div>
    
    <!-- Seção de Recordes adicionada aqui -->
    <div class="high-score-section">
      <h2>Recordes</h2>
      <ul id="high-scores">
        <!-- O JavaScript irá inserir os itens da lista aqui -->
      </ul>
      <button id="clear-records-btn" class="answer-btn">Limpar</button>
    </div>
  </div>

  <script src="politica.js"></script>
</body>
</html>

TI
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Quiz Verdadeiro ou Falso</title>
  <link rel="stylesheet" href="TI.css" />
</head>
<body>
  <div class="quiz-container">
    <h1>Quiz Verdadeiro ou Falso</h1>
    <img id="question-image" class="question-image" src="" alt="Imagem da pergunta" />
    <div id="question" class="question">Carregando pergunta...</div>
    <div class="buttons">
      <button id="true-btn" class="answer-btn">Verdade</button>
      <button id="false-btn" class="answer-btn">Falso</button>
    </div>
    <div id="feedback" class="feedback"></div>
    <div id="score" class="score"></div>

    <!-- Seção de Recordes adicionada aqui -->
    <div class="high-score-section">
      <h2>Recordes</h2>
      <ul id="high-scores">
        <!-- O JavaScript irá inserir os itens da lista aqui -->
      </ul>
      <button id="clear-records-btn" class="answer-btn">Limpar</button>
    </div>
  </div>
  </div>

  <script src="TI.js"></script>
</body>
</html>


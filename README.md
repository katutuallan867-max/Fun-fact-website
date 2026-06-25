<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>#MyFirstWebsite</title>
  <style>
    body { font-family: Arial, sans-serif; text-align: center; margin: 0; padding: 0; }
    header { background: #2c3e50; color: white; padding: 20px; }
    button { padding: 10px 20px; margin-top: 20px; cursor: pointer; }
    section { padding: 40px; }
    footer { background: #2c3e50; color: white; padding: 10px; }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to My First Website</h1>
    <p>Built for the Goodwall Challenge 🚀</p>
  </header>

  <section>
    <h2>Random Fun Fact</h2>
    <p id="fact">Click the button to see a fact!</p>
    <button onclick="showFact()">Show Fact</button>
  </section>

  <section>
    <h2>About Me</h2>
    <p>I’m learning to code and this is my first project using GitHub Copilot.</p>
  </section>

  <footer>
    <p>Connect with me on Goodwall!</p>
  </footer>

  <script>
    const facts = [
      "Honey never spoils.",
      "Bananas are berries, but strawberries aren’t.",
      "Octopuses have three hearts.",
      "Sharks existed before trees."
    ];
    function showFact() {
      const randomIndex = Math.floor(Math.random() * facts.length);
      document.getElementById("fact").innerText = facts[randomIndex];
    }
  </script>
</body>
</html>


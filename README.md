<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portfolio Achmad Aldino</title>
<style>
  body {
    font-family: 'Segoe UI', sans-serif;
    background: #f0f2f5;
    color: #333;
    margin: 0;
    padding: 0;
    text-align: center;
  }

  header {
    padding: 50px 20px;
    background: linear-gradient(135deg, #6a11cb, #2575fc);
    color: white;
  }

  h1 {
    font-size: 2.5rem;
    margin: 0;
    animation: fadeInDown 1s ease forwards;
  }

  p {
    font-size: 1.2rem;
    margin: 10px 0 0;
    animation: fadeIn 1.5s ease forwards;
  }

  .skills {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin: 40px 20px;
    gap: 20px;
  }

  .skill-card {
    background: white;
    padding: 20px;
    border-radius: 15px;
    width: 150px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    transition: transform 0.3s;
    cursor: pointer;
  }

  .skill-card:hover {
    transform: translateY(-10px) scale(1.05);
  }

  @keyframes fadeInDown {
    0% { opacity: 0; transform: translateY(-20px);}
    100% { opacity: 1; transform: translateY(0);}
  }

  @keyframes fadeIn {
    0% { opacity: 0;}
    100% { opacity: 1;}
  }

  footer {
    padding: 20px;
    font-size: 0.9rem;
    color: #555;
  }

  button {
    margin-top: 20px;
    padding: 10px 20px;
    border: none;
    background: #6a11cb;
    color: white;
    border-radius: 10px;
    cursor: pointer;
    font-size: 1rem;
    transition: background 0.3s;
  }

  button:hover {
    background: #2575fc;
  }
</style>
</head>
<body>

<header>
  <h1>Hi, I'm Achmad Aldino 👋</h1>
  <p>Programmer & Creative Technologist</p>
  <button onclick="showAlert()">Klik saya!</button>
</header>

<section class="skills">
  <div class="skill-card">💻 AI Prompter</div>
  <div class="skill-card">🎨 Adobe Animate</div>
  <div class="skill-card">🎨 Figma / UI/UX</div>
  <div class="skill-card">🖌️ Canva</div>
  <div class="skill-card">🌐 Website dengan AI</div>
</section>

<footer>
  📫 Hubungi saya: <a href="mailto:your-email@example.com">your-email@example.com</a>
</footer>

<script>
  function showAlert() {
    alert("Terima kasih sudah mengunjungi portofolio saya! 🌟");
  }
</script>

</body>
</html>

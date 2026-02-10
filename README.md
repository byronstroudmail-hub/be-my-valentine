<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Our Valentine 💖</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
body {
  margin: 0;
  height: 100vh;
  background: linear-gradient(135deg, #ff758c, #ff7eb3);
  font-family: Arial, sans-serif;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
}

.card {
  background: rgba(255,255,255,0.15);
  padding: 35px;
  border-radius: 20px;
  max-width: 420px;
  width: 90%;
  text-align: center;
  box-shadow: 0 15px 30px rgba(0,0,0,0.2);
}

button {
  padding: 12px 26px;
  margin: 10px;
  font-size: 1rem;
  border: none;
  border-radius: 30px;
  cursor: pointer;
  transition: transform 0.2s;
}

button:hover {
  transform: scale(1.1);
}

.primary {
  background: #ff2e63;
  color: white;
}

.secondary {
  background: white;
  color: #ff2e63;
}

.hidden {
  display: none;
}

img {
  width: 100%;
  border-radius: 15px;
  margin-top: 15px;
}

.gallery img {
  width: 100%;
  border-radius: 15px;
  margin-bottom: 12px;
}
</style>
</head>

<body>

<!-- INTRO PAGE -->
<div class="card" id="intro">
  <h1>Hey Beautiful 💕</h1>
  <p>
    Before anything else,<br>
    I just want you to know…<br><br>
    You make my world brighter ❤️
  </p>
  <button class="primary" onclick="showQuestion()">Next ➡️</button>
</div>

<!-- QUESTION PAGE -->
<div class="card hidden" id="question">
  <h1>Will you be our Valentine? 💘</h1>
  <p>From me and the kids ❤️</p>
  <img src="family.jpg" alt="Me and my kids">

  <button class="primary" onclick="goMenu()">Yes 💖</button>
  <button class="secondar

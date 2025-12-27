<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Arabic Vocabulary Flashcards</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f6f8;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }
    .card {
      background: white;
      width: 360px;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.1);
      text-align: center;
    }
    h2 {
      font-size: 26px;
      margin-bottom: 15px;
    }
    .options button {
      width: 100%;
      margin: 6px 0;
      padding: 10px;
      border: none;
      border-radius: 8px;
      background: #e9ecef;
      cursor: pointer;
      font-size: 16px;
    }
    .options button:hover {
      background: #d0d7de;
    }
    .correct {
      background: #28a745 !important;
      color: white;
    }
    .wrong {
      background: #dc3545 !important;
      color: white;
    }
    .next {
      margin-top: 15px;
      padding: 10px;
      width: 100%;
      background: #007bff;
      color: white;
      border: none;
      border-radius: 8px;
      font-size: 16px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div class="card">
    <h2 id="word"></h2>
    <div class="options" id="options"></div>
    <button class="next" onclick="nextCard()">Next</button>
  </div>  <script>
    const cards = [
      { word: "وَالذَّارِيَاتِ", correct: "The winds", options: ["The winds", "The angels", "The ships", "The clouds"] },
      { word: "ذَرْوًا", correct: "Scattering dust", options: ["Heavy rain", "Scattering dust", "Easy movement", "A true promise"] },
      { word: "فَالْحَامِلَاتِ", correct: "The clouds", options: ["The ships", "The angels", "The clouds", "The winds"] },
      { word: "وِقْرًا", correct: "Heavy load of water", options: ["Light rain", "Heavy load of water", "Smooth sailing", "Adornment"] },
      { word: "فَالْجَارِيَاتِ", correct: "The ships", options: ["The winds", "The clouds", "The ships", "The angels"] },
      { word: "يُسْرًا", correct: "Moving easily", options: ["Moving easily", "With difficulty", "A promise", "Punishment"] },
      { word: "فَالْمُقَسِّمَاتِ", correct: "The angels", options: ["The winds", "The angels", "The ships", "The clouds"] },
      { word: "تُوعَدُونَ", correct: "What you are promised", options: ["What you deny", "What you are promised", "What you see", "What you forget"] },
      { word: "لَوَاقِعٌ", correct: "Certain and inevitable", options: ["Unlikely", "Hidden", "Certain and inevitable", "Temporary"] },
      { word: "ذَاتِ الْحُبُكِ", correct: "Beautifully ordered", options: ["Destroyed", "Beautifully ordered", "Empty", "Dark"] }
    ];

    let index = 0;

   

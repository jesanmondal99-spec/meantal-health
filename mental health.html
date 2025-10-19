<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Mental Health Survey</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
         background-color:orange;
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      color: #fff;
    }

    .overlay {
      background-color: rgba(0, 0, 0, 0.7);
      padding: 30px;
      max-width: 700px;
      margin: 50px auto;
      border-radius: 10px;
    }

    h2, label {
      color: #fff;
    }

    select, button {
      width: 100%;
      padding: 8px;
      margin-top: 5px;
      margin-bottom: 15px;
      border-radius: 5px;
      border: none;
    }

    .question {
      margin-bottom: 10px;
    }

    .result {
      margin-top: 20px;
      padding: 15px;
      background-color: rgba(255, 255, 255, 0.9);
      color: #000;
      border-radius: 10px;
    }

    .hidden {
      display: none;
    }
  </style>
</head>
<body>

<div class="overlay">
  <h2>Mental Health Survey</h2>

  <label>Select your category:</label>
  <select id="category" onchange="loadQuestions()">
    <option value="">--Choose--</option>
    <option value="adult">Adult</option>
    <option value="student">Student</option>
  </select>

  <div id="survey" class="hidden">
    <form id="surveyForm">
      <div id="questions"></div>
      <button type="button" onclick="calculateScore()">Submit</button>
    </form>
  </div>

  <div id="result" class="result hidden"></div>
</div>

<script>
const questions = {
  adult: [
    "How often do you feel overwhelmed by responsibilities?",
    "Do you struggle to find joy in daily activities?",
    "Are you sleeping well and waking up refreshed?",
    "Do you feel emotionally supported by friends or family?",
    "Have you experienced frequent mood swings?",
    "Do you feel anxious about your future?",
    "Are you able to concentrate on tasks?",
    "Do you feel physically exhausted without reason?",
    "Have you lost interest in hobbies or socializing?",
    "Do you feel confident in your decisions?",
    "Are you coping well with work-related stress?",
    "Do you feel isolated or lonely?",
    "Have you had thoughts of self-harm or hopelessness?",
    "Do you feel safe and secure in your environment?",
    "Are you able to manage your emotions effectively?"
  ],
  student: [
    "Do you feel stressed about academic performance?",
    "Are you able to balance school and personal life?",
    "Do you feel supported by teachers or peers?",
    "Are you sleeping enough during school days?",
    "Do you feel anxious before exams or presentations?",
    "Have you lost interest in extracurricular activities?",
    "Do you feel confident expressing yourself?",
    "Are you experiencing bullying or peer pressure?",
    "Do you feel motivated to attend classes?",
    "Are you able to concentrate during lectures?",
    "Do you feel overwhelmed by expectations?",
    "Are you coping well with changes in routine?",
    "Do you feel emotionally stable most days?",
    "Have you had thoughts of self-harm or isolation?",
    "Do you feel hopeful about your future?"
  ]
};

function loadQuestions() {
  const category = document.getElementById("category").value;
  const survey = document.getElementById("survey");
  const questionsDiv = document.getElementById("questions");
  questionsDiv.innerHTML = "";

  if (!category) {
    survey.classList.add("hidden");
    return;
  }

  questions[category].forEach((q, i) => {
    const div = document.createElement("div");
    div.className = "question";
    div.innerHTML = `<label>${i + 1}. ${q}</label><br>
      <select name="q${i}">
        <option value="1">Never</option>
        <option value="2">Rarely</option>
        <option value="3">Sometimes</option>
        <option value="4">Often</option>
        <option value="5">Always</option>
      </select>`;
    questionsDiv.appendChild(div);
  });

  survey.classList.remove("hidden");
}

function calculateScore() {
  const form = document.getElementById("surveyForm");
  const data = new FormData(form);
  let score = 0;

  for (let value of data.values()) {
    score += parseInt(value);
  }

  let rating = "";
  let tips = [];

  if (score <= 30) {
    rating = "Excellent";
    tips = ["Keep up your healthy habits", "Stay socially connected", "Practice gratitude daily"];
  } else if (score <= 45) {
    rating = "Moderate";
    tips = ["Try mindfulness exercises", "Talk to a friend or mentor", "Get regular sleep and exercise"];
  } else if (score <= 60) {
    rating = "Concerning";
    tips = ["Consider speaking to a counselor", "Limit screen time and stressors", "Journal your thoughts"];
  } else {
    rating = "Critical";
    tips = ["Seek professional help immediately", "Reach out to support groups", "Avoid isolation and stay active"];
  }

  const resultDiv = document.getElementById("result");
  resultDiv.innerHTML = `<h3>Your Mental Wellness Rating: ${rating}</h3>
    <p>Total Score: ${score}</p>
    <h4>Tips to Improve:</h4>
    <ul>${tips.map(t => `<li>${t}</li>`).join("")}</ul>`;
  resultDiv.classList.remove("hidden");
}
</script>

</body>
</html>

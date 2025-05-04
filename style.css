function showMathFact() {
  const info = document.getElementById('math-info');
  info.textContent = "Did you know? Zero is the only number that can't be represented in Roman numerals!";
  info.style.color = '#2a7a2a';
  info.style.fontSize = '18px';
  info.style.backgroundColor = '#e0f7e9';
}

function generateQuestion() {
  const num1 = Math.floor(Math.random() * 10);
  const num2 = Math.floor(Math.random() * 10);
  const questionBox = document.getElementById('question-box');
  questionBox.textContent = `What is ${num1} + ${num2}?`;
}

function toggleDefinition() {
  const box = document.getElementById('definition-box');
  const existing = document.getElementById('definition');

  if (existing) {
    box.removeChild(existing);
  } else {
    const para = document.createElement('p');
    para.id = 'definition';
    para.textContent = 'Mathematics is the study of numbers, quantities, and patterns.';
    box.appendChild(para);
  }
}
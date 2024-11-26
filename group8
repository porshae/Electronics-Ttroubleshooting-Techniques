<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Interactive Buttons with Colors</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 20px;
      background-color: #f4f4f4;
    }
    h1 {
      color: #333;
    }
    button {
      padding: 10px 20px;
      font-size: 16px;
      margin: 10px;
      border: none;
      cursor: pointer;
      color: white;
      width: 100%; /* Adjust button width for mobile */
      max-width: 300px; /* Prevent buttons from getting too wide */
    }
    button#button1 { background-color: red; }
    button#button1:hover { background-color: darkred; }

    button#button2 { background-color: orange; }
    button#button2:hover { background-color: darkorange; }

    button#button3 { background-color: yellow; color: black; }
    button#button3:hover { background-color: gold; }

    button#button4 { background-color: green; }
    button#button4:hover { background-color: darkgreen; }

    button#button5 { background-color: blue; }
    button#button5:hover { background-color: darkblue; }

    button#button6 { background-color: purple; }
    button#button6:hover { background-color: darkpurple; }

    button#button7 { background-color: indigo; }
    button#button7:hover { background-color: darkindigo; }

    button#button8 { background-color: gray; }
    button#button8:hover { background-color: darkgray; }

    .content {
      margin-top: 20px;
      font-size: 18px;
    }
  </style>
</head>
<body>
  <h1>Electronics Troubleshooting Techniques</h1>
  <p>Click a button to see its content!</p>
  <button id="button1" onclick="showParagraph(1)">Sensory Method</button>
  <button id="button2" onclick="showParagraph(2)">Component Substitution</button>
  <button id="button3" onclick="showParagraph(3)">Signal injection and Tracing</button>
  <button id="button4" onclick="showParagraph(4)">Voltage and Current Measurement</button>
  <button id="button5" onclick="showParagraph(5)">Continuity/Resistance Testing</button>
  <button id="button6" onclick="showParagraph(6)">Waveform Analysis</button>
  <button id="button7" onclick="showParagraph(7)">Display Analysis</button>
  <button id="button8" onclick="showParagraph(8)">Circuit Analysis</button>
  <div id="content" class="content"></div>

  <script>
    function showParagraph(buttonNumber) {
      const content = document.getElementById('content');
      const paragraphs = [
        "This is the first paragraph, full of exciting details!",
        "The second paragraph has even more intriguing information!",
        "The third paragraph ties everything together beautifully.",
        "The fourth paragraph is all about interesting facts.",
        "The fifth paragraph brings a touch of mystery.",
        "The sixth paragraph surprises with fun trivia.",
        "The seventh paragraph inspires with wisdom.",
        "The eighth paragraph concludes with a smile."
      ];
      content.innerHTML = `<p>${paragraphs[buttonNumber - 1]}</p>`;
    }
  </script>
</body>
</html>

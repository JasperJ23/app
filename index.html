<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Text to Speech Converter</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            background-color: lightgreen;
            width: 650px;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        h1 {
            color: lightpink;
            text-align: center;
            font-size: 36px;
        }
        #text-input {
            width: 100%;
            padding: 10px;
            font-size: 18px;
            margin: 20px 0;
            border-radius: 5px;
            border: 2px solid #ccc;
        }
        #submit-btn {
            width: 150px;
            padding: 12px;
            font-size: 18px;
            color: white;
            background-color: yellow;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        #submit-btn:hover {
            background-color: orange;
        }
        #voice-select {
            margin-top: 20px;
            font-size: 16px;
            padding: 10px;
        }
        #footer {
            text-align: center;
            font-size: 14px;
            margin-top: 30px;
            color: #555;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Text to Speech</h1>
        <textarea id="text-input" rows="4" placeholder="Enter text here..."></textarea>
        <br>
        <select id="voice-select"></select>
        <br>
        <button id="submit-btn" onclick="convertTextToSpeech()">Submit</button>
        <div id="footer">
            <p>Jasper's Text To Speech App version 1.0<br>Copyright 2024</p>
        </div>
    </div>

    <script>
        let voices = [];
        
        // Load available voices in the browser
        function loadVoices() {
            voices = speechSynthesis.getVoices();
            const voiceSelect = document.getElementById("voice-select");
            voiceSelect.innerHTML = ''; // Clear current options
            voices.forEach(function(voice, index) {
                const option = document.createElement('option');
                option.value = index;
                option.textContent = voice.name;
                voiceSelect.appendChild(option);
            });
        }

        // Convert text to speech
        function convertTextToSpeech() {
            const text = document.getElementById("text-input").value;
            const selectedVoiceIndex = document.getElementById("voice-select").value;
            
            if (text === "") {
                alert("Please enter some text.");
                return;
            }

            // Set up the speech synthesis
            const speechSynthesis = window.speechSynthesis;
            const speech = new SpeechSynthesisUtterance(text);
            speech.voice = voices[selectedVoiceIndex];
            speech.lang = "en-US";  // Set language to English (US)
            speech.rate = 1;  // Set speaking rate

            // Speak the text
            speechSynthesis.speak(speech);
        }

        // Ensure voices are loaded when the page is ready
        window.speechSynthesis.onvoiceschanged = loadVoices;
        loadVoices(); // Load voices immediately
    </script>
</body>
</html>

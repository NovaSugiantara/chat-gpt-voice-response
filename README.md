README
Introduction
This code utilizes OpenAI's GPT-3 model to provide natural language processing for a user's questions or prompts. It allows the user to verbally input their question using a microphone, transcribes the audio into text, generates a response using GPT-3, and then reads the response aloud.

Requirements
To run this code, the following libraries are required:

1. openai
2. speech_recognition
3. pyttsx3
4. dotenv
   Additionally, an OpenAI API key is required, which can be obtained by creating an account on their website.

Usage

1. Install the required libraries.
2. Obtain an OpenAI API key and set it as an environment variable using dotenv.
3. Run the code.
4. When prompted, say "Garpit" to begin recording your question.
5. Once finished speaking, the code will transcribe your audio to text, generate a response using GPT-3, and then read the response aloud.
   Note: This code is currently set up to use a microphone as the audio input source. If using a different input source, the appropriate changes will need to be made. Additionally, some users may need to configure their audio settings or run alsactl init to avoid any errors related to audio input/output.

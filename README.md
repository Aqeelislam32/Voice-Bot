# VoiceBot: AI Conversations

VoiceBot is a Streamlit application that allows users to have AI-powered conversations through voice input. The app captures user speech, converts it to text, sends the text to OpenAI's GPT-3.5-turbo model to generate responses, and then reads the responses aloud using text-to-speech.

Key Features:

Voice Input: Users can interact with the bot by speaking their questions. The app uses the speech_recognition library to capture and transcribe audio input.

AI Response Generation: The app sends the transcribed text to OpenAI's GPT-3.5-turbo model, which generates a response based on the conversation history.

Text-to-Speech: The generated AI response is converted back to speech and played aloud using the pyttsx3 library.

Chat History: The app maintains a history of the conversation, displaying the user's input and the AI's responses in the chat interface.

This application is ideal for hands-free interaction with AI, making it useful for accessibility, smart assistants, or interactive learning scenarios.

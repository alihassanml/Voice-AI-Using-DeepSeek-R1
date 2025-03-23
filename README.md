# Voice AI Using DeepSeek-R1  

## Overview  
This project implements a real-time Voice AI agent using **DeepSeek-R1**, **AssemblyAI**, and **ElevenLabs** for transcription, text-to-speech, and AI-powered responses. The agent listens to user input, processes it with DeepSeek-R1, and responds in both text and speech.  

## Features  
- 🎤 **Real-time transcription** using **AssemblyAI**  
- 🤖 **AI-powered responses** with **DeepSeek-R1**  
- 🗣 **Natural-sounding speech** generation using **ElevenLabs**  
- 🔄 **Seamless conversation loop** with automatic transcription restart  

## Tech Stack  
- **Python**  
- **AssemblyAI** (for speech-to-text)  
- **DeepSeek-R1** (for AI-generated responses)  
- **ElevenLabs** (for text-to-speech)  

## Installation  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/alihassanml/Voice-AI-Using-DeepSeek-R1.git
   cd Voice-AI-Using-DeepSeek-R1
   ```

2. **Create a virtual environment (optional but recommended)**  
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up API keys**  
   - Create a `.env` file and add your API keys:  
     ```
     ASSEMBLYAI_API_KEY=your_assemblyai_key
     ELEVENLABS_API_KEY=your_elevenlabs_key
     ```

5. **Run the AI Voice Agent**  
   ```bash
   python main.py
   ```

## Usage  
- The AI listens to your speech and transcribes it.  
- DeepSeek-R1 processes the input and generates a response.  
- The response is spoken using ElevenLabs text-to-speech.  
- The system continues running in a loop for real-time conversations.  

## To-Do  
✅ Real-time AI chat with voice  
✅ Speech-to-text conversion  
✅ Text-to-speech response  
⬜ Add support for multiple voices  
⬜ Improve error handling  

## License  
This project is **open-source** under the MIT License.  

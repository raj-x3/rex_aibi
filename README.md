# 🤖 Rex — Your Living AI Companion

Rex is an interactive, web-based AI companion designed to make digital interactions more engaging, expressive, and fun. It features an animated robot character that can chat with users, express emotions, respond to interactions, assist with focused study sessions, and provide entertainment through music and games.

Built with HTML, CSS, and JavaScript, Rex combines a futuristic interface with AI-powered conversations and voice capabilities.

## ✨ Features

- **💬 AI Chat:** Have interactive conversations with Rex using the Gemini API.
- **🗣️ Voice Responses:** Generate spoken responses using ElevenLabs text-to-speech.
- **🎭 Emotional Animations:** Watch Rex react with different expressions and animations, including happiness, sadness, anger, sleepiness, dancing, singing, and more.
- **❤️ Interactive Companion:** Use quick actions such as Pet, Kiss, Tickle, Sleep, Tease, Cry, Comfort, Shake, Dance, and Sing.
- **📷 Vision Selfie:** Access your camera and capture a selfie for AI-assisted interaction.
- **📚 Study Buddy:** Use a 25-minute focus timer to support productive study sessions.
- **🏄 Surf Game:** Play a simple surfing game, jump over obstacles, and track your score.
- **🧠 Memory Bank:** Add personal facts for Rex to use as conversational context.
- **🎵 DJ Station:** Search for music and play YouTube videos directly within the interface.
- **🔊 Sound Controls:** Enable or mute audio and configure voice settings.
- **📱 Responsive Design:** Enjoy a layout designed to adapt to desktop and mobile screens.
- **🌌 Modern UI:** Experience a dark, futuristic interface with gradient backgrounds, glowing elements, glassmorphism, and animated effects.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure |
| CSS3 | Styling, transitions, and animations |
| JavaScript | Interactive features and application logic |
| Tailwind CSS | Utility-based styling |
| HTML Canvas API | Animated robot face and game rendering |
| Gemini API | AI-powered conversations |
| ElevenLabs API | Text-to-speech generation |
| Web Speech API | Browser-based voice input, where supported |
| YouTube Embed | Music playback |
| Browser Local Storage | Saving API settings and application data |

## 🚀 Getting Started

### Prerequisites

- A modern web browser such as Google Chrome, Microsoft Edge, or Firefox.
- An internet connection to load external libraries and access the online services.
- A Gemini API key for AI conversations.
- An ElevenLabs API key and Voice ID for generated speech.

### Installation

**1. Clone or download the repository**

```bash
git clone https://github.com/raj-x3/rex_aibi
cd <rex_git>
```



**2. Open the project**

The main application is contained in the `rex_aibi.html` file.

You can open it in a browser for a quick preview. For a more reliable development setup, serve the project using a local web server.

For this you have to visit - https://rexaibi-pi.vercel.app/

### Remote Link 
https://rexaibi-pi.vercel.app/

**3. Configure the API keys**

Use the settings buttons in the application to configure:

- **Gemini API:** Obtain a key from [Google AI Studio](https://aistudio.google.com/apikey).
- **ElevenLabs:** Obtain an API key and select a voice from [ElevenLabs](https://elevenlabs.io/).

Enter the credentials in their respective settings dialogs and save them.

Camera access generally requires HTTPS or a trusted local development environment such as `localhost`. Browser microphone access also depends on permissions and browser support.

## 🎮 How to Use

1. Open Rex in your browser.
2. Start a conversation using the chat input.
3. Configure the Gemini and ElevenLabs settings to enable the corresponding AI features.
4. Use the quick-action buttons to trigger different robot interactions.
5. Open the **Vision** tab to access the selfie feature.
6. Open **Focus** to start a study session.
7. Open **Surf Game** to play the mini-game.
8. Open **Memory** to add facts for future interactions within the current application session.
9. Open **DJ** to search for music and enjoy animated dance interactions.
10. Use the sound control to mute or enable audio.

## 📁 Project Structure

```text
Rex-AI-Companion/
│
├── rex_aibi.html    # Main application, UI, styles, and JavaScript
└── README.md        # Project documentation
```

The project can be organized into separate HTML, CSS, and JavaScript files as it grows.



## 🔮 Future Improvements

- Add secure backend integration for AI and voice services.
- Improve persistent memory with explicit user controls.
- Add configurable focus durations and session statistics.
- Improve accessibility, keyboard navigation, and screen-reader support.
- Add additional games, robot personalities, and interactive animations.
- Improve error handling, loading indicators, and API usage feedback.
- Optimize the interface for different mobile screen sizes.

## 🤝 Contributing

Contributions, suggestions, and bug reports are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Implement and test your changes.
4. Commit and push your changes to your fork.
5. Open a pull request against the original repository.

## 📄 License

No license is specified in the current project file. Before distributing or accepting contributions, choose and add an appropriate open-source license.

## 💙 Acknowledgements

Rex uses services and libraries from Google AI, ElevenLabs, Tailwind CSS, Font Awesome, Google Fonts, and YouTube.

---

**Rex ~ More than a chatbot. An interactive companion that brings personality to your screen.** 🤖💙

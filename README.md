# Sakal Bharati Format Web App

This is a simple web application designed for text formatting, specifically tailored to convert Tamil text into the Sakal Bharati format. Additionally, the app has a speech recognition feature, allowing users to input text via voice in various supported languages. The app is responsive and optimized for both desktop and mobile devices.

## Features

- **Text Formatting**: Converts Tamil text to the Sakal Bharati format by replacing specific characters.
- **Speech Recognition**: Users can input text using voice commands in multiple languages.
- **Clear Text**: Clear both input and output text fields with a single click.
- **Copy Text**: Copy the formatted text to the clipboard for easy sharing.
- **Responsive Design**: Optimized for both mobile and desktop views.

## Live Demo

You can run the app by simply opening the `index.html` file in a browser (preferably Google Chrome) or by deploying it on a local or remote server.

## Installation

1. Clone this repository or download the files.
2. Open the `index.html` file in your browser.
3. Ensure you're connected to the internet to use the speech recognition feature.

## How to Use

1. **Text Conversion**:
    - Paste your Tamil text into the input text area.
    - Click the "Convert Text" button to convert the text to the Sakal Bharati format.
    - The converted text will appear in the output text area.
    
2. **Voice Input**:
    - Select the language from the dropdown menu.
    - Click the "Start Voice" button and speak into your microphone.
    - The recognized text will automatically appear in the input text area.
    - Click "Stop Voice" to end speech recognition.
    
3. **Clear Text**:
    - Click the "Clear Text" button to erase all text from both the input and output text areas.
    
4. **Copy Text**:
    - Once text is formatted, click the "Copy Text" button to copy the output text to the clipboard.

## Supported Voice Input Languages

- English (US)
- Tamil (India)
- Telugu (India)
- Kannada (India)
- Malayalam (India)
- Hindi (India)

You can easily add more languages by editing the `<option>` elements inside the language selection dropdown in the `index.html` file.

## Compatibility

- The app works best in **Google Chrome** as it supports the Web Speech API (`webkitSpeechRecognition`).
- Make sure you are connected to the internet to use the speech recognition feature, as it requires server-side processing from Google's Web Speech API.
- Ensure microphone permissions are enabled for speech recognition to function properly.

## Troubleshooting

- **Speech recognition not working**:
    - Make sure you're using Google Chrome and have a stable internet connection.
    - Ensure that microphone permissions are granted in your browser settings.
    - Speech recognition requires HTTPS. If you're testing locally, use a tool like `ngrok` to serve your app over HTTPS.

- **Speech recognition error: network**:
    - This error occurs if the browser cannot connect to Google's servers. Make sure you are connected to the internet, and that your network allows access to external APIs.

## Contributing

Feel free to contribute to the project by submitting a pull request. Contributions such as adding new features, improving design, or fixing bugs are highly welcome.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- This project uses the **Web Speech API** for speech recognition.
- Special thanks to the open-source community for making this project possible.

---

Enjoy using the Sakal Bharati Format Web App! 🎉

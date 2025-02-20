# isl_avatar
# Sign Language Video Accessibility Extension

## Problem Statement
Most video content (educational or otherwise) on the web is not fully accessible to the deaf community. Even with closed captions, the content may not be entirely understandable due to the nuances of sign language.

## Challenge
To build a browser-based extension that enhances video accessibility by:
- Popping up a window that plays the video content embedded in a browser.
- Displaying sign language interpretations using either pre-recorded videos or an AI-based avatar.

## Solution Overview
This extension aims to make web and mobile-based video content universally accessible for the deaf community by integrating sign language interpretation. It ensures inclusivity across various domains, including:
- **Education**: Enhancing online learning for deaf students.
- **Skilling and Training**: Providing accessibility to vocational and technical training videos.
- **Entertainment**: Enabling an inclusive media consumption experience.

## Features
- **Browser-Based**: Works as an extension across major browsers.
- **Embedded Video Support**: Detects and syncs with web videos.
- **AI-based Avatar**: Converts captions into sign language using AI models.
- **Pre-recorded Sign Videos**: Integrates with existing sign language interpretation databases.
- **Real-time Sync**: Ensures sign language interpretation is in sync with the video.
- **Wide Accessibility**: Supports multiple languages and sign language formats.

## Technology Stack
- **Frontend**: JavaScript, HTML, CSS
- **Backend**: Node.js, Python (for AI-based avatar generation)
- **AI and Machine Learning**: TensorFlow, MediaPipe, OpenAI Whisper (for speech-to-text conversion)
- **Browser APIs**: Web Extensions API

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/your-repo/sign-language-extension.git
   ```
2. Navigate to the project directory:
   ```sh
   cd sign-language-extension
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Load the extension into your browser:
   - Open your browser’s extensions settings.
   - Enable Developer Mode.
   - Load the `src/` folder as an unpacked extension.

## Usage
1. Open any web page with a video.
2. Click on the extension icon.
3. A pop-up window will appear with sign language interpretation.
4. View the accessible video content in real time.

## Future Enhancements
- **Mobile Application Integration** for accessibility on smartphones and tablets.
- **Advanced AI Models** for improved sign language translation.
- **Multi-language Support** for a global impact.
- **Cloud-based Processing** for scalable real-time translations.

## Contributing
Contributions are welcome. Please fork this repository and submit a pull request with improvements.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any queries or collaborations, please reach out via GitHub issues or email at `khushi7narang@gmail.com`.


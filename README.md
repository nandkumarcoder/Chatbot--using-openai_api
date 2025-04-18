# Chatbot Using OpenAI API

A voice-enabled chatbot built using Python, OpenAI's GPT model, and speech recognition. This chatbot listens to user input via a microphone, generates responses using OpenAI's API, and optionally speaks the response back to the user.

## Features

- Voice input using a microphone.
- Text-based responses generated using OpenAI's `text-davinci-003` model.
- Option to hear the chatbot's response using text-to-speech.
- Continuous conversation until the user decides to exit.

## Prerequisites

- Python 3.x installed on your system.
- Required Python libraries:
  - `openai`
  - `speechrecognition`
  - `pyttsx3`

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd Chatbot--using-openai_api
   ```
3. Install the required libraries:
   ```bash
   pip install openai speechrecognition pyttsx3
   ```

## Usage

1. Open the `eg2.py` file and replace the `openai.api_key` value with your OpenAI API key.
2. Run the script:
   ```bash
   python eg2.py
   ```
3. Speak into the microphone when prompted with "speak now...".
4. The chatbot will process your input and provide a response.
5. Choose whether to print the response or print and hear it using text-to-speech.
6. To exit, say "exit" or type "no" when asked if you want to ask more questions.

## Example

- **Input (spoken):** "What is the capital of France?"
- **Output (printed):** "The capital of France is Paris."
- **Optional (spoken):** "The capital of France is Paris."

## File Structure

- `eg2.py`: The main script containing the chatbot logic.

## Notes

- Ensure your microphone is properly configured and accessible by the script.
- The OpenAI API key is required to use the chatbot. Obtain it from [OpenAI](https://platform.openai.com/).



## License

This project is licensed under the MIT License.

## Acknowledgments

- [OpenAI](https://openai.com/) for providing the GPT model.
- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/) for voice input functionality.
- [pyttsx3](https://pypi.org/project/pyttsx3/) for text-to-speech capabilities.

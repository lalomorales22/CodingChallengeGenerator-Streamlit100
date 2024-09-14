# Coding Challenge Generator

Coding Challenge Generator is a Streamlit-based application that creates customized coding problems to help users practice and improve their programming skills. It uses advanced language models to generate challenges tailored to specific programming languages, difficulty levels, and problem types.

## Features

- Interactive chat interface for requesting and receiving coding challenges
- Support for multiple AI models (OpenAI and Ollama)
- Customizable challenge parameters:
  - Programming language
  - Difficulty level
  - Challenge type
- Conversation saving and loading functionality
- Token usage tracking
- Dark/Light theme options

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/lalomorales22/CodingChallengeGenerator-Streamlit100.git
   cd coding-challenge-generator
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up your OpenAI API key:
   - Create a `.env` file in the project root
   - Add your OpenAI API key: `OPENAI_API_KEY=your_api_key_here`

## Usage

1. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

2. Open your web browser and go to `http://localhost:8501`

3. Enter your name and configure your challenge preferences in the sidebar

4. Start requesting coding challenges and interacting with the AI!

## Customization

- Modify the `PROGRAMMING_LANGUAGES`, `DIFFICULTY_LEVELS`, and `CHALLENGE_TYPES` lists in `app.py` to add or remove options
- Adjust the `custom_instructions` in the sidebar to change the AI's behavior and focus

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

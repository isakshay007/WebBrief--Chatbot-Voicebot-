# WebBrief

WebBrief is a Python-based web application built using Streamlit and the Lyzr SDK. It allows users to explore webpages, generate summaries, uncover insights, and create structured notes through interactive prompts.

## Features
- **Webpage Exploration**: Analyze webpages via URL input.
- **Pre-Defined Prompts**: Quick insights like summaries, historical context, notable figures, and controversies.
- **Custom Queries**: Generate specific notes for user-defined questions.
- **Interactive GUI**: Built with Streamlit for seamless user experience.
- **VoiceBot Integration**: Converts responses into structured notes.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/webbrief.git
   cd webbrief
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Install Playwright:
   ```bash
   playwright install
   ```

4. Set up OpenAI API key:
   - Create a `.streamlit/secrets.toml` file:
     ```toml
     [apikey]
     apikey = "your-openai-api-key"
     ```

5. Run the application:
   ```bash
   streamlit run app.py
   ```

## Usage
1. Enter the webpage URL in the input field.
2. Use pre-defined prompts or enter a custom query.
3. View responses and generate structured notes.

## Key SDKs and Libraries
- **Lyzr SDK**: ChatBot and VoiceBot for webpage analysis and note generation.
- **Streamlit**: For interactive GUI.
- **Playwright**: For web scraping.
- **Pillow**: For image rendering.

## License
This project is licensed under the MIT License.


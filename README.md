# Your Therapist Chatbot
![LLM](https://github.com/user-attachments/assets/4cf5d961-84fb-4146-a7b4-188685cf6753)


This project is a Streamlit-based chatbot application designed to provide mental health support through conversational AI. The chatbot uses a language model to generate responses based on user input and converts the responses to speech using the Google Text-to-Speech API.

## Features

- **Conversational AI**: Provides responses based on user input.
- **Text-to-Speech**: Converts the chatbot's responses into spoken words.
- **Document Retrieval**: Loads and processes PDF documents for context-aware responses.

## Prerequisites

1. **Python**: Ensure you have Python 3.8 or later installed.
2. **Virtual Environment**: It's recommended to use a virtual environment for managing dependencies.

## Setup

1. **Clone the Repository**

    ```bash
    git clone https://github.com/yourusername/your-repository.git
    cd your-repository
    ```

2. **Create and Activate a Virtual Environment**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install Dependencies**

    ```bash
    pip install -r requirements.txt
    ```

4. **Download the LLaMA Model**

    The LLaMA model is not included in the project and must be downloaded separately. You can download the model from the following link:

    [Download LLaMA Model](https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/blob/main/llama-2-7b-chat.ggmlv3.q4_0.bin)

    After downloading, place the model file in the appropriate directory or adjust the code to point to the location of the model file.

5. **Run the Application**

    ```bash
    streamlit run your_app.py
    ```

## Usage

- Open the application in your browser.
- Type your question or message in the input field.
- Click "Send" to receive a response from the chatbot.
- The chatbot's responses will be read aloud.

## Note

- Ensure that you have the LLaMA model file available as described above. The application will not function correctly without this model.
- If you encounter any issues, please refer to the documentation or contact support.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please contact [hello@pragcodes.co](mailto:hello@pragcodes.co).

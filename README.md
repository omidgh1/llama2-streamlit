# Llama 2 Chatbot - Nexum-AI

Llama 2 Chatbot is a dynamic and customizable chatbot application powered by Nexum-AI, built using Streamlit and Replicate. This project allows users to interact with various Llama 2 models and tune parameters to enhance their chat experience.

## Features

- **Multiple Models:** Choose from Llama2-7B, Llama2-13B, and Llama2-70B models.
- **Customizable Parameters:** Adjust temperature, top_p, and max_length for tailored responses.
- **Chat History:** View and clear chat history.
- **Secure API Integration:** Input your Replicate API token securely.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/llama2-chatbot.git
   cd llama2-chatbot
   ```
2. Install the required packages:
```bash
pip install -r requirements.txt
```
3. Set up your Replicate API token:

Add your REPLICATE_API_TOKEN to your Streamlit secrets or input it manually in the sidebar when running the app.

## Usage
1. Run the Streamlit app:

```bash
streamlit run app.py
```
2. Open your web browser and navigate to the provided local URL.

3. Interact with the chatbot by entering your prompt in the chat input.

## Configuration
- **Select Model:** Choose between Llama2-7B, Llama2-13B, and Llama2-70B from the sidebar.
- **Adjust Parameters:** Use the sidebar sliders to modify temperature, top_p, and max_length.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## Acknowledgements
Streamlit
Replicate

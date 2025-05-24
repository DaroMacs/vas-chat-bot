# VAS Chat Bot

An AI-powered chatbot that combines text generation and image creation capabilities using the Together AI API. The bot is designed to provide Buddhist philosophical advice while generating relevant pixel art images.

## Features

- 🤖 Interactive chat interface using Gradio
- 📝 Text generation using Meta-Llama-3-8B-Instruct-Lite model
- 🎨 Image generation with FLUX.1-schnell-Free model
- 🧘‍♂️ Buddhist philosophy-based responses
- 🖼️ Automatic pixel art image generation for each response

## Prerequisites

- Python 3.x
- Together AI API key
- Required Python packages (see Installation)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/vas-chat-bot.git
cd vas-chat-bot
```

2. Install the required packages:

```bash
pip install together gradio pillow requests
```

## Usage

The script can be run with different options:

1. Text Generation Only:

```bash
python main.py -o 1 -k YOUR_API_KEY
```

2. Image Generation Only:

```bash
python main.py -o 2 -k YOUR_API_KEY
```

3. Combined Text and Image Generation:

```bash
python main.py -o 3 -k YOUR_API_KEY
```

4. Interactive Chatbot Interface:

```bash
python main.py -o 4 -k YOUR_API_KEY
```

## Features in Detail

### Text Generation

- Uses Meta-Llama-3-8B-Instruct-Lite model
- Provides concise, philosophical responses
- Grounded in Buddhist teachings from the Tibetan Book of the Dead

### Image Generation

- Creates pixel art style images
- Automatically generates relevant images for each chat response
- Supports custom dimensions (default: 256x256)

### Chat Interface

- Clean, user-friendly Gradio interface
- Real-time chat history
- Automatic image generation for each response
- Support for both button clicks and Enter key submissions

## API Configuration

To use the chatbot, you need to:

1. Sign up for a Together AI account
2. Obtain your API key
3. Pass the API key when running the script using the `-k` or `--api_key` parameter

## Output

- Generated images are saved in the `results` directory
- Chat history is maintained during the session
- Images are displayed in real-time in the chat interface

## License

[Add your license information here]

## Contributing

[Add contribution guidelines here]

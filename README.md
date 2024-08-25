# 🌌 BatchBot: The AI-Powered Discord Bot (Free & Open Source) 🚀

[![Watch the Tutorial](https://img.shields.io/badge/Watch%20Tutorial-%F0%9F%93%BA-red)](https://youtu.be/ow-Cw8OLTdI)

## Introduction

**BatchBot** is a cutting-edge Discord bot powered by advanced AI models, designed to bring a wide array of features to your server—completely free of charge. Whether you want to engage in natural conversations, analyze or generate images, summarize web searches, or explore various other capabilities, BatchBot has you covered.

## 🌟 Features

BatchBot offers a rich set of features powered by state-of-the-art AI models:

- **🤖 AI Chat**  
  Engage in dynamic conversations with BatchBot using Google Gemini AI models (Gemini 1.5 Pro, Gemini 1.5 Pro Advanced, Gemini 1.5 Flash). It understands context, provides insightful answers, generates creative content, and can even engage in role-playing scenarios.

- **🖼️ Image Processing**  
  Upload images, and BatchBot will use powerful vision models to generate detailed descriptions. It can identify objects, scenes, and emotions within the images.

- **🎥 Video Processing**  
  Upload videos, and BatchBot will use powerful vision models to generate detailed descriptions. It can identify objects, scenes, and emotions within the video.

- **🎨 Image Generation**  
  Create stunning and personalized images using Hugging Face's Stable Diffusion. You can generate anything from imaginative scenes to funny memes based on your text prompts.

- **📺 YouTube Analysis**  
  Get summaries and transcripts from YouTube videos. BatchBot can analyze video URLs, extract content, and provide concise summaries.

- **📂 File Analysis**  
  Analyze and extract information from a variety of file types including PDFs, DOCX, Markdown, Python code, JavaScript, and more. BatchBot can also provide summaries and insights from these files.

- **🌐 Web Search and Summarization**  
  Utilize DuckDuckGo's API for web searches. BatchBot provides summaries of the most relevant search results, making it easy to find the information you need.

- **🧠 Memory**  
  BatchBot can remember important information shared during conversations or stored via commands. This feature enables personalized interactions and a better understanding of your preferences.

- **🔤 Custom User Names**  
  Set a custom name for yourself in interactions with BatchBot, enhancing personalization and user experience.

- **🚀 And More!**  
  BatchBot continues to evolve with new features and improvements, providing even more value to your server.

## Getting Started

To get BatchBot up and running on your Discord server, follow these steps:

### 📋 Prerequisites

- A Discord server.
- Python 3.9+ installed.
- A Discord Bot account: [Discord Applications](https://discord.com/developers/applications) 
- An API Key from Google Generative AI (Gemini): [Gemini API Key](https://aistudio.google.com/app/apikey)
- An API Key from Hugging Face: [Hugging Face API Key](https://huggingface.co/settings/tokens)

### 🛠️ Install Dependencies

1. Clone the repository:

   ```bash
   git clone https://github.com/YoussefElsafi/Advanced-AI-Discord-Bot-BatchBot.git
   cd Advanced-AI-Discord-Bot-BatchBot
   

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   

### ⚙️ Configure Settings

Edit the `system/config.py` file with the following content and replace the placeholders with your actual API keys and tokens:

```python
TOKEN = "YOUR_DISCORD_BOT_TOKEN"
API_KEY = "YOUR_GOOGLE_GENERATIVE_AI_API_KEY"
HUGGING_FACE_API = "YOUR_HUGGING_FACE_API_KEY"
# Add other configuration settings as needed


### 🚀 Run the Bot

Start the bot using the following command:

```bash
python main.py


## Usage

Interact with BatchBot using the following commands:

- `/ai [prompt]`: Starts a conversation with BatchBot. Use this command for any text-based prompt.
- `/generate [description]`: Generates an image based on the provided description.
- `/analyze [image_url]`: Analyzes an image and provides a detailed description.
- `/summarize [youtube_url]`: Summarizes a YouTube video and provides a transcript.
- `/file [file_url]`: Analyzes a file and provides key insights.

For a full list of commands, type `/help` in Discord after adding BatchBot to your server.

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before submitting a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgements

- [Google Generative AI](https://aistudio.google.com/app) for providing the advanced AI models.
- [Hugging Face](https://huggingface.co/) for the image generation models.
- [DuckDuckGo](https://duckduckgo.com/) for the web search API.
- And all the amazing contributors who have helped improve BatchBot!

## Support

If you have questions or need assistance, you can:

- Reach out via email: [support@example.com](mailto:batchbothelp@gmail.com)
- Open an issue on our [GitHub repository](https://github.com/YoussefElsafi/Advanced-AI-Discord-Bot-BatchBot/issues)
- Watch our [YouTube tutorial](https://youtu.be/ow-Cw8OLTdI) for setup instructions
- Check our [Documentation](DOCUMENTATION.md) for detailed guides

Enjoy using BatchBot! 🚀

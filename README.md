# AI-Poetica: Video Creation Suite

AI-Poetica is a robust and innovative video creation suite that leverages artificial intelligence to generate engaging videos with text-to-speech. Whether you need a marketing jingle, a poetic narration, or a unique multimedia experience, AI-Poetica has got you covered!

## Features

- **AI-Powered Text Generation**: Utilizes OpenAI's GPT models to create compelling and creative content.
- **Image Integration**: Fetches relevant images from Unsplash to visually enhance the video.
- **Text-to-Speech Conversion**: Transforms the generated text into audible speech, making the content more accessible and engaging.
- **Video Composition**: Seamlessly combines images, text, and audio into a cohesive video clip.

## Requirements

- Python 3.x
- OpenAI API Key
- Unsplash API Key
- ImageMagick Binary

## Installation

1. Clone the repository.
2. Install the required libraries using the command:
   ```bash
   pip install openai requests gtts pydub moviepy python-dotenv
   ```
3. Add your OpenAI and Unsplash API keys to a `.env` file.

## Usage

1. Modify the `humanprompt` and `keywords` variables in the script as per your requirement.
2. Run the script:
   ```bash
   python main.ipynb
   ```
3. The final video will be created in the specified output directory.

## Example

```python
humanprompt = "Waterbottle of joy"
keywords = "water, bottle, joy"
create_video_from_prompt(aiprompt)
```

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Support

For support and inquiries, please reach out to [harsh.avinash.official@gmail.com](mailto:harsh.avinash.official@gmail.com).

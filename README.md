# Image Generator Using DALL-E

A simple Python script that generates AI-powered images from text prompts using **OpenAI's DALL-E model** — just describe what you want, and let AI create it.

---

## About

This project leverages the OpenAI Images API to convert natural language text prompts into AI-generated images. It's a clean, minimal Python implementation that demonstrates how to integrate DALL-E into your own applications.

---

## Features

- **Text-to-Image Generation** — Describe any scene or concept in plain English and get a generated image
- **OpenAI DALL-E Integration** — Powered by OpenAI's industry-leading image generation model
- **Minimal Setup** — Single Python script, quick to run
- **Image URL Output** — Returns a direct link to the generated image

---

## Tech Stack

| Technology | Details |
|---|---|
| Language | Python |
| API | OpenAI DALL-E |
| Library | `openai` |

---

## Getting Started

### Prerequisites

- Python 3.7.1 or higher
- An [OpenAI API key](https://platform.openai.com/account/api-keys)

### Installation

1. **Clone the repository**
```bash
   git clone https://github.com/sanasreeraj/Image_Generator_Using_DALL-E.git
   cd Image_Generator_Using_DALL-E
```

2. **Install dependencies**
```bash
   pip install openai
```

3. **Set your OpenAI API key**

   On macOS/Linux:
```bash
   export OPENAI_API_KEY="your-api-key-here"
```

   On Windows (Command Prompt):
```cmd
   set OPENAI_API_KEY="your-api-key-here"
```

4. **Run the script**
```bash
   python algae.py
```

---

## API Key Security

- **Never hardcode** your API key directly in the source code
- Use environment variables or a `.env` file to store sensitive credentials
- Add `.env` to your `.gitignore` to prevent accidental exposure

---

## Project Structure
```
Image_Generator_Using_DALL-E/
└── algae.py        # Main script — handles prompt input and DALL-E API call
```

---

## Example Usage

Update the prompt inside `algae.py` to generate your desired image:
```python
prompt = "a futuristic city skyline at sunset with flying cars"
```

Run the script and receive a URL to your AI-generated image.

---

## Author

**Sana Sreeraj** — [@sanasreeraj](https://github.com/sanasreeraj)

---

> *"Words become worlds — one prompt at a time."*

# AI-Powered Multimodal Chatbot Assistant

## Problem Statement📚

With the increasing volume and variety of digital content, there is a need for a unified tool that can handle different types of media seamlessly. Users often have to switch between multiple applications to manage audio, images, and document interactions, which is inefficient and cumbersome. 

## Solution🔍

"The AI-Powered Multimodal Chatbot Assistant" addresses this issue by integrating multiple AI models into a single chat interface. This allows users to interact with audio, images, and PDF documents within one platform, enhancing productivity and user experience.

## Technologies Used 🚀
- **Python**: The core programming language used for developing the application.
- **Streamlit**: Used for building the web interface.
- **Whisper AI**: For audio transcription and processing.
- **LLaVA**: For image understanding and interaction.
- **Chroma DB**: For PDF handling and interaction.
- **TheBloke Quantized Models**: For optimizing AI models to run efficiently on standard hardware.

## Overview

**AI-Powered Multimodal Chatbot Assistant** is a project that combines audio, image, and PDF processing into a single chat application using advanced AI models. It offers a hands-on learning experience by integrating Whisper AI, LLaVA, and Chroma DB to create an interactive chatbot. Contributions are encouraged to improve and expand the project further.

## Features

### Quantized Model Integration⚡

This application uses "quantized models," which are optimized for performance on standard consumer hardware. While traditional AI models demand powerful machines, these quantized versions deliver efficient performance without compromising accuracy. This ensures that the chatbot runs seamlessly on everyday computers. (Powered by TheBloke Quantized Models)

### Audio Chatting with Whisper AI🎙️

Whisper AI brings advanced audio transcription capabilities to the chatbot, enabling natural voice input and output. This feature facilitates smooth, interactive conversations through voice. (Powered by Whisper Models)

### Image Chatting with LLaVA🖼️

The chatbot integrates LLaVA, a fine-tuned LLaMA model, for understanding and interacting with images. Using CLIP-generated image embeddings, LLaVA provides advanced text-image comprehension, creating an engaging and dynamic chat experience around visual content. (Powered by llama-cpp-python)

### PDF Chatting with Chroma DB📄

Designed for professional and academic use, this feature utilizes Chroma DB as a vector database for efficient PDF interactions. Users can upload and interact with PDFs to extract summaries, insights, or engage in a dialogue with the content. Whether it's a business report or an academic paper, the chatbot offers an intuitive and powerful way to interact with PDF data. (Powered by Chroma)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/ai-powered-multimodal-chatbot-assistant.git
   cd ai-powered-multimodal-chatbot-assistant

2. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt

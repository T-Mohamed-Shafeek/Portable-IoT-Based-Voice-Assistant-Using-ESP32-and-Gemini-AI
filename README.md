# Portable IoT-Based Voice Assistant Using ESP32 and Gemini AI

## Overview

This project demonstrates the integration of an **ESP32 microcontroller** with a **Gemini AI model** to create a portable, low-power **voice assistant** capable of real-time question answering. The system allows users to interact with the assistant using voice commands, and it provides responses using advanced **natural language processing** and **text-to-speech** technologies. By utilizing the **Deepgram API** for speech-to-text (STT) and providing options for TTS via multiple services, the assistant delivers a seamless user experience in various applications such as smart home control, educational tools, and personal assistance.

## Features

- **Push-to-Ask**: Press a button to initiate voice commands.
- **Real-Time Responses**: Utilizes the Gemini AI model for real-time question answering.
- **External SD Card Support**: Stores longer queries and additional data.
- **Built-in Speaker & 3.5mm Audio Jack**: Provides audio output through the built-in speaker or external audio devices.
- **Repeat Button**: Replay the previous answer.
- **Fully Programmable**: Easily customizable for different applications and use cases.
- **Battery-Powered**: Ensures portability and long-lasting operation.

## Components

- **ESP32 Microcontroller**: Core processing unit for managing voice interactions.
- **I2S Microphone**: Captures voice commands from the user.
- **I2S Amplifier**: Amplifies audio signals for output.
- **Speaker**: Outputs the voice assistant's responses.
- **SD Card**: Stores data such as long queries or configuration settings.
- **3.5mm Audio Jack**: Connects external audio devices.
- **Type C Port**: For programming and charging the device.
- **Battery**: Powers the device for portable use.

## Project Structure

```bash
.
├── /src                 # Source code for ESP32, STT, TTS, and AI integration
├── /docs                # Documentation and project guidelines
├── /hardware            # PCB design and hardware component details
└── /test                # Unit tests and hardware validation scripts
```
## Installation and Setup

## Clone the Repository
```bash
git clone https://github.com/your-username/portable-voice-assistant-esp32.git
```

## Change the working directory
```bash
cd portable-voice-assistant-esp32
```

## ESP32 Setup
- **Install the ESP32 Arduino IDE.**
- **Connect the ESP32 microcontroller to your system via the Type C port.**

## Libraries and Dependencies
Install the required libraries for ESP32 and AI model integration:
- ESP32 Core Libraries
- I2S Libraries
- Deepgram API for STT
- Text-to-Speech API (Google TTS)
- Gemini AI Model Integration (use provided code)

## Programming the ESP32
- **Open the voice_assistant.ino file in the Arduino IDE.**
- **Upload the code to your ESP32.**

## Hardware Assembly
- **Connect the I2S microphone, amplifier, speaker, and SD card to the ESP32 as per the circuit diagram provided in the /docs folder.**
- **Ensure the power supply (battery) is connected properly for portability.**


## API Key Setup
- **Obtain your Deepgram API key and Text-to-Speech API credentials.**
- **Add these to the configuration file in /src/config.**

## Usage
- **Power on the Device: Once powered, the assistant will be ready to process queries.**
- **Push to Ask: Press the Push-to-Ask button to give a voice command.**
- **Voice Interaction: The assistant will capture your query, process it using the Gemini AI model, and respond audibly via the speaker or 3.5mm jack.**
- **Repeat Function: Press the Repeat button to replay the last response.**
  
## Block Diagram
**Refer to the block diagram in the /docs folder for a visual overview of the system architecture.**

## Future Enhancements
- **Expanded Voice Command Library: Add more voice commands for increased functionality.**
- **Smart Home Integration: Integrate with popular smart home platforms like Google Home or Alexa.**
- **Enhanced AI Models: Integrate more powerful AI models like Llama or GPT for improved responses.**
- **Improved Voice Recognition: Implement local speech-to-text processing for offline use.**

## License
**This project is licensed under the MIT License.**

## Contact
**For any questions, feel free to reach out:**
**Name: Mohamed Shafeek T.**
**Email: shafeeubaidah@gmail.com**
**LinkedIn : https://www.linkedin.com/in/mohamed-shafeek-t-a226981b9/**

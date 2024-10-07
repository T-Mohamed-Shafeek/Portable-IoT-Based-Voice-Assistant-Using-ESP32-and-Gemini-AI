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
- **Repeat Button**: Plays the previous response.
- **Type C Port**: For programming and charging the device.
- **Battery**: Powers the device for portable use.

## Project Structure

```bash
.
├── /src                 # Source code for ESP32, STT, TTS, and AI integration
├── /docs                # Documentation and project guidelines
├── /hardware            # PCB design and hardware component details
└── /test                # Unit tests and hardware validation scripts

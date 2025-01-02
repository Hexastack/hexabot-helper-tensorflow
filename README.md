# Hexabot Tensorflow NLU Helper Extension

The Tensorflow NLU Helper is an extension for Hexabot that acts as a utility class to interact with the Tensorflow NLU engine.

Hexabot is an open-source chatbot / agent solution that allows users to create and manage AI-powered, multi-channel, and multilingual chatbots with ease. If you would like to learn more, please visit the [official github repo](https://github.com/Hexastack/Hexabot).

This helper extension simplifies the use of the Tensorflow NLU engine by providing methods for preprocessing responses, formatting incoming data, and managing settings. These utilities can be leveraged across various components of Hexabot's architecture to enhance overall functionality and performance.

## Tensorflow NLU Engine

The **Hexabot Tensorflow NLU** engine is designed to process and analyze text input, extracting key information such as intent and entities to facilitate downstream tasks like chatbot interactions.  For more details, check the [official Github Repository](https://github.com/Hexastack/hexabot-tensorflow-nlu)

## Installation

To use the Hexabot Tensorflow NLU Helper Extension within Hexabot, follow the steps below: 
```bash
cd ~/projects/my-chatbot
npm install hexabot-helper-tensorflow
hexabot dev --services nlu
```
## Usage
The Hexabot Tensorflow NLU Helper provides a range of methods to interact with the Tensorflow NLU engine. Here’s how you can use its functionalities.

### Settings
The extension provides configurable settings that can be adjusted to suit your needs. Below are the available settings:
- **API Token:** API token required for authentication with the NLU engine.
- **Endpoint:** URL of the Tensorflow NLU API endpoint to interact with
- **Confidence:** Sets the minimum confidence score required for predictions.

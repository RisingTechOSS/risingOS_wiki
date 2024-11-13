# AI Assistant Documentation

## Overview

The AI Assistant is a beta feature designed to assist users, especially those with visual impairments, through voice commands. It provides hands-free control over various device functions by recognizing and responding to voice inputs.

Risa is a system service specifically programmed to recognize a set of voice commands. Unlike other AI assistants, Risa does not collect data for machine learning purposes. It operates by utilizing system resources to execute commands. The system relies on Gemini’s API key to handle unprogrammed responses, connecting through the Gemini API without collecting or transmitting user data, except for the specific command or question the user provides.

Risa can function without the Gemini API key for executing commands listed in the Supported Phrases section. However, for broader requests, such as general assistance, it requires Gemini to process the request. Additionally, Risa needs an internet connection and a text-to-speech engine to operate effectively.

> **Note**: Currently, the AI Assistant only supports English. Contributions to add support for other languages and refinements are welcome! Feel free to submit a pull request if you’d like to contribute.

---

## Activation

To activate the assistant, perform a two-finger swipe-down gesture. An orb animation will appear, indicating that the assistant is loading or preparing a session.

---

## Supported Phrases

The assistant requires an internet connection and text-to-speech functionality (a text-to-speech update may be needed).

### Application Control
- **"Launch/Open `<application_name>`"** - Launches the specified application  
  - Example: `"Launch Settings"`

- **"Launch/Open `<application_name>` in freeform mode"** - Launches the specified application in freeform/multi-window mode  
  - Example: `"Launch Brave in freeform"`

### Media Playback
- **"Play music/song/media"** - Starts playing music or media  
  - Example: `"Play music"`

- **"Stop/Pause music/song/media"** - Pauses any active playback  
  - Example: `"Stop music"`

- **"Next/Prev music/song/media"** - Skips to the next or previous song  
  - Example: `"Next music"`

### Device Settings
- **"Turn on/off Bluetooth"** - Activates or deactivates Bluetooth  
  - Example: `"Turn on Bluetooth"`

- **"Clear all notifications"** - Clears all notifications in the Quick Settings panel  
  - Example: `"Clear all notifications"`

- **"Show Volume Panel"** - Displays the volume panel  
  - Example: `"Show Volume Panel"`

- **"Turn on/off torch/flashlight"** - Activates or deactivates the device’s flashlight  
  - Example: `"Turn on torch"`

### General Assistance
- **"Why/What/When..."** - Asks questions and receives answers via Gemini (Gemini API key required)  
  - Example: `"When is Christmas?"`

- **"Connect with ChatGPT"** - Connects to ChatGPT to launch its assistant  
  - Example: `"Connect with ChatGPT"`

### Ringer Mode
- **"Set ringer mode to silent/vibrate/normal"** - Changes the device ringer mode to the specified setting  
  - Example: `"Set ringer to silent"`

---

This documentation serves as a guide for using voice commands with the AI Assistant. Each command can streamline interaction with the device, especially for users requiring accessibility support.

# Ivy Streams - Agora Video Calling Application

## Overview

**Ivy Streams** is a web-based video calling application utilizing the Agora API for real-time communication. This project demonstrates the integration of the Agora RTC SDK for enabling video and audio streaming capabilities.

## Features

- **Join Stream:** Users can join a video stream.
- **Leave Stream:** Users can leave the video stream.
- **Toggle Microphone:** Users can mute or unmute their microphone.
- **Toggle Camera:** Users can turn their camera on or off.
- **Real-time User Management:** Handles user joining and leaving events in real time.

## Technologies Used

- **HTML:** For structuring the web page.
- **CSS:** For styling the user interface.
- **JavaScript:** For implementing the application logic and Agora API integration.
- **Agora RTC SDK:** For real-time video and audio streaming.

## Setup and Installation

To run the Ivy Streams application locally, follow these steps:

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/your-username/ivy-streams.git
   cd ivy-streams
   ```

2. **Install Dependencies:**
   This project uses the Agora RTC SDK, which is included in the project. No additional installation is required.

3. **Set Up Agora Account:**
   - Sign up for an Agora account at [Agora](https://www.agora.io/).
   - Create a new project in the Agora console and obtain the APP ID and Temporary Token.
   - Replace the placeholder `APP_ID` and `TOKEN` in the `index.js` file with your Agora project credentials.

4. **Run the Application:**
   Open the `index.html` file in your preferred web browser.

## Usage

1. **Join a Stream:**
   - Click the "Join Stream" button to connect to the video stream.
   - The user's video will be displayed in the video stream container.

2. **Leave a Stream:**
   - Click the "Leave Stream" button to disconnect from the video stream.
   - The user's video will be removed from the video stream container.

3. **Toggle Microphone:**
   - Click the "Mic On" button to mute or unmute the microphone.

4. **Toggle Camera:**
   - Click the "Camera On" button to turn the camera on or off.

## Code Overview

### HTML
The `index.html` file contains the structure of the web application, including buttons for joining and leaving streams, and toggling microphone and camera.

### CSS
The `main.css` file is used for styling the user interface elements such as buttons and video containers.

### JavaScript
The `index.js` file includes the logic for interacting with the Agora RTC SDK:

- **joinStream:** Handles joining the stream and displaying the local video.
- **handleUserJoined:** Manages newly joined remote users and displays their video.
- **handleUserLeft:** Manages users leaving the stream and removes their video.
- **toggleMic:** Toggles the microphone state between muted and unmuted.
- **toggleCamera:** Toggles the camera state between on and off.
- **Event Listeners:** Set up for join, leave, microphone toggle, and camera toggle buttons.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or new features..

---

Enjoy using Ivy Streams! Happy streaming!

# WebRTC Video Chat Application

DebugDen is a robust video chat application built using WebRTC and the Agora SDK. It supports group video calling and real-time chat messaging.

### Deployed - https://keshav1sharma.github.io/Debug_Den/

## About WebRTC

WebRTC (Web Real-Time Communication) is a free, open-source project that provides web browsers and mobile applications with real-time communication (RTC) via simple APIs. It allows audio and video communication to work inside web pages by allowing direct peer-to-peer communication, eliminating the need to install plugins or download native apps.

## Features

- **Group Video Calling**: The application supports group video calling, allowing multiple users to join the same room and participate in a video chat.
- **Real-Time Chat**: In addition to video calling, the application also supports real-time chat messaging. Users can send and receive messages in real-time while in a video call.

## How it Works

This application uses the Agora SDK for WebRTC communication. The SDK provides easy-to-use APIs that help with implementing real-time, interactive video functionality.

The main files involved in DebugDen are:

- [room.html](room.html): This is the main room where the video chat happens.
- [lobby.html](lobby.html): This is the lobby where you can create a new room.
- [js/room_rtc.js](js/room_rtc.js): This file contains the logic for the RTC (Real-Time Communication) functionality.
- [js/room_rtm.js](js/room_rtm.js): This file contains the logic for the RTM (Real-Time Messaging) functionality.

When a user creates a room, the application establishes a connection with the Agora servers using the Agora SDK. Once the connection is established, the user can share the room link with others. When other users join the room, their video streams are added to the RTC connection, enabling real-time video chat.

## Getting Started

To get started with DebugDen, simply clone the repository and open `index.html` in your browser. Make sure to replace the placeholder values in the `room_rtc.js` and `room_rtm.js` files with your Agora App ID and Token.

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## License

DebugDen is open source and available under the [MIT License](LICENSE).

# Aora Video Sharing Platform

## Description
Aora is a dynamic, mobile-first video sharing platform that brings the power of content creation and consumption to your mobile device. Built with React Native, Aora offers a seamless native app experience for uploading, watching, and interacting with videos. With features like user authentication, video uploading, commenting, and personalized recommendations, Aora provides a robust alternative to platforms like YouTube, optimized for mobile devices. Whether you're a content creator looking to share your vision or a viewer seeking entertainment and knowledge on-the-go, Aora offers an intuitive and engaging platform for all your video needs.

## Topics
video-sharing react-native mobile-app javascript user-authentication video-streaming content-creation social-media cross-platform ios android

## Table of Contents
- [Aora Video Sharing Platform](#aora-video-sharing-platform)
  - [Description](#description)
  - [Topics](#topics)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Technologies Used](#technologies-used)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Credits](#credits)
  - [License](#license)

## Features
- User authentication and profile management
- Video uploading and processing
- Video playback with quality options
- Commenting and interaction system
- Like and dislike functionality
- User subscriptions
- Trending videos and personalized recommendations
- Search functionality
- Cross-platform support (iOS and Android)
- Offline viewing capabilities

## Technologies Used
- Frontend: React Native, JavaScript
- Authentication: JWT
- Video Processing: FFmpeg
- State Management: Redux
- Navigation: React Navigation
- UI Components: React Native Paper

## Installation

Follow these steps to set up the Aora project locally:

1. **Clone the repository**
   ```
   git clone https://github.com/yusrilprayoga-code/aora_react_native.git
   cd aora_react_native
   ```

2. **Install dependencies**
   ```
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory and add necessary environment variables:
   ```
   API_URL=your_backend_api_url
   ```

4. **Run the application**
   For iOS:
   ```
   npx react-native run-ios
   ```
   For Android:
   ```
   npx react-native run-android
   ```

Make sure you have Xcode (for iOS) or Android Studio (for Android) installed and properly configured.

## Usage

To use the Aora video sharing app:

1. **Sign Up/Login**: 
   - Create an account or log in to access all features.

2. **Browse Videos**: 
   - Explore trending videos on the home screen.
   - Use the search bar to find specific content.

3. **Watch Videos**:
   - Tap on a video thumbnail to watch.
   - Adjust video quality as needed.
   - Like, dislike, or comment on videos.

4. **Upload Videos**:
   - Tap the "Upload" button.
   - Select your video file from your device and add title, description, and tags.
   - Wait for processing to complete.

5. **Interact with Content**:
   - Subscribe to channels you enjoy.
   - Leave comments on videos.
   - Reply to other users' comments.

6. **Manage Your Channel**:
   - View your uploaded videos.
   - Check your subscriber count and video analytics.

7. **Customize Your Experience**:
   - Update your profile information and avatar.
   - Adjust account settings and notifications.

## Credits

This project is made possible thanks to the following technologies and resources:

- [React Native](https://reactnative.dev/) - A framework for building native apps using React
- [Node.js](https://nodejs.org/) - JavaScript runtime built on Chrome's V8 JavaScript engine
- [Redux](https://redux.js.org/) - A Predictable State Container for JS Apps
- [React Navigation](https://reactnavigation.org/) - Routing and navigation for React Native apps
- [React Native Paper](https://callstack.github.io/react-native-paper/) - Material Design for React Native

Special thanks to the open-source community and all contributors who have helped shape this project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

MIT License

Copyright (c) 2024 [Aora App]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
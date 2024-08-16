# Can Read - Braille to Speech Application
# Project Overview
"Can Read" is a mobile application designed to assist visually impaired individuals by converting Braille text into audible speech. Using a mobile camera, the app scans Braille characters and translates them into spoken words in real-time. This project integrates AI and image processing techniques to provide an accessible reading experience for the blind.

# Technologies Used
- **Programming Language:** Python
- **Mobile Development:** Flutter, Android Studio
- **Libraries & Tools:**
  - **imutils:** For image processing and transformations.
  - **imageio:** For reading and writing images.
  - **playsound:** For playing the audio output.
  - **gTTS (Google Text-to-Speech):** For converting text into speech.
  - **OpenCV:** For image processing and contour detection.
  - **Matplotlib:** For displaying images and visual data.
# Features
- **Braille Scanning and Recognition:** The app uses the mobile camera to capture images of Braille text and processes the images to recognize the Braille patterns.
- **Real-time Speech Conversion:** Converts the recognized Braille characters into speech using the Google Text-to-Speech (gTTS) library.
- **Error Handling:** The app can manage various image qualities and handle common issues in image recognition through preprocessing techniques.
- **User-friendly Interface:** Designed with an intuitive interface to ensure ease of use for visually impaired users.
# Usage
- Launch the App: Open the "Can Read" application on your mobile device or run the script on your local machine.
- Scan Braille Text: Use your device's camera to capture an image of the Braille text.
- Listen to the Text: The app will process the image, recognize the Braille characters, and convert the text into speech. The audio output will be played automatically.
# How It Works
- **Image Acquisition:** The app captures an image using the mobile camera.
- **Preprocessing:** The image is converted to grayscale, blurred to reduce noise, and edges are detected to find the contours of the Braille dots.
- **Contour Detection:** The app identifies the individual Braille dots by analyzing the contours.
- **Braille Character Recognition:** The recognized patterns are matched against a Braille alphabet to identify the corresponding letters.
- **Text-to-Speech Conversion:** The recognized text is converted into speech using the Google Text-to-Speech (gTTS) API, and the audio is played back to the user.
# Future Enhancements
- **Multi-language Support:** Extend support for Braille in different languages.
- **Improved Accuracy:** Enhance the image processing algorithms to improve Braille character recognition accuracy.
- **Offline Mode:** Implement an offline mode for areas with limited internet access.

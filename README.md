# Railway Indoor Navigation Through ARCore

[![ARCore](https://img.shields.io/badge/ARCore-enabled-brightgreen)](https://developers.google.com/ar) 
[![Android](https://img.shields.io/badge/platform-android-blue)](https://www.android.com/)
[![License](https://img.shields.io/badge/license-MIT-green)](./LICENSE)

## Overview

The **Railway Indoor Navigation through ARCore** project is an innovative mobile application designed to assist passengers in navigating through large railway stations using **Augmented Reality (AR)**. Leveraging Google’s **ARCore**, this app provides real-time guidance and turn-by-turn directions, overlaying AR elements onto the real-world environment to help users find ticket counters, platforms, restrooms, and other key locations within a railway station.

## Features

- **Augmented Reality Navigation**: Provides real-time AR-based path guidance within railway stations.
- **Indoor Location Mapping**: Detects user location using GPS and AR markers to ensure accurate positioning.
- **Dynamic Path Updates**: Updates navigation path based on the user’s current position and selected destination.
- **POI (Points of Interest)**: Displays important locations like platforms, ticket booths, restrooms, shops, and restaurants.
- **User-friendly UI**: Intuitive interface with AR elements like arrows and markers guiding the user visually.

## Screenshots

| AR Navigation       | Points of Interest |
|---------------------|--------------------|
| ![AR Navigation](./screenshots/ar_navigation.png) | ![POI](./screenshots/poi_list.png) |

## Installation

To build and run the application, follow the instructions below:

### Prerequisites

- Android Studio (latest version)
- Android device with ARCore support
- Minimum SDK: 24 (Android 7.0 Nougat)

### Steps

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/railway-indoor-navigation-arcore.git
    cd railway-indoor-navigation-arcore
    ```

2. Open the project in **Android Studio**.

3. Build the project and run it on a **compatible Android device**.

4. Install the **ARCore** service from the Google Play Store, if not already installed.

## Usage

1. Open the app and point your device’s camera towards any AR markers or visual cues placed within the station.
2. Select your destination from the available Points of Interest (POI), like "Platform 3" or "Ticket Counter."
3. Follow the AR arrows and instructions that appear on your screen to reach your destination.

## Technologies Used

- **ARCore**: To enable AR functionality and object placement within the real world.
- **Android SDK**: For developing the mobile application.
- **Firebase**: (Optional) For storing POI data and location information.
- **OpenCV**: (Optional) For image processing and detecting station-specific AR markers.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Add some feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.

## Acknowledgements

- **Google ARCore** for providing the core augmented reality framework.
- **OpenCV** for optional image processing functionalities.
- **Firebase** for cloud data storage and retrieval.
- Thanks to contributors and testers for feedback and support!

---

Feel free to open issues if you encounter bugs or have feature requests.


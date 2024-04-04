# news_app

![Flutter News App](https://github.com/mulw/CyberNews/blob/main/screenshots/newsApp.png)

# News App
News App developed with Flutter and API from [News API](https://newsapi.org)

## Usage
To run the Flutter News App on your machine, follow these steps:

*Prerequisites:*

Flutter SDK installed on your machine. You can download it from the Flutter website.
Android emulator, iOS simulator, or a physical device connected to your machine for testing.

Steps to run the app:

Clone the repository:

*git clone https://github.com/mulwa/CyberNews.git*

Navigate to the project directory:

*cd CyberNews*

Open the project in your preferred code editor:

*code .*
Replace code . with the command for opening your code editor if you're not using Visual Studio Code.

Update API key:
Open the file lib/repository/news_api.dart and replace YOUR API KEY in the keyApi variable with your own API key obtained from News API.

Get dependencies:
Run the following command to get the required dependencies:

*flutter pub get*

Run the app:
Use the following command to launch the app on your connected device or emulator:

*flutter run*
This command will compile the Flutter code and launch the app on your selected device.

## Requirements:
Flutter version: Ensure that your Flutter SDK is up to date. You can check your Flutter version by running:

*flutter --version*
Android Studio or Xcode: Make sure you have Android Studio installed with the necessary Android SDK components or Xcode installed for iOS development.

API Key: You need a valid API key from News API to fetch news data. Replace YOUR API KEY in the news_api.dart file with your own API key.
## Technology
1. http<br />
This package contains a set of high-level functions and classes that make it easy to consume HTTP resources. It's multi-platform, and supports mobile, desktop, and the browser.
2. MVVM Architecture<br />
Model-View-ViewModel (MVVM) is a software design pattern that is structured to separate program logic and user interface controls.
3. Url Launcher<br />
Flutter plugin for launching a URL in the mobile platform. Supports iOS and Android.
4. JSON Serializable<br />
Automatically generate code for converting to and from JSON by annotating Dart classes.
5. card_swiper<br />
Swiper/Carousel for flutter, with multiple layouts, infinite loop. Compatible with Android & iOS.

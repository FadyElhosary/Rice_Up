# Rice Up

A Flutter mobile application that brings together cloud services, data access, visualization, and machine-learning capabilities.

![Flutter](https://img.shields.io/badge/Flutter-Mobile%20App-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-Programming%20Language-0175C2?logo=dart&logoColor=white)
![AWS Amplify](https://img.shields.io/badge/AWS-Amplify-FF9900?logo=amazonaws&logoColor=white)
![GraphQL](https://img.shields.io/badge/API-GraphQL-E10098?logo=graphql&logoColor=white)
![PyTorch](https://img.shields.io/badge/ML-PyTorch%20Mobile-EE4C2C?logo=pytorch&logoColor=white)

## About the project

Rice Up was built as a Flutter application with a backend-connected architecture. It combines Flutter and Dart with AWS Amplify, Cognito, GraphQL, and DataStore, and also includes charting, connectivity handling, image selection, and PyTorch Mobile support.

The interesting part of the project is how these pieces work together in one application: the UI communicates with application state, the application connects to backend services, and data can be presented visually or used by an ML component.

## Architecture

![Rice Up Architecture](docs/architecture.svg)

The diagram provides a quick view of the main technologies before diving into the source code.

## Main technologies

| Area | Technology | Purpose |
|---|---|---|
| Mobile application | Flutter / Dart | Cross-platform application development |
| State management | Provider | Keep application state organized |
| Authentication | AWS Amplify / Cognito | User authentication and identity |
| API | GraphQL | Backend communication |
| Data | Amplify DataStore | Data access and synchronization |
| Machine learning | PyTorch Mobile | On-device model inference |
| Visualization | Syncfusion Charts | Display application data |
| Connectivity | connectivity_plus | React to network changes |
| Images | image_picker | Select images from the device |

These technologies are reflected in the project's dependency configuration. fileciteturn9file0

## What this project demonstrates

- Building a mobile application with Flutter
- Managing shared state with Provider
- Connecting an application to AWS services
- Working with GraphQL APIs
- Handling application data and synchronization
- Displaying information through charts
- Detecting connectivity changes
- Integrating mobile machine-learning capabilities

## Running the project

### Requirements

- Flutter SDK
- Dart SDK compatible with the project
- Android Studio or Xcode
- Android/iOS emulator or physical device
- The required AWS Amplify configuration for cloud features

### Installation

```bash
git clone https://github.com/FadyElhosary/Rice_Up.git
cd Rice_Up
flutter pub get
flutter run
```

Some cloud features depend on the original Amplify/Cognito environment. Credentials and other environment-specific values should be configured locally and not committed to Git.

## Project notes

This is a practical application project rather than a step-by-step Flutter tutorial. Some integrations reflect the environment in which the application was originally developed, so reproducing the complete application may require additional configuration.

## Author

**Fady Elhosary**  
Data Engineer

- LinkedIn: [Fady Elhosary](https://www.linkedin.com/in/fady-elhosary-68064a338/)
- Email: fadymohamed1@gmail.com

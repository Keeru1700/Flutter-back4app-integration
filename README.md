# Flutter-back4app-integration
ToDo app

Author: Keerthana Arangi
Subject: Cross Platform Application Development
BitsID: 2022MT93573
Assignment : Flutter App with Back4App Integration

 
 keyApplicationId = 'gmYqNWLUCDDJ3laM7WwoyDAx8TD0MqvFku2a4CHx'; keyClientKey = 'GGIekuUEpZ33IdvthlIWoHyUgbRJCYShiRglYMsB'; ParseServerUrl = 'https://parseapi.back4app.com';

Class: Task_Database

Flutter: pubspec.yaml dependencies: environment: sdk: '>=2.12.0 <3.0.0'

parse_server_sdk_flutter: ^7.0.0 intl: ^0.18.1

Scope:
Step 1: Set Up Back4App
Sign up for a Back4App account (if not already done). Create a new Back4App app. Create a class in Back4App named Task with columns title (String) and description (String).

Step 2: Flutter Setup
Create a new Flutter project. Add the required dependencies to your pubspec.yaml file. Initialize the Parse SDK in your Flutter app.

Step 3: Task List
Create a screen in your Flutter app to display a list of tasks. Implement a function to fetch tasks from Back4App using the Back4App API. Display the tasks in a list view with titles and descriptions.

Step 4: Task Creation (10 points) Create a screen for adding new tasks. Implement functionality to create and save tasks to Back4App. Verify that newly created tasks appear in the task list.

Step 5: Task Details
Add a feature to view task details when a task is tapped in the task list. Display the title and description of the selected task.

Step 6: Bonus Features
Add a feature to edit and update existing tasks. Implement a feature for task deletion.

Build dependencies with "flutter pub get" Parse and Execute with "flutter run"

Github Repo & Available Artifacts: https://github.com/Keeru1700/Flutter-back4app-integration

main.dart
pubspec.yaml

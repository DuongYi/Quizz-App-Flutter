# flutter_1st_app

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
# Quizz-App-Flutter

State ---> Satte
App State ---> App Wide State
Widget State ---> Component State



# Flutter
## Stateless Widget
Can pass in data from outside into the stateless widget through the constructor of that class, so of the widget class. And this data can change and actually Flutter would rebuild that widget when that external data changes.
But inside of the widget class, the data will never change, we can only receive new data from outside and that will basically rebuild the widget.

## Stateful Widget
Stateful widget also has a build method that builds a widget and that renders a UI therefore but here, we can also get our input data, so data passed in through the constructor of the widget.
But we also can have some internal state and that's the core thing here and this widget will get re-rendered, so the user interface willo get updated by Flutter whenever either that external, that input data changed or when our internal state changed.
### That's the core difference 
### _ turns from a public into private class

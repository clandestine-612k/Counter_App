# Counter_App

A new Flutter project.
A basic Counter App using Flutter Bloc as well as Cubit


## Getting Started

This project is a starting point for a Flutter application using BLOC.

##What is Bloc?
Flutter Bloc is one of the state management in a flutter. We can use it to handle all the states which we want to perform in our flutter applications.

Bloc is the best and simple way to do state management. We can easily add any type of change to the Flutter application. You can easily learn the concept, no matter what’s your level. You can add this dependency to your project and use it.

Bloc is a design pattern created by Google to help separate business logic from the award layer and authorize a developer to exploit code more efficiently.

A state management library called Bloc was created and maintained by Felix Angelo. It assists developers utensil the Bloc design pattern in their Flutter application. It means that a developer must recognize the state of an app at some time. There should be something on the screen for every interplay with the app to let users know what the incident is incident.

##what is a Cubit?
Cubit is a minimal version or a subset of the BLoC design pattern that simplifies the way we manage the state of an application. To do so, it substitutes the use of events (used in Bloc) with functions that rebuild the UI by emitting different states on a stream.

A Cubit is similar to Bloc but has no notion of events and relies on methods to emit new states. Every Cubit requires an initial state which will be the state of the Cubit before emit has been called. The current state of a Cubit can be accessed via the state-getter.

##Bloc VS Cubit:
The only difference is in the syntax of emitting state. Where Cubit uses emit(event) syntax, State Notifier uses state = event. Bloc on the other hand relies on events instead of functions to get feedback from UI to Cubit. The major difference between Bloc and Cubit is, “Bloc is Event-Driven and Cubit is not Event-Driven”. In Bloc, we can override “onTransition” and check how these events are coming and how these states change. And in Cubit, we call functions to send these states, with the help of these functions we can track the state. We use the “onChnaged” function in Cubit.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

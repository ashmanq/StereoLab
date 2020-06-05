# Java Stereo App
A Java app to model a stereo system made up of seperate components.

## Objectives
* Use abstract classes
* Use abstract methods
* Use interfaces
* Implement interfaces in classes
* Implement using TDD

## The app does the following
* Has an abstract Component class for all stereo components
* Has child classes of Component; Radio, CDPlayer, RecordDeck
* Has a Stereo class that has an array of Component classes
* Has an interface, IConnect, that is used to connect devices to the Stereo
* Has an MP3Player class which uses the IConnect interface to connect to a Stereo

# Simple-ConsoleUI-Toolkit
A simple toolkit for creating Console based UI in C#

Step one: Get a reference to the ConsoleUIManager

Step two: Create instances of ConsolePages

Step Three: Create instances of ConsolePageCollections and pack them with the ConsolePage instances
only one ConsolePageCollection is necessary, but one can create and use them to associate ConsolePages in a way that makes sence for their design

Step Four: Initialize the ConsoleUIManager instance with the ConsolePageCollections by calling its Initialize method

At this point the ConsoleUIManager will create the console based upon the first collection that it was fed in initialization

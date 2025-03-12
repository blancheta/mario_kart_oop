# mario_kart_oop

Create the classes for the following models: racer, kart, race

## Class: Racer
### Attributes:
name: The name of the racer (e.g., "Mario", "Luigi").

speed: The base speed of the racer. You can assign a default value like 5.

is_boosting: A boolean that indicates whether the racer is using a boost (e.g., True or False).
### Methods:
use_boost(): This method should change is_boosting to True and increase the racer's speed by 2.

stop_boost(): This method should change is_boosting to False and restore the racer's speed back to normal.

get_speed(): Returns the current speed of the racer, taking into account whether the racer is boosting.

## Class: Kart
### Attributes:
model: The model of the kart (e.g., "Standard Kart", "Pipe Frame").

color: The color of the kart (e.g., "Red", "Blue").
### Methods:
get_info(): This method returns a description of the kart's model and color.

## Class: Race
### Attributes:
racers: A list of Racer objects participating in the race.

track_length: The length of the race track (e.g., 100 meters).
### Methods:
add_racer(racer): Adds a Racer to the race.

start_race(): Simulates the race by looping through the racers and calculating their progress based on their speed. Print the progress for each racer.

declare_winner(): Determines which racer finishes first and prints their name (randomly found from the list of racers for the race).

# Magical_Arena
Magical Arena gamming application


# Magical Arena

## Description
The Magical Arena is a simple game where two players battle each other until one player's health reaches zero. Players take turns attacking and defending, rolling dice to determine the outcome of each attack.

## Components
The project consists of the following components:

- `Player`: Represents a player in the game with attributes such as health, strength, and attack.
- `Die`: Simulates rolling a die with a specified number of sides.
- `Arena`: Manages matches between players in the arena.
- `Game`: Manages the overall flow of the game, including starting matches and determining the winner.

## Setup
To run the game, follow these steps:

1. Ensure you have Java installed on your system.
2. Clone this repository to your local machine.
3. Compile the Java files using the following command:
`javac *.java`
4. Run the game using the following command:
`java Main`
5. Follow the prompts to input the attributes of the players and the number of sides on the dice.


## Sample Output

Here's a sample output of the game:

Starting the game...  
Player A vs Player B  
Player A attacks Player B with roll 5  
Player B defends with roll 2  
Player B takes 30 damage. Player B's health: 70  
...  
Game Over  
Player A's final health: 20  
Player B's final health: 0  
Player A wins!  


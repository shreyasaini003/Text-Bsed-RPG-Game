# Text-Based RPG Game

This project is a simple text-based RPG (Role-Playing Game) developed in Python. The game allows players to engage in a battle against a randomly generated enemy, where they can choose to attack or heal in each turn. The objective is to defeat the enemy without losing all your health.

## Features

- **Randomized Gameplay:** Each game features an enemy with a randomly determined health value, making each playthrough unique.
- **Action Choices:** Players can choose to attack the enemy or heal themselves during battle.
- **Simple and Engaging:** Easy to play with straightforward mechanics, making it fun for anyone to try.

## Technologies Used

- Python
- `random` module for generating random values

## How to Play

1. Run the game:

   ```bash
   python main.py
   ```

2. Follow the on-screen prompts:
   - Enter your player name.
   - Engage in a battle with a randomly generated enemy by choosing your actions.
   - You can either attack the enemy or heal yourself during each turn.

3. The game ends when either the player's health or the enemy's health reaches zero.

### Example Gameplay

```
Welcome to the Text-Based RPG Game!
Enter your name: Alex
Hello, Alex! Let's begin your adventure.

You encountered an enemy!

Your Health: 100
Enemy's Health: 78

Choose your action (attack/heal): attack
You attacked the enemy and dealt 15 damage!
The enemy attacked you and dealt 8 damage!

Your Health: 92
Enemy's Health: 63

Choose your action (attack/heal): heal
You healed yourself and restored 20 health!
The enemy attacked you and dealt 12 damage!

...

Congratulations! You defeated the enemy!
```


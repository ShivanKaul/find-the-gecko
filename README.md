# The Gecko (party game)

An online version of [The Chameleon](https://en.wikipedia.org/wiki/The_Chameleon_(party_game)) party game where one player is secretly designated as the **Gecko** while everyone else gets the same secret word. At the end, everyone must guess who the Gecko is.

The game is designed to be played IRL by a minimum of 2 players.

## How It Works
1. **Pick the Number of Players** – Each round, you specify how many players are in the game.  
2. **Randomly Generate the Secret Word & Gecko** – The game chooses a word from `words.txt` (newline-separated list of possible words) and secretly designates one player as the Gecko.  
3. **Pass the Device Around** – One by one, each player clicks "Reveal" to get their word. One person will be randomly designated as the Gecko and get either a fake word or just be told that they're the Gecko, depending on how the game mode (toggleable).
4. **Accuse and Reveal** – Once everyone has checked their role, it’s time to figure out who’s faking it.

## Developer Instructions
1. **Edit `words.txt`** (Optional)  
   - Replace or expand the list of words to suit your game. Each line should be one word.
3. **Play the Game**  
   - Enter how many players are in your group.  
   - Press **Start Game**.  
   - Pass the device around for each player to see their role.  
   - Once everyone has seen their role, guess who the Gecko is!

## Notes
- This game has **no backend**. Everything is stored in memory until the page refreshes or you start a new game.  
- The game is designed for **in-person** gatherings, passing a single device.  

Enjoy *Gecko*! Feel free to customize or extend it. 

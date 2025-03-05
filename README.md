# 🦎 Find the Gecko (party game)

Variant of [The Chameleon](https://en.wikipedia.org/wiki/The_Chameleon_(party_game)) party game where everyone gets the same word, except for one player who is designated as the **Gecko**. People must guess who the Gecko is.

Play the game [here](http://shivankaul.com/find-the-gecko/).

The game is designed to be played IRL by a minimum of 2 players.

## How It Works
1. **Pick the number of players**: Each round, you specify how many players are in the game.  
2. **Generate secret word**: The game chooses a word from `words.txt` (newline-separated list of possible words) and secretly designates one player as the Gecko.  
3. **Choose the Gecko**: One by one, each player clicks "Reveal" to get their word. One person will be randomly designated as the Gecko and get a fake word. Alternatively, they can just be told that they're the Gecko and not get a fake word, depending on the game mode (toggleable via `Gecko knows?` checkbox).
4. **Bluffing time**: Every player says **one word** out loud that is related to the word they got on the screen.
4. **Vote out** – Once everyone has checked their role, it’s time to figure out who the Gecko is. Players vote on whose answer was most sus.

## Notes
- This game has **no backend**. Everything is stored in memory until the page refreshes or you start a new game.  
- The game is designed for **in-person** gatherings, passing a single device.  

Enjoy *Find the Gecko*! Feel free to customize or extend it 🦎

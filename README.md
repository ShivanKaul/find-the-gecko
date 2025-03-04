**Word Bluff** 

A simple “offline pass-and-play” party game similar to [The Chameleon](https://en.wikipedia.org/wiki/The_Chameleon_(party_game)) where one player is secretly designated as the “Bluffer” while everyone else gets the same secret word. Each player sees their role for four seconds before it disappears. At the end, everyone must guess who the bluffer is.

## How It Works
1. **Pick the Number of Players** – Each round, you specify how many players are in the game.  
2. **Randomly Generate the Secret Word & Bluffer** – The game chooses a word from `words.txt` and secretly designates one player as the Bluffer.  
3. **Pass the Device Around** – One by one, each player clicks “Reveal” to see if they’re the Bluffer or get the secret word. After 4 seconds, the display clears automatically.  
4. **Accuse and Reveal** – Once everyone has checked their role, it’s time to figure out who’s faking it.

## Project Structure
```
WordBluff/
  ├── index.html
  ├── words.txt
```

- **`index.html`** – The main HTML/JavaScript.  
- **`words.txt`** – A newline-separated list of possible words. You can swap this out with any list you prefer.

## Developer Instructions
1. **Edit `words.txt`** (Optional)  
   - Replace or expand the list of words to suit your game. Each line should be one word.
2. **Serve Locally (Recommended)**  
   - Some browsers block `fetch()` from local files. To avoid this, launch a simple local web server in the project folder.  
   - For example:  
     ```bash
     python -m http.server 8000
     ```
   - Then open [http://localhost:8000](http://localhost:8000) in your browser.
3. **Play the Game**  
   - Enter how many players are in your group.  
   - Press **Start Game**.  
   - Pass the device around for each player to see their role.  
   - Once everyone has seen their role, guess who the Bluffer is!

## Notes
- This game has **no backend**. Everything is stored in memory until the page refreshes or you start a new game.  
- The game is designed for **in-person** gatherings, passing a single device.  

Enjoy *Word Bluff*! Feel free to customize or extend it. 

![Wordle+](https://i.imgur.com/5DdKI5G.png)
<div align="center">
  <a href="https://playwordleunlimited.github.io" ><img src="https://github.com/MikhaD/wordle/workflows/Publish/badge.svg?branch=main" alt="Publish workflow"/></a>
  <img src="https://img.shields.io/github/package-json/v/MikhaD/wordle" alt="GitHub package.json version" />
</div>

---
A recreation of the popular game [Wordle](https://www.playwordle.uk/) by Josh Wardle (now purchased by the New York Times), with additional modes and features.
Hosted on GitHub pages [here](https://playwordleunlimited.github.io).

# Additional Features
- Wordle Unlimited offers an enhanced version of the popular Wordle game with several unique features, including:
- Unlimited Games: Unlike the original Wordle, which allows only one puzzle per day, Wordle Unlimited lets you play as many games as you want without waiting for the next day.
- Custom Word Length: You can adjust the length of the word (typically between 4 and 11 letters), making it more challenging or easier, depending on your preference.
- Difficulty Levels: Some versions offer multiple difficulty modes, where the number of guesses allowed can vary or the words become progressively harder.
- Streak Tracking: It often includes a streak counter to track how many consecutive games you've won, enhancing the competitive aspect of the game.
- Daily Challenges: While you can play unlimited games, there’s also the option to engage in daily challenges to compete with others or yourself over time.
- Colorblind Mode: This version often provides accessibility options like a colorblind mode that adjusts the color scheme to make it easier for colorblind players to distinguish correct and incorrect letters.
- Hints and Skips: Some versions of Wordle Unlimited allow hints or the option to skip particularly tough puzzles.
- Multiplayer Mode: You can challenge friends by generating and sharing a custom word or room code for competitive play.
- Words are chosen from the list of words at random instead of in sequence, and the solution is not stored in localStorage, making it harder to cheat. The seed for the random number is created from the date, ensuring that everyone gets the same random number, so people can still compare answers.
- When you complete a game the definition of the word is shown on the end of game modal.
- In addition to the other statistics, your average guesses and your losses are also displayed on the win modal.
- When the timer reaches 0 for a given game mode it changes into a refresh button instead of just staying at 00:00:00.
- When the timer reaches 0 for a given game mode a refresh button appears in the top left corner.
- A tips widget in the settings menu with useful information about the functionality of the game.
- Right clicking a submitted word on the board will tell you its definition.
- Right clicking a submitted word on the board will tell you how many possible words could have been played there, taking all previous information into account.
- Right clicking the row below the last submitted word will tell you how many possibilities there are taking all previous information into account.
- The game mode is reflected in the url, allowing you to share a game mode directly.
- You can share a link to a specific game number, allowing you to play historical games, and share specific rounds of the faster changing modes with your friends.
- You can access previous games from the settings menu by inputting a game number or link.
- Service worker which allows the game to be easily downloaded as a progressive web app and run offline.
- Give Up button.
- Wordle Unlimited keeps the same basic gameplay mechanics as the original, with letter-based logic puzzles, but adds flexibility and new challenges for a more customizable experience.

## Additional modes
The game mode can be changed by clicking WORDLE+ at the top of the screen or swiping the board in either direction.

**Hourly mode**: A new word every hour.

**Infinite mode**: A new word every time you refresh, for the true addicts.

# Technical details
This is written with Svelte in Typescript. This is my first Svelte project, and is intended as an exercise to help me learn and become proficient in Svelte. It also uses some basic scss for styling.

# Forking this project
Anybody is welcome to fork this repository and do what they like with it, provided they follow the accompanying license (GPL-3.0).
I would also appreciate if you could link back to this repository and credit me in your project.

Have fun :)


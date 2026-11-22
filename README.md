# Elgin117
Lodge Education

## Masonic Jeopardy
A black-and-gold Jeopardy-style quiz game for lodge education nights.
Open `index.html` in any browser (or host it with GitHub Pages) - no install needed.

- 6 categories x 5 clues, one hidden Daily Double, and a Final Question
- 2-4 teams, score tracking, 30-second think timer, sound on/off
- Game auto-saves, so a refresh will not lose the scores
- To change the questions, edit the `CATEGORIES` list near the top of the script in `index.html`
- Questions use public Masonic history, symbolism and lodge basics only

### Online play (up to 10 players)
1. On the big screen (laptop/TV), open the game and tap **Host an Online Game**. A 4-letter room code appears.
2. Players open the same page on their phones, tap **Join with a Room Code**, and enter the code and a name (or open the shared link, which fills in the code).
3. Tap **Start the Game**. The player in control picks clues from their phone, and the first player to tap **BUZZ** locks everyone else out. The host taps Right or Wrong, and a wrong answer reopens the buzzers for the remaining players.
- Players who refresh rejoin with the same name and keep their score.
- Connections run peer to peer through the free PeerJS cloud broker (`peerjs.min.js` is bundled in this repo). The host screen must stay open for the whole game.

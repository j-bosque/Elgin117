# Elgin117
Lodge Education

## Masonic Jeopardy
A Masonic-blue Jeopardy-style quiz game for lodge education nights, played by up to 10 people on their own phones.
Open `index.html` in any browser (or host it with GitHub Pages) - no install needed.

1. On the big screen (laptop/TV), tap **Host a Game**. A 4-letter room code appears.
2. Players open the same page on their phones, tap **Join with a Room Code**, and enter the code and a name (or open the shared link, which fills in the code).
3. Tap **Start the Game**. The player in control picks clues from their phone, and the first player to tap **BUZZ** locks everyone else out. The host taps Right or Wrong, and a wrong answer reopens the buzzers for the remaining players.

- 6 categories x 5 clues, one hidden Daily Double, and a Final Question
- Players who refresh rejoin with the same name and keep their score
- Connections run peer to peer through the free PeerJS cloud broker (`peerjs.min.js` is bundled). The host screen must stay open for the whole game.
- To change the questions, edit the `CATEGORIES` list near the top of the script in `index.html`
- Questions use public Masonic history, symbolism and lodge basics only

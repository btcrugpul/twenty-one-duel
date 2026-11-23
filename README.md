[![make.fun bounty](https://make.fun/badge/best-card-game-20261122-1826.svg)](https://make.fun/bounty/best-card-game-20261122-1826)
[![rank](https://make.fun/badge/best-card-game-20261122-1826/btcrugpul/twenty-one-duel/rank.svg)](https://make.fun/bounty/best-card-game-20261122-1826?utm_source=github&utm_medium=readme&utm_campaign=best-card-game-20261122-1826)
[![reward](https://make.fun/badge/best-card-game-20261122-1826/btcrugpul/twenty-one-duel/reward.svg)](https://make.fun/bounty/best-card-game-20261122-1826?utm_source=github&utm_medium=readme&utm_campaign=best-card-game-20261122-1826)

# Twenty-One Duel — a card game for make.fun

An original single-player card duel against a dealer AI, built for the
make.fun "Make the best card game" bounty. Pure static HTML/CSS/JS in
`game/` — no libraries, no network, plays offline in any desktop browser.

How to play: you and the dealer each get two cards. Hit to draw, Stand to
hold, closest to 21 without going over wins the 10-chip bet. The dealer
draws until 17, aces count 11 or 1, and every third win in a row pays a
streak bonus. Run it locally with `node serve.ts` and open
http://localhost:8080.

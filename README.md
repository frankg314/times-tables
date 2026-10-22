# Times Table Quest

A single-file times tables app for a young learner. Open `index.html` in any browser; no build or install.

- **Learn**: each fact drawn as rows of dots, a skip-counting strip, and a trick for each table.
- **Practise**: 10 questions from the chosen tables. A wrong answer shows the dot array, then the fact comes back 3 questions later.
- **Beat the Clock**: 60 seconds, best score kept per table set.
- **My Progress**: a square turns green after 3 correct answers in a row, each within 10 seconds, so counting on fingers doesn't count as knowing it. 3 × 7 and 7 × 3 count as one fact.
- **Four in a Row**: a board game against Robo, based on the classroom "Product Game". Two clips sit on the numbers 1–9. Each turn a player moves one clip and claims the product on a 6×6 board of answers; tapping the wrong square loses the turn. First to four in a row wins. Planning a move means working backwards from the square you want, which practises factors without feeling like a quiz. Robo has two levels: Friendly (a kid who looks for good moves wins about 80% of games in simulation) and Clever (blocks threats and looks one move ahead).
- **Fix my tricky facts**: appears on the start screen once something has been missed; a round drawn only from facts not yet fixed.
- Once a fact is familiar, practice sometimes asks for the missing number (? × 7 = 56), the first step toward division.

**Toon friends**: fan drawings, in the style of the official Dandy's World character poster, of 14 friendly Toons from the Roblox game (Dandy, Astro, Pebble, Shelly, Sprout, Vee, Poppy, Boxten, Tisha, Cosmo, Flutter, Toodles, Looey, Teagan). These are fan-made drawings for personal use, not official artwork.

- **Buddy**: the learner picks one Toon from their team to be their buddy. The buddy appears on every screen and talks in a speech bubble. On the start screen it says hello. In Practise and Beat the Clock it asks the question, cheers right answers and droops gently after a miss. In Learn it shares the trick, and in Four in a Row it plays on the learner's side against Robo. It also celebrates on the results screen.
- **Team**: Dandy, Astro, Pebble and Shelly are on the team from the start. The other ten join as stars add up, quickly at first and then a little further apart (3, 10, 18, 28, 40, 55, 70, 90, 115 and 145 stars). The first new friend arrives after just three right answers. Each new friend is announced after a round or game, never in the middle of a question. A locked friend shows as a silhouette with its star target, and a meter shows how many stars until the next friend joins. "Start progress again" also resets the team.
- The team stands along the bottom edge (one random friend hops up on each right answer and all of them jump after a good round), and team members appear on the start-screen mode cards.

Questions lean toward facts the learner has missed. Keyboard works throughout: digits, Backspace, Enter, Escape.
Progress is saved in the browser's localStorage on that device.

This is standalone and not part of the CCB/Home application.

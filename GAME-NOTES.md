# Fire Soccer: design notes

A game by Obin and Oyun. This file keeps what they decided, in their words, so every change we make stays true to their idea.

## The big idea
- Regular soccer. Fire is in the name because it sounds cool.
- The ball is a normal soccer ball.
- Monsters come down from the sky and attack the soccer team.
- Power-ups also fall from the sky. You touch one with your hand (finger) to get it.

## Levels
- **Level 1:** just soccer. Beat the other team by scoring more goals. Both teams have really good players, so it's hard.
- **Level 2:** monsters fall from the sky. Kill all the monsters AND beat the other team on goals to win.
- Monsters attack the soccer teams. They are not the other team. You never fight the other team, you only out-score them.

## Power-ups (fall from the sky in Level 2)
- Melee attack
- Fireball
- Laser gun (kills a monster)

## Picking a team
- Pick a country you like, then a team from that country.
- You can choose any team in the world, a great team or a bad team.
- **If you pick a bad team, you get a bonus really good player.**
- Players already exist in the game. You pick from them. You don't build characters.
- Each team shows **Power** (stars) and **Speed** (lightning bolts) on the team list. Added at Issac's request, and both are real: Speed changes how fast the team runs, and Power changes shot strength and goalie skill.

## Prizes (when you beat a monster)
- Small monster drops a **gold coin**. Collect it (run into it, or tap it) and your whole team **runs 30% faster for 5 seconds**.
- Big monster drops a **diamond** (worth 5 coins). It gives a **shield for 8 seconds** (monsters can't make your team dizzy), **wakes up any dizzy teammates**, and a **free power-up gift** lands nearby.
- Prizes drift toward you when you get close, and disappear after 14 seconds (they blink at the end).
- A coin counter shows on screen and on the final results screen.
- **Open question:** what should coins be used for? Issac asked. Ideas: spend 10 coins on a free power-up; save coins between games to unlock things; coins make a star rating at the end.

## Controls
- Field players: **W A S D** on a keyboard, or the big square at the bottom of the tablet.
  - Front: tap = shoot, hold = run forward
  - Left / Right / Back = move
- Goalies are controlled by hand too: front, left, right, back = catch (dive) that way.
- To control a different player, tap that player on the screen (or press Tab).
- Power-up: tap the falling gift with your finger, or run into it. Press the big FIRE button (or Space) to use it.
- **Auto-switch:** when the ball goes to another player on your team, you automatically control that player (a "YOU!" tag pops up). It won't switch if you already have the ball, and it waits a moment after any switch so it doesn't flicker. Requested by Issac.
- If nobody is pressing anything for a second, the selected player plays by himself so the team never stands still. (Added by Claude, not in Obin and Oyun's list. Ask them if they like it.)

## Win rule
Whoever scores the most goals wins. In Level 2 you must also beat all the monsters.

## What's in the first draft
- One file: `index.html`. Open it in a browser. Works on a tablet (portrait) and on a keyboard.
- 12 countries, 36 made-up teams (made-up names so we don't use real logos), 3 per country.
- Level 1 (90 seconds) and Level 2 (150 seconds, 12 monsters in 3 waves, a power-up every 11 seconds).
- Monsters make a player dizzy for a few seconds when they touch him. Nobody dies.
- Sounds are simple beeps made by the code.

## Still to ask Obin and Oyun
- Are the monsters too easy, too hard, too many?
- Do they want other power-ups? (shield, freeze, speed boost?)
- Should real player names and faces be in the game? (Real names and logos belong to other people, so for now we made them up.)
- Passing the ball? Throw-ins? Fouls? None of these are in yet.
- Longer matches? Tournament mode (win a few matches to get a trophy)?
- Better art and sound? Right now players are simple circles.
- Should fire show up more (burning goal, fire trail on a strong shot)?

## Known rough spots
- Balance (how hard each team is) is a first guess. Playing will tell us what to change.
- The ball bounces off the edge of the pitch. No throw-ins yet.

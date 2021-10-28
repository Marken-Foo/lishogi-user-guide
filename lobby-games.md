# Lobby and game creation

There are several ways to create a game on lishogi. You can create an open seek for a game that anyone can accept, or create an invitation to directly challenge someone to a game, whether they're a lishogi user or not. You can also challenge an AI to a game.


## Accept an open seek

In the lobby, you can see seeks created by other people looking for a game. The following information is displayed:

- The side the other person will play (a black circle is sente, white is gote, half is random.)
- The user looking for a game. Tip: hover over the name to get a tooltip showing more information about them.
- Their rating in the game mode they are looking for.
- The time control. **| indicates byoyomi, and + indicates Fischer increment.** For example, 0|10 is 10-second byoyomi shogi, 5+5 is 5-minute shogi with 5 second Fischer increment, and 3|0 is 3-minute sudden death shogi.
- Whether the game is rated or not, and the game mode (based on the time control)

You can filter the seeks you see by clicking on the gear icon at the top right.

You can also see all seeks in a graph format by clicking the icon in the top left. To revert to the normal view, click the icon in the top left again.

### Correspondence seeks

Clicking on the correspondence tab in the lobby will show you seeks by other people looking for a correspondence game. The time control displayed is the number of days the players will have to make each move.


## Create an open seek

To create a game offer anyone can see and accept in the lobby, click on the "Create a Game" button from the main page. The game creation dialog will appear, where you can choose your game options, time settings, and rating settings.

**(Note that choosing your side by clicking the shogi piece symbols will create your seek.)**

### Game options

- Variant: Only standard shogi is available for open seeks.
- Time control: Real-time is for games that finish in one sitting, while correspondence lets you play long games where you have several days to make each move.

### Time settings

#### Real-time settings

- "Minutes per side" is the initial time each player starts with.
- Byoyomi is the time limit for each move after a player uses all of their main time. If byoyomi is set to zero, a player will lose when they use all their main time.

Clicking on the triangle reveals more time control options.

- "Periods" is the number of times a player can let the byoyomi countdown run out before losing. This is similar to the NHK Cup. For example, 2 periods means the player loses after their main time expires and they let the byoyomi countdown hit zero for the second time in the game.
- Increment sets a Fischer increment. Each player gains this number of seconds to their main time after making each move.

Note that games using both byoyomi and increment at the same time cannot be rated. In such games, if a player is already in byoyomi, they will not gain any more time from the Fischer increment.

Setting both byoyomi and increment to zero creates a sudden death game, where the players only have their initial time, and will lose when they use all of it.


#### Correspondence settings

If creating a correspondence game, the time chosen is simply the number of days per move. Each player will have this number of days to make each of their moves. Correspondence games can last months, but allow players to think and play moves at their own pace.


### Rating options

- Casual/rated: Whether or not the game result will affect the players' ratings.
- Rating range: Only players in this range will be able to see and accept your seek.
- Side: You can choose which side you play. Black is sente, white is gote, and the middle option gives you a side at random.

**Choosing your side by clicking the shogi piece symbol will create your seek.** You're done! Your seek is now visible in the lobby. Leave your browser tab open while you wait for an opponent. When someone accepts it, you'll automatically go into the game.

To cancel your seek, simply click on your seek yourself.


## Create a game invitation

To create a private invitation to a game, choose "Play with a friend" from the main page. You can then challenge a lishogi user directly, or send a link to the invitation to anyone else, even if they are not a lishogi user.

The dialog is the same as for creating a lobby seek, but this time under Variant you can choose "From Position". This lets you start a game using one of the **preset handicaps**, or from **any position you like** from an SFEN string.

When choosing the side you play, **black is sente/shitate (handicap receiver), and white is gote/uwate (handicap giver)**.

After creating your seek, you'll go to a waiting page. From here, you can choose a lishogi user to challenge directly, or you can copy the provided URL to send to whomever you want to challenge, even if they're not registered on lishogi.

### Tip: Shortcut to challenge a user

If you hover over a user's name and a tooltip appears, you can click the crossed swords icon to challenge them directly. This opens the game creation dialog, and when done it will send the user a challenge notification that they can accept.


## Play against the AI

You can play against AI of different strengths on lishogi by clicking the "Play with the computer" button on the main page. The game settings options are the same as for creating a game invitation above.

The games are unrated, and they will appear in your game history for you to analyse or download later.


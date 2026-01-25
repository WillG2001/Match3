# Gem Blast

2026 Will Giard

Coded using GPT-5.2

Based on gameplay concepts from PopCap Games and King

## What is Gem Blast?

Gem Blast is a "Match-3" puzzle game (think PopCap's "Bejeweled" and King's "Candy Crush"). I created it as a fun, weekend "vibe-coding" project with the goal of replicating one of my favorite childhood game genres.
It is playable in your browser on both mobile and computer (though it's a much better gameplay experience on a computer).

The game features three game modes: Survival (the main way to play), Peaceful (an endless mode with no danger),
and Time Attack (fast-paced, timed gameplay).

## The Basics

Each game mode features the same core gameplay mechanics. At the start of a game, the 8x8 game board will fill with gems of seven different colors. The goal is to align three or more of the same color gem pieces in a
horizontal or vertical line. A move consists of clicking one piece, then clicking an adjacent piece (to the left, right, up, or down, NOT diagonal). Doing so swaps the position of these two pieces as long as it leads to
a match of three or more gems. If the move is invalid, nothing happens and the move is not counted.

When a match is made, the gems are cleared from the board, allowing the above pieces to fall down into place and new pieces
to drop in from the top of the board. Points are earned for successful matches. The base scoring is simple: 10 points per cleared gem. Making a match will sometimes cause more matches to form as pieces fall into new positions.
This is called a combo. Points from combos are multiplied at a rate respective to the number of combos created from a single move.

In the event that there are no more possible moves, the pieces on the board will shuffle so that more moves can be made.

At the top of the board, the game tracks the player's score, overall total number of moves, and number of combos from the current move.

## Special Gems

Matching more than three gems together creates a Special Gem of respective color. Here is a list of the different Specials that can be created, how to make them, and their powers.

### Flame

When four gems are matched together in a line, a Flame is created. Matching a Flame causes it to detonate, clearing the eight surrounding pieces.

### Star

When five or more gems are matched together in a "T", "L", or "cross" shape, a Star is formed. Matching the Star will clear out its entire row and column.

### Hyper

When five gems are matched in a line, a rainbow Hyper piece is formed. When a Hyper is swapped with a gem, it clears all pieces of that gem's color.

It's very rare, but if two Hypers are swapped with each other, the
entire board is cleared.

### Sun

In the extremely rare event that six or more gems are matched in a line, a Sun will be created. When matched, a Sun not only clears its row and column, but the two adjacent rows and the two adjacent columns as well.

## Obstacles and Danger Pieces

There are several obstacles and Danger Pieces that can sometimes appear depending on the game mode. Here is a list of them and what they do.

### Rocks

Rocks are obstacles that spawn from the top of the board. A rock can be swapped with another gem (as long as it leads to a valid gem match), but it itself cannot be matched. Having three or more rocks in a line or formation does nothing.
Instead, rocks need to be destroyed by Special Gems. A Flame, Star, Hyper (when swapped with a rock or another Hyper), or Sun can clear rocks. When destroyed, a rock gives a random amount of points in the range of 25-100.

### Locks

Locks can sometimes appear on normal gems already on the board. When this happens, a notification appears at the bottom of the screen. Locked gems cannot be swapped and are stuck in place, except they can still fall down. Locks will only appear
on ordinary gems. They will not appear on specials, rocks, or bombs. When a lock is cleared via a match or Special, the player is awarded with 25 extra points.

### Bombs

Bombs can drop in from the top of the board. Each bomb has a color that corresponds to one of the seven gem colors. Bombs also have a counter that displays the number of moves remaining until the bomb explodes. If the bomb
is not matched or destroyed via Specials by the time its counter reaches zero, it explodes and the player's game ends. Clearing a bomb awards the player with 50 points.

### Skulls

A Skull is a dangerous type of bomb that appears on a normal gem, much like a lock. It cannot be swapped or matched. The player has 25 moves to destroy it with a Special before it explodes. If the skull is not cleared before the counter
reaches zero, it's game over. Destroying the skull will award the player with 500 points. There can only ever be one skull on the board at any given time.

## About Modes

Here is more information about the three game modes.

### Survival

The main way to play. It features all obstacles and Danger Pieces. The goal is to score as many points as possible before any bombs or skulls reach zero.

The player's current score determines what obstacles and Danger Pieces can appear. The spawn requirements are as follows:
- Bombs can appear from the start.
- Rocks begin appearing at 2,000 points.
- Locks begin appearing at 3,000 points.
- Skulls begin appearing at 10,000 points.

Additionally, the starting number of moves for bomb counters gradually decreases as the player scores more points. At the start of the game, bombs will start at 20 moves, but for every 1,000 points, that number is 1 lower.
However, the bombs will never start lower than 7 moves.

The game has a "leaderboard" for Survival Mode that tracks the ten highest scores on the device.

### Peaceful

An "endless" mode where no bombs, skulls, or locks appear. Rocks can still spawn from the beginning of the game, however. Peaceful Mode is a good place to practice making matches and is perfect for beginners or players who prefer
a less stressful experience.

### Time Attack

The player is given five minutes to score as many points as possible. No locks or skulls appear, but rocks and bombs can spawn from the beginning of the game. Bombs always start with a counter of 20 moves in this mode. The game can still
end before the timer expires if a bomb reaches zero.

The game has a "leaderboard" for Time Attack Mode that tracks the ten highest scores on the device.

## Tips

Prioritize getting rid of bombs as quickly as possible. If you can match one, do it right away! You want to avoid letting them fall to the bottom where it's harder to match them.

In Survival, try to keep as many specials on the board as possible. They can really help with clearing bombs when there are no gems of the bomb's color near it, and are your only line of defense against Skulls.

In Time Attack, you typically want to use Specials as soon as you can. You don't get points for them if they're left on the board when the timer expires. However, it's good to keep a few around for those hard-to-reach bombs.

If there are no corresponding colors for a bomb near it, try making matches to drop it down to where there are. Or make matches above it to try and get new gems of the right color to fall into place.

As much as possible, avoid making matches on the left and right edges of the board. Bombs can drop in and will be harder to match when they're stuck on the side of the board.

Try to clear rocks and locks whenever possible. When they start piling up, they tend to make it a lot harder to deal with bombs. However, the chances of getting a shuffle are higher with more rocks and locks, and a shuffle can
sometimes help.

You always have 25 moves to get rid of a Skull. If possible, try to keep it near the center of the board and away from the bottom. It's much easier to get rid of it that way.

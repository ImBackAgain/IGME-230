# Powers: Of the number 2, I mean
## I. High concept
Yeah, I'm using the template pretty exactly.

[2048](2048.com)'s many variations include hexagonal and triangular ones &ndash; but even Tri2048 kept me engaged only for so long. Hence, Powers! 2048 for short attention spans.

## II. Genre
Down to the numbering style in the headings.

The classic 2048 is part strategizing, part luck. This version is action! Random powerups with time limits, combined with mechanics peculiar to triangular 2048, will make this game more of a think-on-your-feet game &ndash; like a puzzle game but faster-paced. It's very much a casual game, meant to keep the brain awake while waiting for the next class to begin, or the bus ride to end. Oh, no, why am I describing Candy Crush?

## III. Platform
Given the gameplay style, it should be playable on mobile. No reason to exclude computers, though - handling them is usually fairly easy. So universal.

## IV. Story
None whatsoever.

High scores are player motivation. The games run until the board fills up or until the number 65,536 is reached &ndash;
which should happen fairly quickly in each game &ndash; so the goal is to maximize the score while working towards that.

## V. Esthetics
I'm thinking something easy on the eyes. There's not _too_ much to be gained from glorious artwork in this, so as long as colors match and
it looks comfortable, I'm happy. I'm thinking smooth gradients. Maybe try to go for a soothing feel.

I've made some MIDI-based music before, in which all my experience is in (ratherly poorly-composed) orchestral music, which loops.
Simple tunes that are relaxing in normal gameplay, and exciting when powerups are active. Maybe try and find some free sound effects.
Or maybe I'll just use musical ones.

## VI. Gameplay

### Mechanics
Controls in-game consist of choosing one of 6 directions to move the tiles on the board.

The player can undo upto 5 moves at a time - think of a word-processing or graphics with a tiny undo stack.
Performing moves after undoing some restores undo's until the max of 5 is reached again.

There are also three save states that can be saved to once, and loaded from twice each.
Each game will give the player 3 lives - when lives remain and the board fills up, the player can reset to one of the save states
(this does not use up one of the two reloads per state). The game is not meant to be unforgiving.

Powerups are randomly spawned after the player's score has increased by a certain amount since the last one ended
&ndash; a progress bar lets them keep track of when the next will show up. Or maybe not. I'm still thinking.
Perhaps specific sequences of actions create specific powerups on the board?

Alright, here's the powerups I've come up with so far:
1. New tiles spawned are bombs but still with numbers.
When they are flicked into a tile with the same number, instead of merging into the next power of 2, they are both destroyed.
2. Same as above, but without numbers &ndash; they will destroy any tile they are flicked into.
2. Similar to #2, but will merge into any tile to raise it to the next power instead.
2. Maybe something that destroys all tiles in a line?
2. A powerup allowing the player to move one tile to any empty space on the board (not timed).
2. That's all I've got for now.

Oh, and there will be a few buttons on-screen to rotate/reflect the entire board, in case the player wants a different angle on things.

### Controls
Desktop controls require a mouse. One can click-drag and release to flick all tiles in the corresponding direction.
Buttons and some of the powerups can be clicked, too.
Keyboard shortcuts exist for the flicks (A, W, E, D, X and Z) and rotator/reflector buttons, but clickable powerups need the mouse.

Mobile relies on swipes and taps to do everything the mouse can do. (No accelerometer.)

### "Onboarding"
I just learnt a new word! I think a tutorial menu that explains each control should be enough for that.
Since we're talking about casual gamers, I guess I'll have it auto-open for the first time someone plays it,
with a clear way to skip it.

Powerups should have a succinct description remain on-screen while it's active, and a menu somewhere detailing it, maybe
with tips on how to use it effectively.

### Player learning
Like I said, I'm still thinking of some things, but I think I'll design some powerups to have strategies that let them be used better in
some situations than others &ndash; especially if the player has some control over which ones appear when.
Maybe they can be spawned in conjuction, and used together.

## VII. Other
Didn't you say we don't need images for this milestone, Sean? I hope you did.

I have hacked together an incomplete version of the regular (triangular) 2048 in GameMaker before, so that's why I've made this choice.
:)

## VIII. About the dev
I'm a 2nd year Game Dev major by the name of Enan Munzar, which is obvious to you if you're my instructor or his TA.
I like coding and doodling and juggling. I have dabbled in making music, as I mentioned, and know what a fugue is (sorta).
Have you listened to Lugia's song from the second Pokémon movie?
I like that. [Here's a link](https://www.youtube.com/watch?v=ZqpXrDuLqE0), if you're interested.

Thanks for reading all that, if you did. <3

#game_design #project 

# Introduction

Kingstack is a game of perfect hidden information. You know exactly what cards your opponent has, but you don't know where they are on the board. Players create their armies and move their troops, stacks of face down cards, until they are ready to strike!
Attacking costs you information however, so don't give too much away.

The goal of the game is to move your troops, attacking the opponents troops to figure out where they've placed their Fool, and ELIMINATE IT!


# Game Pieces

Kingstack is played with a standard deck of cards. It can be played between 2-4 players. Each player takes one of the 4 suites of cards, A,2,3,4,5,6,7,8,9,10,J,Q,K, and a joker card to represent their "Fool", or "Flag."


# Army Setup

Players each take one suite and a Joker card as the Fool.

Players use their 14 cards to make 4 units or stacks with a different number of cards.
- 5 Stack
- 4 Stack
- 3 Stack
- 2 Stack
Each stack must be either in ascending order or descending order.

The Ace is low and high, so it can go on the top or the bottom of a stack

The Fool can be placed anywhere, but should be protected so it’s best to place it at the bottom of a stack.
<div style="page-break-after: always;"></div>

>[!Example]
>
| Position  | 5 Stack | 4 Stack | 3 Stack | 2 Stack |
| ------ | ------- | ------- | ------- | ------- |
| First  | King    | 9       | 3       | Jack    |
| Second | Queen   | 8       | 4       | Ace     |
| Third  | 10      | 7       | 5       |         |
| Fourth | 6       | 2       |         |         |
| Fifth  | Fool    |         |         |         |

Stacks 5,4, and 2 are all descending, going from high to low.
Stack 3 is ascending, going low to high.



>[!Error] Illegal Setup
>
| Position  | 5 Stack | 4 Stack | 3 Stack | 2 Stack |
| ------ | ------- | ------- | ------- | ------- |
| First  | 2       | 10      | 7       | Ace     |
| Second | King    | 9       | 9       | 5       |
| Third  | 3       | 8       | Fool       |         |
| Fourth | Queen   | Jack    |         |         |
| Fifth  | 4       |         |         |         |

Here each stack is out of order except for the 2 Stack.

<div style="page-break-after: always;"></div>


# Board and Troop Placement

Players each set up their troops in the $\perp$ formation seen below. There is no restriction on which stacks of cards goes where so long as the overall shape is the same.

Stacks are placed face down. Players may look at their cards at any time during the game.

![[Kingstack Board Set Up 3x5.excalidraw|center|250]]
In this figure, red and blue are both in the $\perp$ formation but have positioned their stacks differently.

<div style="page-break-after: always;"></div>
## Two Player 3x5

The most beginner friendly board set up is on a 3x5 board. The grid can be marked with other cards from the deck, or players can just remember how far they've moved. 


![[Kingstack Board Set Up 3x5.excalidraw|center|250]]

<div style="page-break-after: always;"></div>


## Two Player 5x5

For an additional challenge, players can play on a 5x5 grid instead. A blockade is positioned in the very center of the board which no unit may move onto, or through, or attack onto, or through.

![[Kingstack Board Set Up 5x5.excalidraw|center]]
The green X in the middle of the board represents the blocked square.
This could be a river that the armies cannot pass through except via bridges on either side.

The center square is blocked for the entire game.

<div style="page-break-after: always;"></div>


## 3-4 Players

For 3-4 players, games should always be played on the 5x5 grid with all squares available to play on (ie the center square is not blocked).

For 3 players, whoever is in the middle will be at a disadvantage since they are trapped on either side. So, the other players will shift one column away to provide a bit more breathing room.

![[Kingstack Set Up 5x5 3 Players.excalidraw|center]]



For 4 players, setup is the same and all players will position their formation in the center of each side.

![[Kingstack Set Up 5x5 4 Players.excalidraw|center]]

---
# How to Play

To win the game you must attack the opponents Fool. Probe the enemy to determine their troop formation. Attack quickly but don't reveal too much.
Read your opponents moves and bluff your way through your own.

Once the armies are set up, players communicate the number of cards in each stack.

Decide which player goes first.

Players choose one unit to make a single action. The basic rules are:
- Players may do exactly one of the following:
	- Move a unit.
	- Attack an opposing orthogonal unit.
	- Stall by revealing the top card of one of their own stacks.
- Once a card is revealed it stays revealed until it is removed from the game.
- The Fool cannot attack at all and loses to everything.
- If two players remain, then if a player's final unit is the Fool, they lose the game immediately.

---
## Actions

### Move

- Movement can only be horizontal or vertical. Units may not move diagonally and they may not move on the same square as another unit or a blockade.

---
### Attack

- Adjacent units can attack each other. Diagonal attacks are not allowed. The attacking unit will reveal the top card on the stack if it is not already revealed. 
	- The defending unit will reveal the top card on the stack if it is not already revealed. If the defending unit loses the battle, after they have removed the defeated card, they may reveal the next card in the stack to "retaliate." In general, the defending player may continue to retaliate until the attacking card has lost.

The rules of combat are expounded upon in a later section.

---
### Stall

- Players who want to preserve their strategic position may choose to reveal the top card of a hidden stack instead of moving or attack. If all of their stacks are revealed, then they must move or attack with a unit.

If the active player holds a tactical position they don't want to give up, then they may reveal the top card from one of their facedown stacks.

---
# Combat

There are 3 types of cards that can attack and defend during combat:
- Numbered Cards
- Face Cards
- Ace

Numbered cards will lose to all Face cards.
All Face Cards lose to the Ace.
Ace loses to all Numbered Cards.

![[Kingstack Combat Diagram.excalidraw|center]]

This holds in all situations. 

<div style="page-break-after: always;"></div>
>[!Example] Example 1: Combat
>Player A attacks Player B
>Player A reveals a 10 with their attacking unit
>Player B reveals a 3
>Player A wins
>Player B's 3 is removed

>[!Example] Example 2: Face Card Combat
>Player A attacks Player B, revealing a 10
>Player B reveals a Jack
>Player B wins
>Player A's 10 is removed

>[!Example] Example 3: Ties
>Player A attacks player B, revealing a 6
>Player B reveals a 6
>The battle is a draw
>Both 6s are removed


Note: The only way to win the game is to attack the opponents Fool. The Fool may not attack. The Fool loses to everything.

### Numbered Cards

Number cards have the most utility in defense. The attacking card will be going up against the sum of all the cards used in defending.

>[!Example] 
>A 10 attacks a 2.
>The 2 is removed from the game.
>Defending player chooses to reveal the next card to defend.
>A 9 is revealed.
>9 + 2 > 10, so the 9 wins.
>The 10 is removed from the game and combat ends.
>The 9 survives.

Here the 9 wins on defense since the 2 ate up some of the 10s strength.
This is only for a single combat. The following turn, the 9 acts as a 9 still. 

The effects from a battle are not persistent. Everything resets at the end of the turn.


>[!Example] Multiple Defenses
>A 10 attacks a 2
>The 2 is removed
>Defending player reveals a 3
>10 > 2 + 3, so the attacker wins again
>The 3 is removed
>Defending player reveals a 5
>10 = 2 + 3 + 5, so the combat ends in a draw
>The attacker's 10 and the defender's 5 are both removed

Here all the cards revealed in defense are removed, but they still manage to take down the 10.

<div style="page-break-after: always;"></div>
### Initiative

If an attacking stack reveals a card of equal power on the defending stack, then the attacking card will survive while the defending card will be removed from the game. This is the *Initiative Rule*.

>[!Example] Initiative 1
>Attacking player has a King and attacks a face down unit.
>The top card is revealed to be a King.
>The attacking King has initiative and so wins the battle.


>[!Example] Initiative 2
>The active player attacks a face down stack with a face down stack.
>Both players reveal the top card to be a 7.
>The attack player's 7 survives while the defending player's 7 is removed from the game.

>[!Warning] Note:
>The defending may still reveal the next card to defend. The attacking player's 7 in the above example would be *depleted* and thus be removed from the game.

---
### Face Cards and MAD

Face cards are very powerful. They defeat all numbered cards, regardless of the number of defenses. This means if a Jack is attacking a unit of only numbered cards, the defending player could reveal all of their cards in defense and lose all of them.

Numbered cards cannot ever kill a Face Card.

Face Cards follow their own hierarchy with King>Queen>Jack.


>[!Example] Attacker Wins
>A King attacks a face down unit.
>The top card is revealed to be a Queen.
> The King is stronger and wins the combat.
> The Queen is removed from the game.

>[!Example] Defender Wins
>A Jack attacks a face down stack.
>The top card is revealed to be a Queen.
>The Queen is stronger.
>The Jack is removed from the game.

Standard play between two face cards.

If any Face Card attacks a unit whose top card is a numbered card and the defending player reveals the next card to be a Face Card of equal strength, then both Face Cards are removed from the game. This is the **MAD Rule: Mutually Assured Destruction**.

>[!Example] MAD 
>A Queen attacks a face down unit.
>A 10 is revealed.
>The Queen wins and the 10 is removed.
>Defending player reveals a Queen on defense.
>Queens are of equal power and so are both removed from the game.


Now here are a few examples of what should be avoided.

>[!Warning]
>A King attacks a face down unit.
>A 10 is revealed and is removed.
>The defending player reveals a 9.
>The 9 is removed.
>Defending player reveals an 8.
>The 8 is removed.
>etc...

>[!Warning]
>A King attacks a face down unit.
>A 8 is revealed and is removed.
>The defending player reveals a 9.
>The 9 is removed.
>Defending player reveals an 10.
>The 10 is removed.
>Defending player reveals a Jack.
>Jack is removed.
>Defending Players reveals a Queen.
>Queen is removed.

These are legal plays, just ill advised. Mutually Assured Destruction only occurs when the defending card is of equal strength to the attacking Face Card.

---
### Ace

The Ace loses to all numbered cards, even the 2, but can defeat all Face Cards in attacking or defending.

>[!Example]
>A King is revealed on the top of a stack.
>The active player attacks the king with a face down unit, revealing it to be an Ace.
>Ace wins and the King is removed from the game.
>Defending player reveals a 3 on defense.
>Ace is removed from the game.

---
# Ending the Game

The game is won when a player successfully attacks their opponent's flag.

If one player has no cards that can defeat one of their opponents cards, then the game should end. The player with the higher card being the winner.

If both player's are left only with their Fools left, then the game is a draw.
If both player's are left with one unit each of equal strength, then the game is a draw.

A player can only win if they have two or more units.

To avoid one player simply running away forever, players may implement a rule to shrink the playing grid.

# Misc.

Here are some miscellaneous rules:
- Players may ask how many cards are in any other player's stack at any time.
- Players may ask how many cards any other player has lost throughout the game at any time.
- Players may ask which cards any other player has lost throughout the game at any time.


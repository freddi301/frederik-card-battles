# Game Material

A standard 52-card poker deck, so no jokers.

The game can be played with 2 to 6 players.

# Goal

The winner is the player with the strongest card combination at the end of the game.

The strength of card combinations is the same as in poker.

To create your card combination, you can choose up to 5 cards,

you can pick from the cards in front of you and include at most one face-up card from other players (not one per player, just one total).

# Drawing Phase

In the drawing phase, players draw cards from the central deck to build the set of cards in front of them. Here's how it works:

Clockwise, for 5 rounds,

the player draws 5 cards from the central deck,

chooses one and places it face down in front of them,

the rest go to the bottom of the central deck (these 4 cards can be rearranged in any order).

The player must now ensure that at most one of the cards in front of them is face down, and must reveal the others.

Alternatively, in your first drawing round, you may place all 5 drawn cards face down in front of you; if you do this, you can no longer act until the battle phase.

# Battle Phase

In the battle phase, players can sabotage other players’ setups or improve their own as follows:  
Clockwise, for 2 rounds, players can take one of the following actions:

- Discard two cards of the same number and draw 4 cards from the top of the central deck
- Discard three cards of the same number and draw 6 cards from the top of the central deck
- Draw one card from the top of the central deck
- Draw the N-th card from the top of the central deck, where N is the sum of the numbers from any combination of face-up cards you have in front of you
- Turn one of your own cards face down
- Turn one of your own cards face up to force another player of your choice to turn one of their cards of your choice face up
  - To block this action, any player may discard a card with the same color or number as the one you just revealed. In that case, the targeted player does not flip their card, and yours stays face up
- You may swap one of your cards with a face-up card from another player if your card has a higher number and their card is the highest of its suit
  - The opponent can respond by revealing a card that effectively protects the targeted card. If so, you discard yours and they keep theirs
  - Any player may interrupt this action by discarding a card with the same number or suit as yours; if so, you discard your card and the opponent keeps theirs
- You may swap one of your cards with a face-up card from another player if your card has a lower number and the same suit, and the opponent's card is the lowest of that suit
  - The opponent can respond by revealing a card that protects the targeted card; if so, you discard yours and they keep theirs
  - Any player may interrupt this action by discarding a card with the same number or suit as yours; if so, you discard your card and the opponent keeps theirs
- You may swap one of your cards with a face-up card from another player if your card has the same number (in this case, higher or lower cards of the same suit do not protect the target)
  - Any player may interrupt this action by discarding a card with the same number or suit as yours; if so, you discard your card and the opponent keeps theirs
- You may discard one of your cards to make an opponent discard a face-up card if your card has a higher number and their card is the highest of that suit
  - The opponent can respond by revealing a card that protects the targeted card; if so, you discard yours and they keep theirs
  - Any player may interrupt this action by discarding a card with the same number or suit as yours; if so, you discard your card and the opponent keeps theirs
- You may discard one of your cards to make an opponent discard a face-up card if your card has a lower number and the same suit, and their card is the lowest of that suit
  - The opponent can respond by revealing a card that protects the targeted card; if so, you discard yours and they keep theirs
  - Any player may interrupt this action by discarding a card with the same number or suit as yours; if so, you discard your card and the opponent keeps theirs
- You may discard one of your cards to make an opponent discard a face-up card if your card has the same number (in this case, higher or lower cards of the same suit do not protect the target)
  - Any player may interrupt this action by discarding a card with the same number or suit as yours; if so, you discard your card and the opponent keeps theirs
- You may discard a card to steal a card from an opponent if your card has a higher number than the one you want to steal, their card is the highest of that suit, and you have two cards with the same color or number as the card you want to steal
  - The opponent can respond by revealing a card that protects the targeted card; if so, you discard yours and they keep theirs
  - Any player may interrupt this action by discarding a card with the same number or suit as yours; if so, you discard your card and the opponent keeps theirs
- You may discard a card to steal a card from an opponent if your card has a lower number than the one you want to steal, their card is the lowest of that suit, and you have three cards with the same color or number as the card you want to steal
  - The opponent can respond by revealing a card that protects the targeted card; if so, you discard yours and they keep theirs
  - Any player may interrupt this action by discarding a card with the same number or suit as yours; if so, you discard your card and the opponent keeps theirs

You can interrupt another player's action, usually by discarding a card with the same color or number as the one being used.

Each action clearly indicates whether it can be interrupted and what the outcome is.

Using the interrupt action does not consume your battle turn since it happens during another player's turn.

# Additional Rules and Clarifications

Remembering cards is allowed.

You cannot look at the cards in the central pile.

To "discard" means placing cards at the bottom of the central pile (you may reorder them however you wish).

You cannot target face-down cards of other players, and you cannot use them to calculate your score unless otherwise stated.

You can use your own face-down cards during the battle phase unless stated otherwise.

Cards of the same suit protect each other from swap, steal, or discard actions in numerical order, examples:

- you cannot swap a 2 of hearts with an opponent’s K of hearts if the opponent has a 10 of hearts
- you cannot use an ace to make an opponent discard a 10 of spades if they have a J of spades

Summary of combination hierarchy:

| Combination     | Description                                   |
| --------------- | --------------------------------------------- |
| Royal Flush     | 10 J Q K A of the same suit                   |
| Straight Flush  | 5 cards in numerical order of the same suit   |
| Four of a Kind  | 4 cards with the same number                  |
| Full House      | Three of a kind plus a pair                   |
| Flush           | 5 cards of the same suit                      |
| Straight        | 5 cards in numerical order of different suits |
| Three of a Kind | 3 cards with the same number                  |
| Two Pair        | Two pairs                                     |
| One Pair        | 2 cards with the same number                  |
| High Card       | The card with the highest number              |

[Return to index](README.md)

# Gameplay

## Flow of the game

1. The game is played in rounds, in which each player takes a turn in clockwise order, starting with the starting
   player.
1. In a co-op game, there is an Overlord turn at the beginning of each round.

## Overlord turn

1. If there was an active Overlord event card, discard it.
1. The top card of the Overlord event deck is turned face up, activating it.
1. If the Overlord has hit points between 70 and 99, the effect under the ![img.png](icons/overlord-anger.png) header is
   resolved.
1. If the Overlord has hit points between 40 and 69, the effect under
   the ![img.png](icons/overlord-anger.png)![img.png](icons/overlord-anger.png) header is resolved.
1. If the Overlord has hit points between 1 and 39, the effect under
   the ![img.png](icons/overlord-anger.png)![img.png](icons/overlord-anger.png)![img.png](icons/overlord-anger.png)
   header is resolved.
1. Some effects trigger immediately and only once, some offer conditional effects, some offer active effects until the
   beginning of the next Overlord turn.

## Player turn

1. A player turn consists of the beginning of his turn, then a main phase followed by a clean up phase.
1. The main phase consists of exactly one main action and any number of minor actions, in any order.
1. The clean up phase consists of paying weight cost, resetting the journey track, resetting the attack and defense
   power of the player, and resetting minor actions.

## Beginning of turn

1. The player flips inactive pearl tokens.
1. Resolve conditional abilities that trigger at the beginning of a turn.

## Main actions

1. There are two main actions that are always available to players: journeying and resting.
1. If there is an active Overlord card in play, there is another main action available to players: challenging the
   Overlord.

## Journeying

1. Journeying means taking a card from the journey track.
1. There are six slots on the track to journey to, numbered 0 to 5, from left to right.
1. The player cannot journey to a slot that does not contain a card.
1. The cost of journeying to a slot is a number of crystals equal to the slot number.
1. If the player has the “journeys at ![img.png](icons/damage.png) 3 or more cost you only
   3 ![img.png](icons/crystal.png)” effect, and the slot number is three or higher, this cost is set to 3.
1. This cost is lowered by the player’s speed value. If it’s less than one, the cost is zero.
1. If the player does not pay the cost, he cannot journey to this slot.

## Journey results

1. If the slot contains a creature card, combat takes place (see there). If combat fails, skip the rest of the section.
1. If the card contains an immediate effect ability, resolve it. These effects are prefixed with
   the ![img.png](icons/immediate-effect.png) icon. If the player does not own the card anymore after resolving this
   ability, skip the rest of the section.
1. If the player has effects that trigger after taking a card of this type, resolve those.
1. If it's item card, the player adds that card to his item stack.
1. If it's an enchantment card, the player adds that card to his enchantment stack.
1. If it's a creature card, the player adds that card to his creature stack.

## Combat

1. The player may take any minor actions he desires.
1. If the player does not have attack power equal to or greater than the health of the creature:
    2. Combat failed.
    3. Discard the card on journey track slot 0.
    4. If there is an active Overlord in play, the discarded card may trigger an invasion.
    5. Skip the rest of this section.
1. The creature attacks the player.
1. Combat was successful, and the creature is defeated. If the player has abilities that trigger when a creature of this
   type is defeated, resolve them now.

## Resting

1. To rest, the player chooses one of the rest actions available to him. Rest actions
   have ![img.png](icons/rest-action.png) in their cost.
1. Each village card defines at least one rest action.
1. Some item, enchantment and Overlord cards also define rest actions.
1. If the rest action defines an additional cost, the player may pay it. If the player does not pay the cost, he cannot
   take that action.
1. The player resolves the effects of the rest action.
1. The player discards the card on journey track slot 0.
1. If there is an active Overlord in play, the discarded card may trigger an invasion.

## Overlord invasion

1. If there is not an active Overlord in play, skip the rest of this section.
1. This happens when a card from journey track slot 0 is discarded due to resting or failing combat.
1. Invasion abilities are defined on the Overlord card as: *type: effect*.
1. If the Overlord has invasion abilities associated with the type of the discarded card or any token on it, resolve the
   effects of the abilities.
1. Discard all tokens on the card.

## Challenging the Overlord

1. Challenging the Overlord means fighting him to either gain reward tokens or reduce his hit points.
1. If there is not an active Overlord in play, this action is not available.
1. Most Overlord cards define at least one challenge action. Challenge actions have ![img.png](icons/overlord.png) in
   their cost.
1. If the challenge action defines an additional cost, the player may pay it. If the player does not pay the cost, he
   cannot take this action.
1. Combat takes place. If combat fails, skip the rest of this section.
1. If you chose to play with reinforcements, add a reinforcement token with a random side up on the Overlord. If this is
   a two-player game, add another reinforcement token with a random side up on the Overlord.
1. If this is not a co-op game, the player takes one reward token from the Overlord card. The token acts as a card with
   the text that’s in the “reward” section of the Overlord card. If the reward section defines an immediate
   effect ![img.png](icons/immediate-effect.png), resolve it now.
1. If this not a co-op game and the last reward token is taken from the Overlord, he is considered defeated and inactive
   from now on.
1. If you chose to play a co-op game, resolve the effects of the “reward” section of the Overlord card. This typically
   lowers the hit points of the Overlord.
1. The player discards the top card of the adventure deck.

## Minor actions

1. Minor actions are defined as: *cost ![img.png](icons/minor-action.png) effect*.
1. Rest actions and challenge actions also follow this format but are not considered minor actions. They have
   either ![img.png](icons/rest-action.png) or ![img.png](icons/overlord.png) in their cost.
1. A player can activate minor actions visible on his stacks, on the village card and on the Overlord card.
1. A minor action can only be activated during a player’s turn and when preparing for a duel, and only once per turn per
   card.
1. A multi-action is a minor action in every regard, except it can be activated more than once per turn per card.
1. A double action is a minor action in every regard, except it can be activated twice per turn per card.
1. To activate a minor action, the player must pay the cost. If he does, the effect is resolved, and if it’s not a
   multi-action the effect on this card gains a used label.
1. The player may pay part or all of the crystal costs of a minor action by flipping any of his active pearl tokens.
   Each flipped pearl token is equal to paying 1 crystal.

## Paying weight cost

1. If the player journeyed this turn, discard crystals equal to his weight value.

## Resetting the journey track

1. From left to right, move visible cards on the track to the leftmost spot that’s empty.
1. As long as there are empty spots on the track and cards in the adventure deck, draw cards from the adventure deck and
   place them left to right on the track.

## Resetting attack and defense

1. Set the player’s attack power to the sum of all visible ![img.png](icons/attack.png) icons, reduced by the sum of all
   visible ![img.png](icons/attack-down.png) icons. If the value is less than zero, the value is zero.
1. Set the player’s defense power to the sum of all visible ![img.png](icons/defense.png) icons, reduced by the sum of
   all visible ![img.png](icons/defense-down.png) icons. If the value is less than zero, the value is zero.

## Resetting minor actions

1. This means that minor actions lose the used label.

## End of the game (non-co-op)

1. The game ends after a turn when there are no more cards on the journey track nor in the adventure deck.
1. In a game where one complete kingdom deck is used per player, each player should’ve taken exactly 25 turns.
1. If you are playing with the *Arena Mundi* village card, each player duels the player to their left.
1. If you are playing with *Sa’akara the Gamerunner*, each player may duel a target player once for each reward token he
   possesses. The player may choose the same target multiple times.
1. Each player calculates how many victory points he has. The players with the highest amount wins, each other player
   loses.

## End of the game (co-op)

1. If at any point, there are more wound tokens on the wound threshold card than the limit on that card, each player
   loses the game.
1. If at any point the Overlord has zero hit points remaining, each player wins the game.
1. If there are no more cards on the journey track nor in the adventure deck, each player loses the game.

## Victory point calculation

1. Sum the victory points gained from the following sources:
    - From the village card.
    - From the visible sections of the cards in your stacks.
    - From reward tokens, where each reward token counts as a card with the description that appears in the “reward”
      section of the Overlord card.
    - From your wound count: you get -1 victory point for each wound.
1. The total number of victory points may be less than zero.

[Return to index](README.md)

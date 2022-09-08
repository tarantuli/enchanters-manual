[Return to index](README.md)

# Writing Reference

## Standard terminology

- Always write “Overlord” with a capital.
- Whenever you are referring to a card, make sure to add “card” to the text.
  E.g., you add tokens to an *Overlord* card, but it’s an Overlord (without card) that attacks.
- Refer to stack and deck positions as “top” and “bottom”, and to card sections as “upper”, “lower”, “middle”, “left”
  and “right”.
- Use “each player” instead of “all players” or “every player”.
- Use “each other player” instead of “all other players” or “every other player”.
- Use “whenever” instead of “if” whenever it means “whenever”.
- Use “whether” instead of “if” whenever it means “whether”.
- The only thing you can “pay” is costs; everything else is usually “discarded”, sometimes “removed”.
  - E.g., you pay 2![img.png](icons/crystal.png) by discarding two crystals.
- Abilities are triggered by circumstances; effects are resolved by players.
- Put specific card names in italics.
  E.g., the *Cave of Fools* village card.
- Be careful to use creature, monster, and dragon correctly.
- You “journey” to slots, you don't “travel”.

## Ordering items

| Subject            | Target            | Action  | Set | Size    |
|--------------------|-------------------|---------|-----|---------|
| Taking damage      | You               | Use     | And | Lowest  |
| Healing            | A specific player | Journey | Or  | Highest |
| Attack power       | Another player    | Take    |     |         |
| Defense power      | Each other player | Give    |     |         |
| Speed value        | Each player       | Discard |     |         |
| Weight value       | Monsters          | Remove  |     |         |
| Speed value        | Dragons           | Bury    |     |         |
| Slime value        | Overlords         | Unbury  |     |         |
| Undead value       |                   | Flip    |     |         |
| Pearls             |                   | Shuffle |     |         |
| Crystals           |                   |         |     |         |
| Cards in general   |                   |         |     |         |
| Item stack         |                   |         |     |         |
| Enchantment stack  |                   |         |     |         |
| Creature stack     |                   |         |     |         |
| Banners            |                   |         |     |         |
| Classes            |                   |         |     |         |
| Attacking          |                   |         |     |         |
| Dueling            |                   |         |     |         |
| Village            |                   |         |     |         |
| Journey track      |                   |         |     |         |
| Graveyard          |                   |         |     |         |
| Monster stats      |                   |         |     |         |
| Monster abilities  |                   |         |     |         |
| Dragon stats       |                   |         |     |         |
| Dragon abilities   |                   |         |     |         |
| Overlord stats     |                   |         |     |         |
| Overlord abilities |                   |         |     |         |
| Tokens in general  |                   |         |     |         |
| Reward tokens      |                   |         |     |         |
| Desert token       |                   |         |     |         |
| Winning            |                   |         |     |         |
| Losing             |                   |         |     |         |

## Cleaning up files

### Normalizing numbered list indices

Using PhpStorm:

- Replace in files
- Find `^( *)\d\.` (regex)
- Replace by `$11.`

[Return to index](README.md)

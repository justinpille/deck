# deck

This module generates and exports an array of 50 objects (no jokers). Each one has the following properties:

**index:** A number from `0` to `49`.

**nameIndex:** A number from `0` to `12`.

**suitIndex:** A number from `0` to `3`.

**value:** A number from `1` to `10`. Note there are 16 cards with a value of 10.

**name:** One of the following strings:

- `ace`
- `one` through `ten`
- `jack`
- `queen`
- `king`

**suit:** One of the following strings:

- `spades`
- `clubs`
- `hearts`
- `diamonds`

**id:** A unique two-character identifier. The first character stands for the name, and the second for the suit. For example, `as`, `4c`, `qh`.

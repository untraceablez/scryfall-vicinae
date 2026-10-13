# Scryfall for Vicinae

Search Magic: The Gathering cards from [Vicinae](https://docs.vicinae.com) using the [Scryfall API](https://scryfall.com/docs/api).

## Usage

Run **Search Scryfall** (`scry`) and type a card name or any [Scryfall search syntax](https://scryfall.com/docs/syntax):

- `lightning bolt`
- `t:dragon c:r cmc<=4`
- `o:"draw a card" f:modern`

The first few matches are shown with the card image and details. The last row opens the full results on scryfall.com in your default browser.

| Action | Result |
| --- | --- |
| Enter on a card | Open it on Scryfall |
| Copy Card Name / Oracle Text | Copy to clipboard |

The number of cards listed can be changed in the extension preferences.

## Development

```bash
npm install
npm run dev    # live reload
npm run build  # install into Vicinae
```

## Disclaimer

Unofficial and not affiliated with Scryfall or Wizards of the Coast. Card data and images are provided by Scryfall; Magic: The Gathering is a trademark of Wizards of the Coast.

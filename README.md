# Elf Continent Marketplace Analytics Dashboard

Static analytics dashboard for Elf Continent Marketplace Resources, General items, and Pi Elf Outfit prices.

## Features

- Tracks Resources items such as crops, fruit, wood, ore, egg, and milk.
- Tracks General items such as gift cards, treasure maps, relics, and blueprints.
- Tracks Pi Elf Outfit items such as CiDi Echo, Tiger Head, Genesis Pioneer, Cosmic Sovereign, and Take My Pi.
- Shows General and Pi Elf Outfit item images from Elf Market Tracker image assets.
- Refreshes recent transaction prices every 5 minutes for the selected market tab.
- Shows latest price, quantity, total amount, buyer player name, seller player name, and update time.
- Includes item search, sorting, and player-name transaction search.
- Adds player income ranking, related-account analysis, neutral market-pattern notices, Marketplace Pattern Score, daily Sigil income, and item market concentration.
- Opens on a market overview dashboard before any player search is entered.
- Supports Traditional Chinese and English through `languages/zh-TW.json` and `languages/en.json`.

## UI Structure

- Dashboard: market totals, top income players, concentrated items, recent transactions, and high pattern score players.
- Search: player, item, and transaction results from one fixed top search box.
- Player profile: overview, transactions, related accounts, daily income, pattern alerts, and item concentration tabs.
- Mobile: compact cards, horizontally scrollable tabs, and compact transaction views.

## Data Source

The page reads recent transaction prices from:

```text
https://elf-market-api.vercel.app
```

Prices are recent transaction prices, not the full official order book.

General and Pi Elf Outfit item images reference:

```text
https://elfmarkettracker.com/images/{itemId}.png
```

## GitHub Pages

Publish this repository with GitHub Pages from:

```text
Branch: main
Folder: / (root)
```

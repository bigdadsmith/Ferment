# Ferment — Architecture Overview

## Core Modules

- **Launcher Core:** Game library, game metadata, storage
- **UI Layer:** Main window, game cards, overlay/GameBar, settings
- **Integrations:** GPTK runner, Steam/Epic catalog, system integrations (Do Not Disturb, analytics)
- **Analytics:** Play time, achievements, session history, stats

## Technologies

- Swift, SwiftUI
- GPTK (Game Porting Toolkit)
- Steam & Epic Games Store APIs (public data, web scraping if needed)
- Modern macOS features (Liquid Glass, dark mode)

## User Flow

1. Add a game via .exe/.msi
2. Game metadata (artwork, description) auto-fetched
3. Launch via GPTK, overlay stats shown
4. Games bought in Steam/Epic appear automatically in library
5. Wishlist and stats visible in the main menu

_More details and diagrams to be added here as the project develops._

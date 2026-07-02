# Changelog

All notable changes to AlaCraft are documented here.  
The project has been live at [alacraft.day](https://alacraft.day) since November 2023.

---

## 2026

### July

- **Craft Map** — a new interactive tool at `/craft-map` displays all Minecraft crafting recipes as one connected, draggable board. Every recipe is a card with its crafting grid and result; arrows show which crafted items feed into other recipes. Focus mode traces any item back to its raw resources through the full crafting chain. Card positions are saved in the browser, the board is filterable by mod, and pinch-zoom works on phones

### June

- **Paintings Catalog** — a new `/paintings` page covers all 50 Minecraft paintings with their exact sizes in blocks, the real-world artwork each one references, the artist, and ready-to-use `/give` and `/summon` commands. Every painting has its own detail page (e.g. `/paintings/orb`) with size diagram, lore, and FAQ
- **Seed Map** — an interactive `/seed-map` tool renders a live, zoomable biome map for any Minecraft Java seed directly in the browser (versions 1.7 through 1.21.4). Shows structure icons, slime chunks, biome highlights, a chunk grid, and generates shareable links with coordinates
- **Our Mods** — a `/mods` page showcases our three free, open-source NeoForge server mods for Minecraft 1.21: AlaLoot (loot scales with your XP level), AlaHorde (mobs grow stronger the more you kill), and AlaAggro (every mob turns hostile on spawn). Each mod has an in-game screenshot, download count, and direct CurseForge and GitHub links, plus a step-by-step install guide
- **Stack & Inventory Calculator** — `/stack-calculator` converts any item quantity into filled Minecraft containers: chest, double chest, shulker box, or player inventory. Includes shulker-box nesting mode (a double chest of shulkers holds up to 93,312 items), visual Minecraft-style slot grids, and per-slot stack counts. Available in all 7 languages
- **XP & Level Calculator** — `/xp-calculator` converts between Minecraft levels and total experience, calculates how much XP it takes to go from one level to another, and explains enchanting costs (1/2/3 levels spent, 15 bookshelves for level 30). Includes an XP sources reference table, copy-ready `/xp` commands, and a companion guide at `/news/xp-calculator-guide`. Available in all 7 languages
- **Furnace & smelting recipes** — 116 cooking and smelting recipes added to the crafts catalog: Furnace, Blast Furnace, Smoker, and Campfire. Recipe cards show the input item, fuel slot, XP reward, and cooking time. Searchable alongside crafting table recipes from the same `/crafts` page
- **In-world interaction recipes** — 29 crafting methods that require no crafting table added to the catalog: filling cauldrons with water, lava, and powder snow; scooping buckets; End Portal Frame + Eye of Ender; Chiseled Bookshelf + book; candle cakes; lodestone compass; respawn anchor charging; log stripping; dirt paths; farmland; carved pumpkins; and beehive harvesting

### May

- **Create 3D Block** — `/create-3d-block` lets players upload a texture for each of the six cube faces, rotate and zoom a pixel-perfect 3D preview, and download the result as a transparent PNG at any resolution from 256×256 up to 2048×2048. Available in all 7 languages
- **Potion Generator** — `/potion-generator` builds custom potions and generates the ready-to-use `/give` command with the correct NBT tags. Available in all 7 languages
- **Account email verification** — the sign-up confirmation flow now shows a clear result page after clicking the verification link: either "Email confirmed, you are signed in" or "This link expired — request a new one". Expired links no longer land on a generic error; players can paste their email and get a fresh link in one click
- **Sulfur Cube guide** — `/sulfur-cube` covers all 12 Sulfur Cube archetypes from Minecraft 26.2 Chaos Cubed — the exact block that triggers each one, how each archetype moves, how to catch a cube in a bucket, and how to grow or keep it small
- **Achievement Generator** — `/achievement` creates high-resolution Minecraft advancement-style PNG images with Task, Goal, and Challenge frames. Choose an icon from the block catalog, set a title and description, and download the result
- **Stronghold Finder** — `/stronghold-finder` triangulates the End portal location from two Eye of Ender throws using the player's X/Z coordinates and the F3 screen Facing angle. No math required
- **Custom Crafts Creator** — `/custom-crafts` lets players build their own 2×2 and 3×3 crafting recipes using the full AlaCraft block catalog and export them as datapack JSON. Includes a step-by-step guide
- **Public changelog** — `/changelog` now tracks AlaCraft updates chronologically, accessible from the navigation bar and footer in all 7 languages
- **Seeds catalog** — `/seeds` is a hand-picked Minecraft world seed collection with maps, coordinates, categories (survival, villages, rare biomes, scenic starts, speedrun), and Java/Bedrock compatibility notes. Each seed has its own detail page
- **Community Portal** — `/community` lets players publish posts, react to builds, and share presets directly on the site. Moderation and reporting are built in
- **Japanese locale** — AlaCraft is now available in Japanese (`/ja/`), the 7th supported language. Block names and item labels use official Mojang translations
- **New command & world tools** — Nether Coordinate Calculator (`/nether`), Fireworks Builder (`/fireworks`), `/tellraw` Editor (`/tellraw`), and Flat World Generator (`/flat-world`) added. Each includes a step-by-step guide and FAQ
- **Contact page** — `/contact` provides a direct way to reach the AlaCraft team
- **Block guide pages** — 1,332+ individual block pages go live at `/{lang}/blocks/{slug}`, each with a multilingual description, crafting recipe, usage guide, and FAQ in all 7 languages
- **Automated sitemap** — XML sitemap with `hreflang` alternates for all 7 locales, updated automatically on every deployment

---

## 2025

- **News & Guides** — `/news` section launched; Minecraft news, patch notes, and long-form how-to guides published regularly
- **Block reference catalog** — full database of 1,332 blocks with search, mod filters, and version filtering
- **Multilingual expansion** — Ukrainian (`/uk/`), Spanish (`/es/`), French (`/fr/`), and German (`/de/`) locales added
- **Player profiles** — registration, personal inventory tracking, and activity history

---

## 2024

- **Armor Color Generator** — visual leather armor dye tool with interactive 3D skin preview (July)
- **Skin Viewer** — look up and preview any player's Minecraft skin in 3D by username (May)
- **Banner Generator** — design any Minecraft banner pattern and get the `/give` command and Loom recipe
- **MOTD Generator** — create custom server messages with color formatting and live preview (April)
- **Color Codes** — full Minecraft formatting and color code reference (March)
- **Privacy Policy & Terms of Service** — added (January–February)
- **Crafting recipes database** — initial database of 753 vanilla crafting recipes, searchable by item name and ingredient
- **Russian and English locales** — first two supported languages

---

## 2023

- **Domain registered** — `alacraft.day` registered November 3, 2023
- **Soft launch** — homepage goes live November 26, 2023
- **Core platform** — Laravel + Vue 3 stack, MySQL database, Cloudflare CDN
- **Crafts foundation** — initial import of Minecraft crafting recipe database

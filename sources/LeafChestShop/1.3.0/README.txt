LeafChestShop 1.3.0

Feature: tiered Sell Wands priced from WorldsBestShop sell prices.

Reconstruct the source bundle by concatenating every LeafChestShop_Source_1.3.0.part*.txt file in filename order.

Sell Wand tiers:
- Tier 1: 1000 uses, 1.0x WorldsBestShop sell price
- Tier 2: 3000 uses, 1.5x WorldsBestShop sell price
- Tier 3: 10000 uses, 2.0x WorldsBestShop sell price

Admin command: /givesellwand tier <1-3> <username>

Use: hold the enchanted stick and left-click a ChestShop sign owned by you. The wand sells all sellable contents of the attached container using WorldsBestShop prices. Unsellable items remain in the container and are reported as skipped.

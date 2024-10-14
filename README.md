<div align="center">
<h1>My Minecraft Servers</h1>
</div>

## Index
- [How to Use](#how-to-use)
- [Bedwars](#bedwars)
  - [Differences between My Bedwars and Hypixel Bedwars](#differences-between-my-bedwars-and-hypixel-bedwars)
- [Ballwars](#ballwars)
  - [Differences between My Bedwars and Ballwars](#differences-between-my-bedwars-and-ballwars)
  - [Ballwars Strategies](#ballwars-strategies)
- [Pillars of Fortune](#pillars-of-fortune)
- [Party Games](#party-games)

## How to Use
- Download one of the folders. Each one contains a different server
- Edit the run.sh file such that it points to your Java installation
- Download a server.jar
  - Any spigot-based server works but I use [Paper](https://papermc.io/) for my servers
  - I use [paper-1.8.8](https://papermc.io/downloads/all) for my bedwars and ballwars servers
- Rename the file to server.jar and place it into the server folder
- Run run.sh
- Note: I set my servers to use a different port than normal. Some servers include a whitelist plugin and are configured to run in <ins>offline mode<ins>

## Bedwars
My Bedwars servers use [Screaming Bedwars](https://www.spigotmc.org/resources/screaming-bedwars-1-8-8-1-21-1.63714/) ([github](https://github.com/ScreamingSandals/BedWars)) and [Screaming Bedwars Addons](https://www.spigotmc.org/resources/sba-screaming-bedwars-addon-1-8-8-1-21-1.99149/) ([github](https://github.com/boiscljo/SBA)), with config changes to make it as close to normal bedwars as possible.

### Differences between My Bedwars and Hypixel Bedwars:
- Click the sign to join the game, or type `/bw join` (`/bedwars join`)
- The server has one map/one game at a time
- There is no sudden death 
- Bots can be added but they're practically useless (`/sba ai join` in lobby)

__Maps:__
- Ruins (2 islands)
- Invasion (4 islands)
- Lighthouse (8 islands)

__Resources:__
- Iron spawns 1 per second
- Gold spawns 1 per 8 seconds
- Diamonds spawn 1 per 30 seconds
- Emeralds spawn 1 per minute 

__Shop:__
- Fireballs aren't as accurate (sniping is impossible)
- Fireball jumping is different
  - Fireballing straight down sends you extremely high
  - I tried tweaking this for a long time to make it similar to Hypixel
- Spamming fireballs or throwing while running may cause them to hit you
- Fireballs destroy stone (they use the same logic as TNT) and spash through blocks
  - This means covering blocks in glass won't work
- Water costs 6 gold
- Silverfish don't exist
- The only potions are invis and instant heal (1 emerald)
- You can only set the bottom row of quick buy
- Iron golems are weak
- You can directly buy any level tools
  - Tools (usually) downgrade 1 level (until wood) upon death

__Team Upgrade Shop:__
- Forge costs 2 diamonds per level and increases base resource generation by +33% per level, up to +100%
- Mining fatigue trap costs 2 diamonds for balance
- Counter-offense trap gives jump boost and regen

## Ballwars
Ballwars is a fun Bedwars variant where the rules and mechanics are the same, but fireballs and bridge eggs are cheap. My friends and I came up with this, and it's surprisingly fun.

### Differences between My Bedwars and Ballwars
- Iron spawns 1 every 2 seconds (instead of every second)
- Fireballs cost 3 iron (instead of 40 iron)
- Bridge eggs cost 6 gold (instead of 1 emerald)
- Glass costs 2 gold for 4 glass (instead of 12 iron)

### Ballwars Strategies
- You can cover your bed using 8 glass for 4 gold. This is the only fireball-proof bed defense besides obsidian due to fireballs behaving identically to tnt
- Double-fireball-jumping by rapidly throwing 2 fireballs downwards can allow you to clear the gap between a base and the diamond island in a single jump
  - This means that teams can attack extremely early in the game
- Creating a jumping platform using ~5 blocks can let you clear the gap between islands easily with one fireball
- Bridge eggs can be used to easily reach the emerald islands
- Bridge eggs can be used to block fireballs when attacking
- Upgrading Forge with diamonds can allow you to stock up on bridge eggs and fireballs

## Pillars of Fortune
- Server for the minigame Pillars of Fortune
- See https://www.spigotmc.org/resources/moonpillars.116071/

## Party Games
- Server that I use to test my Party Games plugin
- See https://github.com/Melumi11/Party-Games for detailed documentation

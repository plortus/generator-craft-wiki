# GeneratorCraft Knowledge Dump - mob-killing

![Guild icon](https://cdn.discordapp.com/icons/1339343877743579297/0070beb6be20d8d9b95a09782c983e77.png?size=512)
GeneratorCraft Knowledge Dump
currency features / mob-killing
 
 
![Avatar](https://cdn.discordapp.com/avatars/498513173150695428/1d938f45c971fe11c92bb52faa374851.png?size=512)
ignDante
 
[2025-03-15 23:25](#chatlog__message-container-1350580700700737557)
After 
killing a mob
, Coins, Gems and Lootboxes may drop according to the player's respective chances The formulas are as such: Coin Drop amount from non monster entities = 
`((MaxHP/2)+Random[1-10])*CoinMultiplier`
 Coin Drop amount from monster entities = 
`(((MaxHP/2)+Random[1-10)+(MaxHP/2))*CoinMultiplier`
 Gem Drop amount from non monster entities = 
`((MaxHP/5)+Random[1-5])*GemMultiplier`
 Gem Drop amount from monster entities = 
`(((MaxHP/5)+Random[1-10)+(MaxHP/5))*GemMultiplier`
 If the 
Looting 
enchantment is present this amount is added(+) at the end of the formula: Coins = 
`CoinDrop*((1.5*LootingLevel)+(Random[1-10])`
 Gems = 
`GemDrop*((1*LootingLevel)+(Random[1-10])`
 Lootbox Drop: Lootboxes will drop according to your Box Chance. If the weapon has Looting there exists a formula to drop another Lootbox: if 
`Random[LootingLevel-10]`
 >= 5
 
(edited)
 
![Avatar](https://cdn.discordapp.com/avatars/498513173150695428/1d938f45c971fe11c92bb52faa374851.png?size=512)
ignDante
 
[2025-03-15 23:37](#chatlog__message-container-1350583722008772698)
Before GeneratorCraft 1.2.5, this is how your chat would look like after killing a mob
 
(edited)
[https://cdn.discordapp.com/attachments/1350575131034124369/1350583721790537810/image.png?ex=6921845b&is=692032db&hm=24cca30c43267ff6b518e8a6956ac318f7b04f687427bdb490286119f8730d8a&](https://cdn.discordapp.com/attachments/1350575131034124369/1350583721790537810/image.png?ex=6921845b&is=692032db&hm=24cca30c43267ff6b518e8a6956ac318f7b04f687427bdb490286119f8730d8a&)
 
![Avatar](https://cdn.discordapp.com/avatars/498513173150695428/1d938f45c971fe11c92bb52faa374851.png?size=512)
ignDante
 
[2025-04-13 22:54](#chatlog__message-container-1361067058661429460)
After 1.2.5, it's much more nicely organized
[https://cdn.discordapp.com/attachments/1350575131034124369/1361067058451972156/image.png?ex=692214fa&is=6920c37a&hm=9fc198fc7c77d81e73b591d693b6bb31a256006652b3e063be278235ca466612&](https://cdn.discordapp.com/attachments/1350575131034124369/1361067058451972156/image.png?ex=692214fa&is=6920c37a&hm=9fc198fc7c77d81e73b591d693b6bb31a256006652b3e063be278235ca466612&)
 
![Avatar](https://cdn.discordapp.com/avatars/498513173150695428/1d938f45c971fe11c92bb52faa374851.png?size=512)
ignDante
 
[2025-08-22 16:44](#chatlog__message-container-1408446616762978326)
Since version 1.3.7 it is possible to toggle seeing the mobkill chat message through the GeneratorCraft Store ( 
#generatorcraft-store
 )
 
 
Exported 4 message(s)
Timezone: UTC+2

---

Original HTML file: `assets/original_html/GeneratorCraft Knowledge Dump - currency features - mob-killing [1350575131034124369].html`

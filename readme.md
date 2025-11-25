# 🍽️ Dishaster
**Welcome to Dishaster — the only job where spilling drinks, dodging the boss, and flirting for tips are part of the shift!**

Dishaster is a fast-paced, humorous management and stealth game where you play as a banquet waiter working at chaotic events — weddings, galas, and bar mitzvahs.  
Your goal is simple: serve as many guests as possible, collect generous tips, and survive the night without getting caught slacking by your terrifying boss!  
Mixing time management, stealth, and comedy, Dishaster turns catering into pure chaos and laughter.

---

## 👥 Team Members
- Raphael Coeffic  
- Yanai Levy

---

## 📜 Project Files
- [Formal Elements Document](https://github.com/GenesisWarfare/Dishaster/blob/main/formal-elements.md)
- [Market Research Document](https://github.com/GenesisWarfare/Dishaster/blob/main/Market_Research.md)
- [Levels Design Document](https://github.com/GenesisWarfare/Dishaster/blob/main/Levels-Design.md)


## Core Loop

Play the game on itch.io: [Link of the game](https://genesiswarfare.itch.io/dishaster-core-loop)

### How to play:
Move with arrows, go to the food zone (right side of the kitchen) to open the food menu, click salad fish meat dessert to take food, you can carry maximum 2 food items. Go to the DRINKS zone to open the drinks menu, click water wine cocktail to take drinks, you can carry maximum 2 drinks. When a table wants to order a square flashes above the table. Press E near the table to take the order.  When a table needs to be cleaned a square appears above it without flashing. Go back to the table and press E again to serve the food and drinks if you have the correct items, when a table is dirty press V near it to pick up the trash, you can carry up to 6 trash. Go to the trash zone left of the kitchen and press V to empty your trash. You cannot take trash if you carry food or drinks. You cannot take food or drinks if you carry trash. Hold S with an empty tray to pretend you are working when the boss passes (he says you something if you work or not). Goal earn as much money as possible before the time ends


### UML

Assets
├── Prefabs
│   └── OrderCard.prefab
│
├── Scenes
│   └── SampleScene.unity
│
├── Scripts
│   ├── BossAndNPC
│   │   ├── BossVision.cs
│   │   ├── BossPatrol.cs
│   │   ├── DanceNPC.cs
│   │   └── ConeFollower.cs
│   │
│   ├── Gameplay
│   │   ├── CleanTrayZone.cs
│   │   ├── DrinkPickupZone.cs
│   │   ├── FoodPickupZone.cs
│   │   ├── GuestOrder.cs
│   │   ├── TableInteraction.cs
│   │   └── TableOrder.cs
│   │
│   ├── Managers
│   │   ├── BossMessageUI.cs
│   │   ├── GameManager.cs
│   │   └── OrderUIManager.cs
│   │
│   ├── Player
│   │   ├── FollowCamera.cs
│   │   ├── PlayerBlinkWhenPretend.cs
│   │   ├── PlayerController3D.cs
│   │   └── PlayerTray.cs
│   │
│   ├── UI
│   │   ├── DrinkMenuUI.cs
│   │   ├── EndScreenUI.cs
│   │   ├── FoodMenuUI.cs
│   │   ├── OrderCardUI.cs
│   │   └── TrayHUD.cs
│   │
│   └── Utils
│       ├── OrderUtils.cs
│       └── TimeUtils.cs
│
├── ProjectSettings
└── Packages


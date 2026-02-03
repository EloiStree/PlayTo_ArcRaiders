# PlayTo_ArcRaiders
Lets play to ARC Raiders with code.


For the keyboard
<img width="1124" height="762" alt="image" src="https://github.com/user-attachments/assets/5e650b5d-673d-45e3-a03f-bbc79ae782ac" />  
<img width="1128" height="766" alt="image" src="https://github.com/user-attachments/assets/fc0873b0-c6de-4917-822a-eb66edc8fe9b" />  
<img width="1109" height="761" alt="image" src="https://github.com/user-attachments/assets/e6052811-b490-4212-9509-3c2720384240" />   
<img width="672" height="277" alt="image" src="https://github.com/user-attachments/assets/824e15fe-9ef3-4a6e-99a9-65a6e92bd31e" />   


For the controller   
<img width="553" height="294" alt="image" src="https://github.com/user-attachments/assets/af17b1aa-0f73-4e4e-be3f-006e7f13229c" />   
<img width="501" height="450" alt="image" src="https://github.com/user-attachments/assets/f0e601b8-e6b2-474a-9bff-08d2a2c43b24" />
<img width="507" height="458" alt="image" src="https://github.com/user-attachments/assets/230df239-01d5-4d9c-974d-e0bb457a3be2" />



# Coding Challenge

## Core Actions

* Open the map for **0.1 seconds**

  * Open the map and zoom out fully in the shortest possible time
* Select **1 of 8 emotions**
* Select **1 of 8 inventory items**
* Unequip your champion (unarmed)
* Play **SOS in Morse code** using the flashlight

  * Play the entire Morse sequence in-game
* Enable autorun
* Use the currently selected object
* Open Inventory → Take Screenshot → Close Inventory
* Open Inventory → Open Map → Close Inventory
* Open System → Screenshot proximity → Close
* Open in-game menu and navigate through:

  * Inventory
  * Crafting
  * Map
  * Logbook
  * System
* Surrender a game

  * Exit the game intentionally
  * Open Settings
* Start / Stop / Toggle:

  * Voice chat to all
  * Voice chat to friends

---

## Hard Challenges

### Inventory Management

* Completely empty:

  * Backpack
  * Equipment
  * Safe Pockets
  * Quick Use slots
* Swap one Safe Pocket item with one Quick Use item
* Sell **all** inventory items

### Crafting

* Craft the following items:
  * Bandage
  * Shield Recharge
  * Smoke Grenade
  * Flash Grenade
  * Adrenaline Shot
  * Flame Spray
 
### Quest and Trades
-  Select Trader
- Buy from celeste
- Buy from shani
- Buy from Tian
- Buy from Lance
- Buy from Apollo
- Check 1 to 8 quests and screenshot  

### World Interaction

* Empty a ground loot container by navigating through its bag UI
* Empty Scrappy’s entire inventory while the menu is open
* Open the Blueprint menu

---

## Buy and Craft Challenge

### Easy

* Build basic items from the main Crafting menu
* Select the correct crafting category programmatically based on the target item

### Hard

* Use **image recognition** to identify and select what to craft

---

## Texture / UI Reading Challenge

* Detect if “Speak to All” is active
* Read:

  * Shield value
  * Health value
  * Camera rotation / degree
* Detect:

  * “E” interaction prompt on screen
  * Red oil texture on screen
  * Menu context pixel
* Read:

  * Time remaining
  * Credits
  * Coins
  * Raider Tokens
  * Player level

    * Level percentage
    * Exact XP value

---

## QA Tester Challenge

* Take screenshots of **all menu pages**
* For **every supported language**:
  * Change language
  * Restart the game
  * Repeat screenshots
* Record with OBS the store of the day
  * Or take screenshot of the full store
* Record audio gain and notify when audio is saturated
* Record spectrum and notify anomaly
    

---

## Hater Challenge (Questionable Life Choices)

* Record enemy voice chat names
* Save names and notes to a file
* Record names of players who kill you
* Compare names across encounters
* Trigger an audio alert when a match is found
* Expert:

  * Use TTS to read stored notes
* Justify vengeance internally. Preferably quietly.

---

## Anti-Spam Challenge

* Capture screenshots of friend requests
* Extract and save usernames
* If the name matches a website pattern:

  * Extract Embark ID
  * Report and block the user
  * Save the data for submission to Steam and the developers

---

## Inventory Automation Challenge

* Use pixel recognition to:

  * Identify unwanted stash items
  * Sell them automatically

---

## AI / Expert challenge

- Try to detect specific sound from the audio spectrum with MiraBox webcam
  

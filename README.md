[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: [Lachlan]
### Student number: [47396903] 

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

### 1.1. Discovery
What does the player learn? How does your encounter and broader level design facilitate learning in a way that follows good design practice?

The first scene/encounter in my level serves to inform the player of the numerous challenging level design decisions that will be present throughout the whole level. Take for instance the enemies in the first encounter, both types of enemies (spitters and chompers), as well as spikes are present in the first encounter and pose a serious threat to the player. Just before the player gets their hands on their first weapon, they must first squeeze through an area with two chompers whilst also avoiding the spikes that are present. It is almost impossible for the player to get through this area without at least getting hit once, signaling the player to my challenging level design choice of having numerous enemies attempt to overwhelm the player on the path ahead. The acid in the second encounter also presents a challenge to the player as it forces them to be patient and careful, else they will fall in and have to respawn at the nearest checkpoint.

### 1.2. Drama
What is the intensity curve? How does your design facilitate increasing yet modulating intensity, with moments of tension and relief? 

I have tried to space out the drama curve of my level so that each encounter is as engaging as the last. The first encounter is quite intense with jumping over spikes, being rushed by chompers and a spitter raining acid down from above, serving as a good introduction to the rest of the level. In the second encounter things are a bit calmer, with some simple platforming to maneuver and a few enemies to deal with, I tried to make it a little slower whilst also empowering the player by giving them the gun, although this is a red herring as the next encounter is riddled with enemies. In the third encounter, I placed the highest concentration of enemies in the whole level with three spitters and five chompers. The reason I have done this is to bring the level to its climax as sort of a last battle in the level, in place of the absent boss enemy.

### 1.3. Challenge
What are the main challenges? How have you designed and balanced these challenges to control the difficulty curve and keep the player in the flow channel?

The main challenge of my level is probably the enemy density coupled with the environmental dangers such as the spikes and the acid. I have designed the levels so that the enemies are challenging for the player to deal with, however I have balanced out this by rewarding the players hard work at defeating the enemies with numerous health items throughout the level so that the player shouldn’t really be ever low on health. The only time they get sent back to a checkpoint is through falling into the acid lake, which is part of the reason as to why I placed the acid lake in the second encounter so that the player has to traverse the acid multiple times, with a checkpoint before and after the acid so that every time they fall in they are respawned on whatever side of the lake they came from.

### 1.4. Exploration
How does your level design facilitate autonomy and invite the player to explore? How do your aesthetic and layout choices create distinct and memorable spaces and/or places?

I put much thought into how I would incite the player into exploring the level, with their being a few instances of branching pathways in the level noticeably in the first encounter, as you can jump up to the key without going through the encounter, however if you skip the encounter then you lose out on the melee attack for the rest of the game. Nothing says autonomy in level design like a big arrow pointing to where you are supposed to go. Only joking, I made the decision to put the arrow in the background tile map at the beginning of the level so that the player doesn’t get hung up on the staff pickup at the start of the level so frustratingly behind a one tile thick wall, mocking the player. In most instances throughout my level, I put the items the player needed most in the furthest parts of the encounters. You might ask why I put the key in a more accessible location than the gun in the second encounter. That is because the gun is there to reward the player for their exploration, as having the gun makes the third encounter (with all the enemies) much easier to travel through. I’d like to point out that in both the first and second encounter the player can choose to skip exploring further once they obtain the key and actually never pick up a weapon. In my opinion, a painful mistake when attempting to take on the gauntlet.

## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.1. Spikes

The spikes are the first prefab that the player encounters, lining the walls of a tight gap it is intended for the player to be hit by the spikes and take some damage, as they can then use the brief period of invincibility in order to evade the enemies and reach the staff pickup. Alternatively if the player makes the jump without being hit by the spikes they have little to no time to react to the enemies that will swarm the player.

### 2.2. Chompers

The chompers are the second prefab that the player encounters and they are there to rush the player, after the spike jump the chompers will rush the player potentially dealing damage if the player made the jump without getting injured, but ulitmately will succeed in pressuring the player to make a decision whilst taking advantage of the invulnerability after taking damage (it is very difficult to escape that area without taking damage).

### 2.3. Health Pickups

The first health pick up is in the first encounter located behind the two chompers, I put the health item there instead of where the key is because, once the player has a weapon, they will feel more inclined to jump back down and kill the chompers and not just leave them there, effectively getting two uses out of the chompers in the same encounter.

### 2.4. Weapon Pickup (Staff)

The first proper appearance of the staff pickup, not including the one at the very start of the level, was placed at the very back of the first encounter so that no matter which path you take (up or down) you still need to get past enemies without a weapon in order to obtain your weapon. I did this so that the player would feel vulnerable whilst going through the first encounter and changing that to a sense of satisfaction as they acquire a weapon and presumably use it to take down all the enemies.

### 2.5. Spitters

I put spitters after staff pick up because even though you can encounter the spitter before the staff, the designed path of the encounter will have the player finding the spitters after the staff. The spitter is guarding the key from the high ground giving it an advantageous and distanced postion maximising the spitter's abilities (long ranged attacks).

### 2.6. Keys

The first key is placed after the spitter and is put there to to reward the player for persevering through the encounter. After all, collecting the keys is the main objective of the level and it just felt suitable for the first key to be acquired upon completing the first encounter.

### 2.7. Checkpoints

The first checkpoint in the game comes after the first encounter, between the first encounter and the key door. The reason as to why I put the checkpoint so far away from the second encounter is to give the player time to think about what they did wrong (presuming they fell into the acid and had to respawn), whilst also leaving space for the health items so the player can recover their health from falling into the acid.

### 2.8. Acid

The acid is the first prefab the player encounters in the second encounter. I positioned the entire second encounter over the acid so as to instill a foreboding in the encounter in order to make for the lack of enemies in the level. The acid isn't much of a threat, however, it will absolutely catch the player off their guards if they are not careful. The acid was never meant to be a prominent challenge, more of a slap on the wrist to ensure the player is taking the level seriously.

### 2.9. Moving Platforms

Without the moving platforms in the second encounter, it would be impossible to progress. I put the moving platforms in the second encounter so that the player can pass over the acid and complete the remainder of the level. The second moving platform passes under an ledge, giving the player the ability to either jump up to where the next encounter is or to drop down and explore this quartered off region.

### 2.10. Weapon Pickup (Gun)

Travelling through the platforming "puzzle", the player will find the much anticipated gun at the top of second encounter. A reward for not just going immediately to the next encounter upon picking up the key. They gun is behind two breakable walls, I must confess that they were not my first choice in semi blocking the player. At first I tried a pressure plate and trigger door, but was unable to get the door to open, then I tried a box the player could move but this felt clunky to me. So I decided to go with the breakable walls.

### 2.11. Passthrough Platforms

The last prefab in the level is the passthrough platform, I placed this prefab last so as to give the player a shortcut back to the second encounter once they were able to collect all the keys, instead of having them go all the way back through the third encounter. I decided to all the player to skip the partial runback as there isn't anything left in the last encounter so forcing them to run back through serves no purpose. The player still needs to get past the acid lake before reaching the end, which will be tough if they are low on health as the jump isn't the easiest to make, accidentally hitting ellens head on the ceiling and falling into the acid in a miss timed jump.

## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram
(DocImages/MD.jpg)

### 3.2. Level Map – Section 1

### 3.3.	Level Map – Section 2

### 3.4.	Level Map – Section 3

## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.




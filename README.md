# School

A simple TI-BASIC game that i made in middle school years ago. The original game can be found on [ticalc.org](https://www.ticalc.org/archives/files/fileinfo/218/21871.html). It was a menu-based RPG à la [Drug Wars](http://tistory.wikidot.com/drugwars) and was filled with inside jokes/references from things at our school.

This document is intended to document the original, the final game will fill in a lot of gaps to make it more playable as a graphical game, adding more weapons and enemy types and perhaps making small changes to the storyline to be more congruent (and perhaps a bit more palatable).

# Format

The main character goes through a series of levels fighting "bad guys/gals" in order to upgrade health and weapons and eventually defeat the boss of each level. Enemies get progressively stronger as you go through.

Bosses have a short comic dialog before the fight.


# Black Market / Store

All items were purchased from the black market, which served as the main way to upgrade your health and weapons. You could buy multiple items at once as there was a number telling you how many of an item you could afford.

## Health

### Price
$10
### Effect
Health + 5
### Description
For $10 you can add 5 to your HP.

## Weapon

### Prices and effects

Weapon | Cost | Attack Increase
--- | :---: | :---:
Hands and Feet | (Default) | 0
Ruler | 500 | 15
Spitball | 600 | 25
Knife | 700 | 40
Gun | 1000 | 60
Automatic | 1500 | 100

### Description
Weapons can only be purchased individually, so to unlock the next weapon you must have purchased the one before it.

## Steroids

### Price
$20
### Effect
Attack + (Current Weapon * 2)
### Description
Steroids increase your attack according to what weapon you have.

## Beer

### Price
$100
### Effect
Attack + 20  
Health + 20
### Description
Increases your health and attack by 20 each.

# Locations

There are 13 locations in the game plus the final boss fight (which takes you back to the Principal's Office if you lose).

## Bus Stop

### Enemies
Name | Health | Attack | Pay
--- | :---: | :---: | ---
Sis' | 50 | 25 | 50
Bro' | 100 | 40 | 55
Bully | 150 | 60 | 65

### Boss

#### Name
Parent

#### Text
"Mrs. Maull will triumph! (Even though it's not the best thing for Johnny)"

#### Defeated Text
[---]

#### Health
400

#### Attack
125

#### Pay
200



## School Bus

### Enemies
Name | Health | Attack | Pay
--- | :---: | :---: | ---
Seat | 400 | 100 | 90
Bus Boy | 550 | 210 | 100
Window | 600 | 450 | 95

### Boss

#### Name
Bus Driver

#### Text
"Mrs. M gave me some twinkies to get plump with, so I joined her side."

#### Defeated Text
[---]

#### Health
1000

#### Attack
450

#### Pay
300



## School Yard

### Enemies
Name | Health | Attack | Pay
--- | :---: | :---: | ---
Worm | 900 | 850 | 150
6th Grader | 1000 | 900 | 160
Oak Tree | 2000 | 2000 | 170

### Boss

#### Name
Janitor

#### Text
"Don't tell Mrs. M. this..."  
"...but I've had a crush on her ever since I cleaned up that kid she sat on."

#### Defeated Text
[---]

#### Health
2500

#### Attack
2500

#### Pay
400



## Hallway

### Enemies
Name | Health | Attack | Pay
--- | :---: | :---: | ---
Geek | 3000 | 2750 | 200
Nerd | 4500 | 3500 | 210
Hall Monitor | 4000 | 5000 | 220
Addict | 5000 | 8000 | 230

### Boss

#### Name
Police

#### Text
"Stop in the name of Mrs. Maull!" 

#### Defeated Text
[---]

#### Health
5000

#### Attack
6000

#### Pay
500



## Classroom

### Enemies
Name | Health | Attack | Pay
--- | :---: | :---: | ---
Paper | 5000 | 4000 | 250
Desk | 5500 | 5500 | 260
Pencil Sharpener | 6500 | 7500 | 270

### Boss

#### Name
Teacher

#### Text
"Mrs. Maull is God!"  
"You: I don't believe in God!"

#### Defeated Text
[---]

#### Health
6000

#### Attack
6000

#### Pay
400



## P.E. (Huh?)

### Enemies
Name | Health | Attack | Pay
--- | :---: | :---: | ---
Soccer Ball | 6500 | 5000 | 300
Baseball | 7000 | 5100 | 310
Football | 8000 | 5500 | 320

### Boss

#### Name
Sub

#### Text
"Wait..."  
"You: There will be no waiting, you @#!^$!"

#### Defeated Text
"Wait! It's me, Mr. McNice!"  
"You: You too? I thought she got rid of you..."  
"No, but she drove me and my staff out of the office and into these crummy sub positions!"  
"She's filled the office with her P.E. cronies and devoted a room to storing..."  
"Uhhh..."  
"He dies before he finishes his sentence."

#### Health
99000

#### Attack
320

#### Pay
500



## Math Room

### Enemies
Name | Health | Attack | Pay
--- | :---: | :---: | ---
TI-83+ | 7100 | 5500 | 350
Jerry | 5500 | 5800 | 360
Ray | 8500 | 5900 | 370
Protractor | 9000 | 7000 | 380


### Boss

#### Name
Mrs. G

#### Text
"Remember, my boss, Mrs. Maull, says 1+1=3!"

#### Defeated Text
[---]

#### Health
9500

#### Attack
8000

#### Pay
600



## Science Room

### Enemies
Name | Health | Attack | Pay
--- | :---: | :---: | ---
Test Tube | 9500 | 6500 | 400
Iguana | 9900 | 6800 | 410
Biologist | 10,000 | 9000 | 420
Rocket Scientist | 11,000 | 9200 | 430


### Boss

#### Name
Mrs. Berson

#### Text
"I joined Mrs. M because she won a Nobel Prize for the equation 'Mrs. M + Twinky = fatter Mrs. M'."

#### Defeated Text
[---]

#### Health
13,000

#### Attack
10,000

#### Pay
600


## Latin

### Enemies
Name | Health | Attack | Pay
--- | :---: | :---: | ---
Damno | 12,000 | 10,000 | 450
Cockroach | 12,700 | 10,000 | 460
Declension Chart | 14,000 | 12,000 | 470
Roman Soldier<sup>1</sup> | 15,000 | 100,000 | 750

1. *The soldier will always run away if you have the "automatic" weapon, saying:* "Soldier ran away".

### Boss

#### Name
Mr. Discenza

#### Text
"Mrs. Maull speaks Latin well! She said 'Bonjour'!"

#### Defeated Text
[---] ("You: Sic semper tyrannis!")

#### Health
16,000

#### Attack
16,000

#### Pay
900


## English Room

### Enemies
Name | Health | Attack | Pay
--- | :---: | :---: | ---
Aesop | 12,600 | 12,600 | 490
Novel | 13,700 | 13,700 | 500
Grammar | 15,000 | 15,000 | 510
Billy S<sup>1</sup> | 16,000 | 16,000 | 520
1. *Shakespeare*

### Boss

#### Name
Mrs. Rust

#### Text
"I joined Mrs. Maull because she has good grammar (she's just like me!). The way she asked 'I be get the letter I'll wrote?' was poetry to my ears!"

#### Defeated Text
[---]

#### Health
19,000

#### Attack
19,000

#### Pay
700


## Social Studies
Not sure why Mr. Nixon's text is more like a P.E. teacher's...

### Enemies
Name | Health | Attack | Pay
--- | :---: | :---: | ---
Overhead Projector | 19,000 | 19,000 | 550
Robert E. Lee | 20,000 | 16,000 | 560
The President | 22,000 | 15,000 | 570
Congress | 17,000 | 1,000,000 | 550
House of Representatives | 100,000 | 1,000,000 | 1000


### Boss

#### Name
Mr. Nixon

#### Text
"Drop and give me 20!"  
"(For Mrs. M, who can't quite do one yet, but we're workin' on her...)"

#### Defeated Text
[---] ("I'm history...")

#### Health
27,800

#### Attack
15,700

#### Pay
750


## Health

### Enemies
Name | Health | Attack | Pay
--- | :---: | :---: | ---
Fruits | 20,000 | 200,000 | 590
Veggies | 28,200 | 16,000 | 600
Nutrition | 8,300 | 7,000 | 610
Crack | 28,500 | 17,200 | 620
Officer Bob | 30,000| 17,300 | 630


### Boss

#### Name
Sub 2

#### Text
"Who's Mrs. Maull?"  
"You: Don't play stupid with me!"

#### Defeated Text
[---]

#### Health
35,000

#### Attack
18,000

#### Pay
800


## Principal's Office
For some reason it seems that the Principal's office is closer to the P.E. room.

### Enemies
Name | Health | Attack | Pay
--- | :---: | :---: | ---
Soccer Player | 50,000 | 29,500 | 700
Baseball Player | 34,000 | 17,700 | 660
Football Player | 40,000 | 20,000 | 670
Runner | 32,000 | 24,000 | 650

### Boss

#### Name
Mrs. Maull

#### Text
"You will never beat me! Even if you do, I will soon arise. You mustn't underestimate the power of the Twinkie, for in time, they... will... prevail!!!"

#### Defeated Text
"You: What the +@(#! It was a fake! That #$@& %*#$@&% daughter of a #@%\^!"  
"Psst... Over here, I'll help you!"  
"Mrs. Maull got some scientists and got a cloner and cloned herself as a..."  
"..."  
"POWERFUL TWINKIE!"


#### Health
200,000

#### Attack
50,000

#### Pay
0


## Final Fight
The final fight starts with a short cutscene of Mrs. Maull talking to her cronies. After the cutscene, there's a short animation with Mrs. Maull's name scrolling onscreen.

### Pre-battle cutscene
"Mrs. Maull: How many times must I tell you! You need to train my agents. That @(#hole is killing them all!"  
"Secretary: I-I-I'm sorry, my Lord. We will train them better."  
"Mrs. Maull: NO! MORE! TWINKIES! 'TIL HE'S KILLED!"  
"Mrs. Maull: What's that I smell? Chocolate! Yes, yes, yes!"  
"You: Crap! I forgot to take my @_#\*$[' chocolate bar out of my pocket!"  
"Mrs. Maull: Come out, my dear spy."  
"You: @(#\*!"

### Stats
Name | Health | Attack | Pay
--- | :---: | :---: | ---
Twinkie Maull | 500,000 | 50,000 | 0

### Text
"You're gowen down!"

### Defeated Text
After a short victory animation:  
"You ruined your life with drugs and alcohol and you died at a very young age. But you did not die in vain! You will forever be remembered by your non-agent teachers and classmates as the great hero who destroyed Mrs. Maull. A memorial was erected in your honor."  
"You were not blamed for the death of Mr. McNice."

### Attacks
Name | Type | Formula | Text
--- | :---: | :---: | ---
Body Slam | Attack | (A-100) - (A+700) | "Twinkie Maull used body slam!"
Twinkie | Health | H * 1.8 | "Twinkie Maull ate a twinkie!"
Belly Swirl | Attack | A - (A+500) | "Twinkie Maull used fat belly swirl!"
Health Book | Attack | (A-700) - (A+1000) | "Twinkie Maull used the health book!"
Buttface | Attack | A - (A+750) | "Twinkie Maull stuck her huge butt in your face!"
Twinkie Snatch | Attack | A * 1.1 | "You see a twinkie at your feet. The next thing you know, Twinkie Maull's running right at you..."  "Ouch..."
 
### Losing
Losing shows a short animation saying "You lose". It also makes you lose all your money and takes 100 from your attack and your health.


# Fights

Fights are automated, the player just presses the [2nd] button to start each round. When either the player or the enemy's health reaches zero, the fight ends.

## Attacking
Your attack is calculated as a random number between ATK and ATK - 24. The player always attacks first. The same formula is used for enemy attacks.

## Winning
If the enemy was a boss, you get their full amount of money. Otherwise, you get a random amount of the enemy's money, from (MAX GOLD - 50) to MAX GOLD.

### Critical Kills
You have a 1 in 10 chance of getting a critical kill.

#### Text
"You hurt 'em"  
"You took all of their money and left them lying there..."

## Losing


### Text
"You lost!"  
"[enemy] took [x] dollars from you"


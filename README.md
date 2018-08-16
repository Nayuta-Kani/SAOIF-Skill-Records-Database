# SAOIF-Skill-Records-Database

A WIP database for all SAOIF data. Created specially for the Sword Art Online:Integral Factor Discord Server

Server link: https://discord.gg/IntegralFactor

## How to Help?

Firstly, thanks for offering! It's really good to have helping hands :D

Anyways, helping is rather easy, just need to copy some data and PM me the data on discord at "Nayuta Kani#0002"! Here's what you have to do:
1) State which character is the record skill for.
2) Prepare the data for the skill record you're submitting
3) Here's the tricky part:
You'll need to find the following data, and I'm gonna represent them with #. So...

### If it's a attack skill...

\#1 = the character name E.g. Asuna, Silica, Agil etc.

\#2 = the english skill record name with no spaces and in lowercase. E.g. kindxmas

\#3 = The skill record name. E.g. `Kind X'mas`

\#4 = The rarity. So say 4 starts will have 4 of `:star:`, which would be `:star::star::star::star`:

\#5 = The Element of the skill record. E.g. `Thrust`, `Thrust/Wind`

\#6 = The SP of the skill record

\#7 = The Cost of the Skill Record

\#8 = Equipment Type E.g. `1H Rapier`, `1H Sword`

\#9 = The effect of the skill record. E.g. `680% dmg (5x All Foes)［Front/Arc/Mid］/[Bonus]Your HP recovers for 30seconds (1.3%/3sec). Effect will be removed with damage`

\#10 = The link to the thumbnail of the skillrecord (if you have, if not, just leave it there). E.g. `https://i.imgur.com/7C8xRR5.jpg`

Present the data in the following form (Copy and paste, then replace the [Insert # Here] below with the actual data)
```
<div class="[Insert #2 Here]">
  <p class="name">[Insert #3 Here]</p>
  <p class="rarity">[Insert #4 Here]</p>
  <p class="element">[Insert #5 Here]</p>
  <p class="sp">[Insert #6 Here]</p>
  <p class="cost">[Insert #7 Here]</p>
  <p class="equipment">[Insert #8 Here]</p>
  <p class="effect">[Insert #9 Here]</p>
  <img src="[Insert #10 Here]" class="thumbnail"></img>
</div>

```

###If it's a passive skill...
\#1 = the character name E.g. `Asuna`, `Silica`, `Agil` etc.

\#2 = the english skill record name with no spaces and in lowercase. E.g. `longhair`

\#3 = The skill record name. E.g. `Long Hair (ラブリーウインク)`. Japanese names are optional

\#4 = The rarity. So say 4 starts will have 4 of `:star:`, which would be `:star::star::star::star`:

\#5 = The Attack of the skill record. E.g. `52`

\#6 = The Defense of the skill record E.g. `56`

\#7 = The HP Bonus of the skill record E.g. `865`

\#8 = The Cost of the Skill Record E.g. `16`

\#9 = The effect of the skill record. E.g. `[Enhance Defense 4] Defense increase by 8%, [Fluff Step 4] Defence+ with each hit
   [防御強化4] 防御力が8%上昇, [フラッフステップ4] HIT数が多い程、防御力が上昇`

\#10 = The link to the thumbnail of the skillrecord (if you have, if not, just leave it there). E.g. `https://i.imgur.com/tMswyZ0.png`

```
<div class="[Insert #2 Here]">
  <p class="name">[Insert #3 Here]</p>
  <p class="rarity">[Insert #4 Here]</p>
  <p class="atk">[Insert #5 Here]</p>
  <p class="def">[Insert #6 Here]</p>
  <p class="hp">[Insert #7 Here]</p>
  <p class="cost">[Insert #8 Here]</p>
  <p class="equipment">passive(アビリティ)</p>
  <p class="effect">[Insert #9 Here]
  <img src="[Insert #10 Here]" class="thumbnail"></img>
</div>
```

4) Send the completed data by DMing me on discord (Nayuta Kani#0002) or [make an issue here on github and put it here](https://github.com/Nayuta-Kani/SAOIF-Skill-Records-Database/issues/new)!

## Example submission:
```
Character: Asuna

<div class="longhair">
  <p class="name">Long Hair (ラブリーウインク)</p>
  <p class="rarity">:star::star::star::star:</p>
  <p class="atk">52</p>
  <p class="def">56</p>
  <p class="hp">865</p>
  <p class="cost">16</p>
  <p class="equipment">passive(アビリティ)</p>
  <p class="effect">[Enhance Defense 4] Defense increase by 8%, [Fluff Step 4] Defence+ with each hit
     [防御強化4] 防御力が8%上昇, [フラッフステップ4] HIT数が多い程、防御力が上昇
  <img src="https://i.imgur.com/tMswyZ0.png" class="thumbnail"></img>
</div>
```

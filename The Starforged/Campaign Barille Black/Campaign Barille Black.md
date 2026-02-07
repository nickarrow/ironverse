---
name: Campaign Barille Black
ironvault:
  playset:
    type: globs
    lines:
      - "@include(starforged)"
      - asset:sundered_isles/** [starforged.recommended=true]
      - oracle_rollable:sundered_isles/misc**
      - oracle_rollable:sundered_isles/overland**
      - oracle_rollable:sundered_isles/weather**
      - oracle_rollable:sundered_isles/treasure**
      - "!oracle_rollable:sundered_isles/misc/local**"
      - "*:ancient_wonders/**"
      - "*:starsmith/**"
  customContentFolder: Custom Content
iron-vault-kind: campaign
---

# [[The Starforged]]
This campaign is setup to be played in the standard Starforged setting, except it includes the recommended Sundered Isle's assets and a few Sundered Isles oracles that I think work really well in Starforged (Magnitude, size, weather, etc.). I've also added [Starsmith](https://playeveryrole.com/starsmith-products/), and [Ancient Wonders](https://ludicpen.itch.io/ancient-wonders) content because they are so freaking cool. 

I've also set this campaign up to be an [[Epistolary Guide|Epistolary]] game with a shared vow of [[Expose the darkness behind the attacks across the sector and stop it from spreading]]. Barille has sent his first message marking progress on the vow ([[Message 01 - Barille Black]]) - feel free to join in on the fun and help complete this shared vow!

We currently have several players in this campaign, [[Echo 'Phantom' Stirling]], [[Tybalt-Yhen Serrato]], [[Sable Rowe]], and [[Barille Black]]. Feel free to read along on their respective journals!

```dataview
TABLE WITHOUT ID file.link as "Journals", file.mtime as "Last Updated"
FROM "The Starforged/Journals/Barille" OR "The Starforged/Journals/Echo" OR "The Starforged/Journals/Tybalt-Yhen Serrato" OR "The Starforged/Journals/Sable"
Sort file.mtime desc
```


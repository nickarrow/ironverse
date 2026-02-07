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

Welcome to your new campaign! This is a campaign index file, which marks its folder as a campaign. Any journals or game entities inside this folder will use this campaign for any mechanics or commands. You can replace all this text with any details or notes you have about your campaign. As long as the file properties remain the same, you don't have to worry about the contents of this file.

## Included Datasets

Iron Vault includes data from various official and community rulesets and expansions. This data has been generously made available for free to community tools by their respective authors, allowing you to use Iron Vault without paying. You can control which datasets are activated in the playset settings page for your campaign.

We ask that, if you haven't already, you consider buying the source books for these rulesets and expansions when you decide to play with them in your campaign, in order to support the game creators that make this experience possible:

* [Ironsworn](https://tomkinpress.com/collections/products-for-ironsworn) ([CC-BY-4.0](https://creativecommons.org/licenses/by/4.0))
* [Ironsworn: Delve](https://tomkinpress.com/collections/products-for-ironsworn-delve) ([CC-BY-4.0](https://creativecommons.org/licenses/by/4.0))
* [Ironsworn: Starforged](https://tomkinpress.com/collections/products-for-ironsworn-starforged) ([CC-BY-4.0](https://creativecommons.org/licenses/by/4.0))
* [Sundered Isles](https://tomkinpress.com/collections/products-for-sundered-isles) ([CC-BY-NC-SA-4.0](https://creativecommons.org/licenses/by-nc-sa/4.0))
* [Ancient Wonders](https://ludicpen.itch.io/ancient-wonders) ([Print-on-demand](https://www.drivethrurpg.com/product/505365)) ([CC-BY-NC-SA-4.0](https://creativecommons.org/licenses/by-nc-sa/4.0))
* [Fe-Runners](https://zombiecraig.itch.io/fe-runners) ([CC-BY-NC-SA-4.0](https://creativecommons.org/licenses/by-nc-sa/4.0))
* [Ironsmith](https://playeveryrole.com/ironsmith/) ([CC-BY-4.0](https://creativecommons.org/licenses/by/4.0))
* [Starsmith](https://playeveryrole.com/starsmith-products/) ([CC-BY-4.0](https://creativecommons.org/licenses/by/4.0))

This campaign is setup to be played in the standard Starforged setting, except it includes the recommended Sundered Isle's assets and a few Sundered Isles oracles that I think work really well in Starforged (Magnitude, size, weather, etc.). I've also added [Starsmith](https://playeveryrole.com/starsmith-products/), and [Ancient Wonders](https://ludicpen.itch.io/ancient-wonders) content because they are so freaking cool. 

I've also set this campaign up to be an [[Epistolary Guide|Epistolary]] game with a shared vow of [[Expose the darkness behind the attacks across the sector and stop it from spreading]]. Barille has sent his first message marking progress on the vow ([[Message 01 - Barille Black]]) - feel free to join in on the fun and help complete this shared vow!

We currently have several players in this campaign, [[Echo 'Phantom' Stirling]], [[Tybalt-Yhen Serrato]], [[Sable Rowe]], and [[Barille Black]]. Feel free to read along on their respective journals! 

Need to update
```dataview
TABLE WITHOUT ID file.link as "Journals", file.mtime as "Last Updated"
FROM "The Starforged/Journals/Barille" OR "The Starforged/Journals/Echo" OR "The Starforged/Journals/Tybalt-Yhen Serrato" OR "The Starforged/Journals/Sable"
Sort file.mtime desc
```


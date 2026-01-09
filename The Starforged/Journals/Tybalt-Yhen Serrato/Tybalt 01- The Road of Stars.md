```iron-vault-mechanics
actor name="[[The Starforged\/Characters\/Tybalt-Yhen Serrato.md|Tybalt-Yhen Serrato]]" {
    move "[Begin a Session](datasworn:move:starforged\/session\/begin_a_session)" {
        meter "Momentum" from=8 to=9
    }
    move "[Undertake an Expedition](datasworn:move:starforged\/exploration\/undertake_an_expedition)" {
        roll "Edge" action=4 adds=0 stat=1 vs1=5 vs2=9
        burn from=9 to=2
    }
}
progress from=0 name="[[The Starforged\/Progress\/Tybalt-Yhen Serrato\/Reach the Devil's Chain Sector.md|Reach the Devil's Chain Sector]]" rank="formidable" steps=1
oracle name="[Space Encounter Oracles \/ Space Sighting \/ Outlands](datasworn:oracle_rollable:starforged\/space\/sighting\/outlands)" result="[Stellar Object](datasworn:oracle_rollable:starforged\/space\/stellar_object)" roll=6
oracle name="[Space Encounter Oracles \/ Stellar Object](datasworn:oracle_rollable:starforged\/space\/stellar_object)" result="Neutron star surrounded by intense magnetic fields" roll=77

```

It was, perhaps
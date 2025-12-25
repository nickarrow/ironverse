| Name               | Reck                                          |
| ------------------ | --------------------------------------------- |
| Location           | Planetside                                    |
| Population         | Thousands                                     |
| First Look         |                                               |
| Settlement Trouble | Terrifying manifestations, Someone is missing |
|                    | asdf                                          |
|                    | asdf                                          |
|                    |                                               |

```iron-vault-mechanics
oracle-group name="Settlement: Hypatia" {
    oracle name="[Templates \/ Region](datasworn:oracle_rollable:starforgedsupp\/core\/region)" result="Terminus" roll=24
    oracle name="[Settlement Oracles \/ Settlement Name](datasworn:oracle_rollable:starforged\/settlement\/name)" result="Hypatia" roll=35
    oracle name="[Settlement Oracles \/ Location](datasworn:oracle_rollable:starforged\/settlement\/location)" result="Orbital" roll=44
    oracle name="[Population](datasworn:oracle_rollable:starforged\/settlement\/population\/terminus)" result="Thousands" roll=57
    oracle name="[Settlement Oracles \/ First Look](datasworn:oracle_rollable:starforged\/settlement\/first_look)" result="Obvious social stratification" roll=60
    oracle name="[Settlement Oracles \/ Initial Contact](datasworn:oracle_rollable:starforged\/settlement\/initial_contact)" result="Destroyed" roll=94
    oracle name="[Settlement Oracles \/ Authority](datasworn:oracle_rollable:starforged\/settlement\/authority)" result="None \/ lawless" roll=11
    oracle name="[Settlement Projects](datasworn:oracle_rollable:starforged\/settlement\/projects)" result="Agriculture" roll=2
    oracle name="[Settlement Projects](datasworn:oracle_rollable:starforged\/settlement\/projects)" result="[Action](datasworn:oracle_rollable:starforged\/core\/action) + [Theme](datasworn:oracle_rollable:starforged\/core\/theme)" roll=100 {
        oracle name="[Core Oracles \/ Action](datasworn:oracle_rollable:starforged\/core\/action)" result="Secure" roll=85
        oracle name="[Core Oracles \/ Theme](datasworn:oracle_rollable:starforged\/core\/theme)" result="Vengeance" roll=93
    }
    oracle name="[Settlement Trouble](datasworn:oracle_rollable:starforged\/settlement\/trouble)" result="Deprived of a resource" roll=23
    oracle name="[Settlement Trouble](datasworn:oracle_rollable:starforged\/settlement\/trouble)" result="Changing environment" roll=9
}
```


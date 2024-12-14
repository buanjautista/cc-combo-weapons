# Combo Weapons

A mod that allows equipment items to combo with other equips for extra hidden stats. 
This mod requires [Item Api](https://github.com/CCDirectLink/item-api/).

## Usage:
Add the "combo" tag to one of the item db entry, to match the customItem tag of the combo item; then add "comboProperties" for the stats when the combo is active.
```
            "combo": "ct-equip-leftsword",
            "comboProperties": {
                "ASSAULT": 1.75,
                "OVERHEAT_REDUCTION": 1.3,
                "DASH_INVINC": 1.3,
                "GUARD_STRENGTH": 1.3
            }
```
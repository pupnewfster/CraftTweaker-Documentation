# CTSkill

CTSkills exist for both custom skills, and skills built into Reskillable.

| ZenGetter/ZenMethod   | ZenSetter/ZenMethod | Type     |
|-----------------------|---------------------|----------|
| key                   |                     | string   |
| name                  |                     | string   |
| backgroundLocation    |                     | string   |
| enabled               | enabled             | boolean  |
| cap                   | cap                 | int      |
| hidden                | hidden              | boolean  |
| skillPointInterval    | skillPointInterval  | int      |
| getLevelUpCost(level) |                     | int      |
| baseLevelCost         | baseLevelCost       | int      |
| levelStaggering       | levelStaggering     | string[] |

`compareTo(CTSkill other)` returns 0 if this CTSkill has the same name as the other CTSkill. 
A collection of simple drop-in levelgens. Check source code for configuration
options.

# base_control.levelgen

## Examples

[Base Control](http://bitfighter.org/levels/levels/view/374) - kaen

## Overview

Adds "base control" to zone control games. When a zone is captured, nearby
Turrets and Forcefields are switched to the capturing player's team. Objects
belong to the GoalZone closest to them, and are owned by the team which
controls the zone. Objects are healed when a zone is captured by a new team.
When a team scores a touchdown, it loses control of all objects belonging to
goal zones, and the objects are set to 0 health.

## Exemptions

Objects with an ID number higher than 9000 are exempted from ownership changes.
You can use this to make certain objects obey normal rules instead of changing
owners.

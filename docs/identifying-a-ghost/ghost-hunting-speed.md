---
sidebar_position: 3
---

# Ghost Hunting Speed

## Default Behavior

Ghosts move at a base speed of 1.7 m/s during a hunt. When the ghost can see you, they will slowly increase their speed eventually reaching a top speed of 2.8 m/s. When the ghost cannot see you it will return even more slowly back to it's original speed.

## Conditional Behavior

The following ghosts follow the default speed rules, but under certain conditions will ignore them.

**Jinn**:

If a jinn...

- can see a player
- that player is farther than 3 m away
- and the fuse box is on

then it will move at a fixed speed of 2.5 m/s. Otherwise, it will behave like a standard ghost.

**Moroi**:

A moroi will have a greater base and maximum speed when average sanity is lower

| Average Sanity (%) | Base Speed (m/s) | Max Speed (m/s) |
| ------------------ | ---------------- | --------------- |
| 45 +               | 1.5              | 2.4             |
| 40 - 45            | 1.6              | 2.6             |
| 35 - 40            | 1.65             | 2.75            |
| 30 - 35            | 1.75             | 2.9             |
| 25 - 30            | 1.85             | 3.0             |
| 20 - 25            | 1.9              | 3.15            |
| 15 - 20            | 2                | 3.3             |
| 10 - 15            | 2.1              | 3.45            |
| 5 - 10             | 2.15             | 3.55            |
| 0 - 5              | 2.25             | 3.7             |

**Raiju**:

Depeding on the map size, the raiju will move at a fixed rate of 2.5 m/s if within a specific range of electronics.

| Map Size | Distance to Electronics (m) |
| -------- | --------------------------- |
| Small    | 6                           |
| Medium   | 8                           |
| Large    | 10                          |

**The Twins**:

The twins have 50% chance to hunt with a base speed of 1.53 m/s and a 50% chance to hunt with a base speed of 1.87 m/s.

## Exempt Behavior

The following ghosts ignore the default speed rules in favor of some other ruleset.

**Deogen**:

The deogen will range from 0.4 m/s (when within 2.5 m of the player) and 3 m/s (when further than 6 m from the player). If smudged, the ghost will retain it's previous speed with a max of 1.6 m/s.

**Hantu**:

Hantus will be faster when the room is colder ranging from 1.4 m/s to 2.7 m/s.

**Revenant**:

The revenant moves at 1 m/s when wandering and 3 m/s when chasing. If a player is lost after being chased, it will quyckly return to 1 m/s.

**Thaye**:

A thaye begins its life at 2.75 m/s and drops 0.175 m/s each time it ages down to 1 m/s.

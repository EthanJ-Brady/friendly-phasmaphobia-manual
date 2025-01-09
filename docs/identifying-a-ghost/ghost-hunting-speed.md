---
sidebar_position: 3
---

# Ghost Hunting Speed

## Default Behavior

Ghosts move at a base speed of 1.7 m/s during a hunt. When the ghost can see you, they will slowly increase their speed eventually reaching a top speed of 2.8 m/s. When the ghost cannot see you it will return even more slowly back to it's original speed.

## Conditional Behavior

**Jinn**:

If a jinn...

- can see a player
- that player is farther than 3m away
- and the fuse box is on

then it will move at a fixed speed of 2.5m/s. Otherwise, it will behave like a standard ghost.

**Moroi**:

A moroi will have a greater base and maximum speed when average sanity is lower

| Average Sanity % | Base Speed m/s | Max Speed m/s |
| ---------------- | -------------- | ------------- |
| 45 +             | 1.5            | 2.4           |
| 40 - 45          | 1.6            | 2.6           |
| 35 - 40          | 1.65           | 2.75          |
| 30 - 35          | 1.75           | 2.9           |
| 25 - 30          | 1.85           | 3.0           |
| 20 - 25          | 1.9            | 3.15          |
| 15 - 20          | 2              | 3.3           |
| 10 - 15          | 2.1            | 3.45          |
| 5 - 10           | 2.15           | 3.55          |
| 0 - 5            | 2.25           | 3.7           |

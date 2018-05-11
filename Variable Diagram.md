# ZONK Variable Diagram

## A
- Miscellaneous menu input

## B
- Battle choice

## C
- Mod activation choice

If C=0, the mod assumes ZONK is just getting started, and the creator's name is moved to Str2 for display in the initial menu. The creator's name must be sixteen characters or less.

If C=1, the mod assumes ZONK is trying to get a character and picks one out.

If C=2, the mod assumes the player has made a move in ZONK and calculates the effect on both the enemy and the player.

## D
- Character choice

The mod randomizes D between 1 and the number of enemies it has, for use in identifying the effects in battle.

## E
- Enemy health

## G
- Player gold

## H
- Player health

## R
- Room number (counts down from 100)

## T
- Thief's loot

## Spare variables:
A, F, I, J, K, L, M, N, O, P, Q, S, U, V, W, X, Y, Z, θ

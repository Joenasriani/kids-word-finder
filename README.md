# WORD FINDER

Play: https://joenasriani.github.io/kids-word-finder/

WORD FINDER is an eight-level bilingual word-search game developed as part of a multi-game interactive children’s edutainment activation in the UAE.

## Game structure

Each level generates a square letter grid and places three target words in horizontal, vertical or diagonal directions, including reversed directions. The player selects adjacent letters in a straight line by dragging with a mouse or touch input.

**generate grid → place three target words → drag across letters → validate selected word → mark found word → find all three → advance level**

The grid expands with progression:

- Level 1: 3×3
- Level 2: 4×4
- Level 3: 5×5
- Level 4: 6×6
- Level 5: 7×7
- Level 6: 8×8
- Level 7: 9×9
- Level 8: 10×10

## English and Arabic modes

The game includes separate English and Arabic word pools. Switching to Arabic changes the interface language, applies right-to-left layout behavior and displays level/grid numbers with Arabic-Indic digits.

## Interaction details

- exactly three target words are selected for each level;
- overlapping found words can share letters and display combined color treatment;
- the mascot reacts to valid and invalid selections;
- fullscreen and home/reset controls are built into the game;
- completing Level 8 opens the final victory screen.

## Activation context

This game belongs to the same `kids-*` game set developed for the multi-game interactive children’s edutainment activation in the UAE.

## Evidence boundary

The repository implements bilingual word-search play. It does not contain a study measuring vocabulary acquisition, reading development, language learning, memory improvement or transfer outside the game.

## Repository scope

The playable implementation is contained entirely in `index.html`.

`index.html` is preserved as the game artifact. Documentation and discovery files must not alter the word pools, grid generation, word placement, selection rules, level progression, language behavior, controls, visuals, mascot behavior or runtime behavior.

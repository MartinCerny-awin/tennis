# Tennis-test

Goal: Re-create a game of tennis including:

    - 2 players
    - The basic rules of Tennis
    - Some tests (using `Jest`) to certify that the logic is working as expected

### Basic Rules of Tennis
    - Players scores one at a time
    - The score of a player increments in the following way: 0 - 15 - 30 - 40
    - When only one player has score 40 and he scores, then this player wins. Return `player x wins`
    - When both players have score 40, then return `deuce`
    - When player scores and there is deuce, then the scoring player gets advantage. Return `player x adv`
    - When player has advantage and scores again then this player wins. Return `player x wins`
    - When player has advantage and the other player scores, it goes back to `deuce`

### Out of scope
    - We are counting only one set
    - There is no need to reset the score after one player wins

## Available commands:
    - npm test (runs the `test.ts` file with jest)

# Rock-Paper-Scissor-Game

Basic Web Game using HTML5, CSS3, JS

## Author
[@ZAID](https://fiverr.com/users/zaidqaiser3)

## PREVIEW:
![1](https://github.com/zaidqaiser/Rock-Paper-Scissor-Game/assets/114343092/90735019-a642-4f1a-b63c-801121c4e8ec)
![2](https://github.com/zaidqaiser/Rock-Paper-Scissor-Game/assets/114343092/5bddb503-46e5-4626-a166-3fcaa4e918ec)

## Game Logic

1. **User Makes a Choice**:
    - The function starts by noting the user's choice.

2. **Computer Makes a Choice**:
    - The computer randomly picks between "rock", "paper", and "scissors".

3. **Check for a Draw**:
    - If the user's choice is the same as the computer's choice, the game is a draw and a message indicating this is displayed.

4. **Determine the Winner**:
    - If it's not a draw, the function checks which choice beats the other:
        - "Rock" beats "Scissors".
        - "Paper" beats "Rock".
        - "Scissors" beat "Paper".
    - Based on this comparison, it determines whether the user or the computer wins.

5. **Update Scores and Messages**:
    - If the user wins, their score is increased by one, and a winning message is displayed.
    - If the computer wins, its score is increased by one, and a losing message is displayed.

6. **Repeat the Process**:
    - Event listeners ensure that each time the user makes a choice, the game logic is executed again.

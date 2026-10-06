# Cops and Robbers

An application designed to simulate a game named "Cops and Robbers". A user (player) identifies themselves using their first and last name. The game takes place in a room paved with square grid tiles (cells), enclosed by outer walls and containing inner wall obstacles. Inside the room, there is a cop (guard) and a robber. The player's goal is to guide the robber safely to the room's exit. Both the robber and the cop move one tile at a time across any of the eight adjacent cells (Moore neighborhood).

Multiple scenarios must be supported. For each scenario, the movement strategy of the cop is controlled by a probability $K$:

    In K% of cases, the cop moves randomly into one of the eight valid adjacent tiles (walls permitting);
    In (100 − K)% of cases, the cop's direction is calculated using the Ant Colony Optimization (ACO) algorithm.

Additionally, colored items are available in the room for the robber to pick up:

    Green - The cop moves in the opposite direction of the robber for 10 seconds.

    Yellow - The cop moves in a random direction for 10 seconds.

    Red - The cop moves toward the exit (using Ant Colony Optimization).

The game management software displays the leaderboard showing the best scores achieved by all players across all matches (fewest steps taken to reach the exit) at the start and end of every game.

<br><br>
![gif1](https://github.com/user-attachments/assets/1390b381-5948-489a-878a-243c325943bb)
<br><br>
![gif2](https://github.com/user-attachments/assets/db13b924-5f91-4f23-a4d1-cc8fbcd569cd)
<br><br>
![gif3](https://github.com/user-attachments/assets/0deae5f7-5b69-4e2b-bd56-ecd09d453548)
<br><br>
![gif4](https://github.com/user-attachments/assets/b768e635-782c-43ff-8698-5b3b7977d7c2)
<br><br>
![gif5](https://github.com/user-attachments/assets/0a35ba3b-3ac0-4afa-ad66-62ba6a128ab8)
<br><br>

Devs:
- [Dk000t](https://github.com/Dk000t)
- [MrHide](https://github.com/Atymia)

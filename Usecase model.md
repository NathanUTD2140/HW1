## Abstract and Highlevel Usecase
|UC1. User logins into the game |
| --- |
|TUCBW: The player enters in their login credentials and sees their account details.      |
|TUCEW: The player log outs of their session or begins a new game.                        |

|UC2. User begins a new game |
| --- |
|TUCBW: The player enters in their login credentials and selects to start a new game attempt.|
|TUCEW: The player selects to quit out of the game or finished the game's content.|

## Usecase Text

|UC1. User logins into the game |
| --- |
|Precondition: The game is already up and running.|

| Actor: player | System: Adventure Time Game |
| :---: | :---: | 
|1- TUCBW: The player enters in their login credentials and sees their account details.| 2- Game checks to see if their is an account with their login credientials 2a.The login credentials match, and the player is able to see previous scores. 2.b Login credentials are not identified as valid, asks to enter in information again if the username is already in use. 2.bi Tells then if they're a new user to select a different username. 2.c Game is unable to identify user, creates a new account for the user with username. 2.ci User is able to confirm username and password for the game, and a new user is created for them|
|3a. The user is able to view previous highscores of the game, before and are asked if they want to start a new game. | |

|Postcondition: The user has been logged in, and the score is now being stored for the user. |
| --- |


|UC2. User begins a new game |
| --- |
|Precondition: The user has logged in. |


| Actor: player | System: Adventure Time Game |
| :---: | :---: | 
|1- TUCBW: The player enters in their login credentials and selects to start a new game attempt.| 2- Game loads the obstacle course structure that the player must interact with for the game, and starts keeping track of the player's score.|
|3. The player navigates the course with their input device, navigating it until the end of the course. 3a. The player avatar has failed the course, resulting in their progress being taken  | 4. Fails the course, the system readjusts their position to be in a different spot from their failure. |
|5. The player reaches the end of the course. | 6. The player's score is calculated from a timer and stored into their account credentials|
|7. The player exits out of the game, or chooses to play the game again. ||

|Postcondition: The user has been logged in, and the score is now being stored for the user. |
| - |

## Usecase Diagram

![Image of the Usecase Diagram](https://github.com/user-attachments/assets/ff1764d8-256d-481e-9457-5503de75b3b4)





# RETD college - C Language For Embedded: Final project, BlackJack game.
Haim Ozer
Student I.D: 316063569  
Date: 18/08/2024 ~ 20/9/2024 
Lecturer: Shmuel 

--------------------------------------------------------------------------

# BlackJack

Running the Blackjack Game
To compile and run the Blackjack game, use the following commands:

1. Compile the game:
   gcc main.c game.c deck.c hand.c card.c game_state.c game_phases.c visuals.c -o blackjack

2. Run the game:
   ./blackjack.exe

--------------------------------------------------------------------------

Running the Test Suite
To compile and run the test suite for verifying the card encoding, linked list operations, and scoring logic, use the following commands:

1. Compile the test suite:
   gcc test_blackjack.c card.c deck.c hand.c -o test_blackjack

2. Run the test suite:
   ./test_blackjack.exe
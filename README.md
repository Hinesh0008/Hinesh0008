
<!---#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    int guess, number, attempts = 0;
    char playAgain;

    // Seed the random number generator
    srand(time(0));

    do {
        // Generate a random number between 1 and 100
        number = rand() % 100 + 1;

        printf("Welcome to the Number Guessing Game!\n");
        printf("I have picked a number between 1 and 100. Try to guess it.\n");

        // Reset attempts counter for each new round
        attempts = 0;

        // Game loop
        do {
            printf("Enter your guess: ");
            scanf("%d", &guess);
            attempts++;

            if (guess < number) {
                printf("Too low! Try again.\n");
            } else if (guess > number) {
                printf("Too high! Try again.\n");
            } else {
                printf("Congratulations! You've guessed the number %d in %d attempts.\n", number, attempts);
            }
        } while (guess != number);

        // Ask the player if they want to play again
        printf("Do you want to play again? (y/n): ");
        scanf(" %c", &playAgain);  // Space before %c to consume newline character

    } while (playAgain == 'y' || playAgain == 'Y');

    printf("Thank you for playing! Goodbye.\n");

    return 0;
}
Hinesh0008/Hinesh0008 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

## Psuedocode

# What starting data does my application need to run

- Questions and answers

    - Array list for all the questions

        [President, etc. ]

    - Each question will be an object
        '''
        {
            question: "who is the president?",
            multipleChoiceOptions: [
                "Obama"
                "Shakira"
            ],
            correct: "alert"
        }

- Timer / Score

# What kind of actions does my application need to do

-Needs to start the quiz
function startGame() { ... }

    -hide welcome message
    function hideWelcome() {...}

    -display the question
    function displayQuestion() {...}

    -start the countdown timer
    function startCountdown() {...}

- validate the users choice

    - if the choice is wrong, subtract time from the timer

- display the next question

- display the answer result

-end the game

    - Stop the timer from counting down (clearInterval)
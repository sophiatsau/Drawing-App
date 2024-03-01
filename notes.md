* Physics game with drawing element
* Quick, Draw! Google game, AI based
    * simple ver: alphabet? chinese chars?
* Skribblio, but 1 player at a time:
    * draw a # of prompts
    * guess a # of prompts
    * telephone game?
    * score:
        * avg # of guesses / time to guess prompt
    * option to guess, option to draw

    * accounts
    * leaderboard
        * total score
        * avg score?
        * score for guesses
        * score for drawings

    * User
        * artistScore
        * guessScore

    * add Drawing
        * userId
        * picture
        * prompt
        * list of attempts

    * add Guess
        * correct? (0 or 1)
        * guess (str)

    * class: Attempt
        * userId
        * list of guesses
        * drawingId
        * score

    * max 10 guesses
        * score = 10 - # guesses

    * Draw your own character

# Structure
 - Golang backend
 - React frontend

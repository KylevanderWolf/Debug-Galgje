## NO PROBLEMS
step 1: Cloning the Github repository

## PROBLEMS
Step 2: Npm install, found 7 vulnerabilities (1 low, 2 moderate, 4 high)
Step 3: Npm Audit, Run: npm install react-scripts@4.0.3  to resolve vulnerabilities

## FIX BUGS
step 4: Problem is in the isGameOver function, you had 1 too many tries
step 5: Problem Fixed by replacing "> game.maxGuesses" to ">= game.maxGuesses" in the isGameOver function
step 6: BUG FIXED
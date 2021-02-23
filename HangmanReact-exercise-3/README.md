## NO PROBLEMS
step 1: Cloning the Github repository

## PROBLEMS
Step 2: Npm install, found 7 vulnerabilities (1 low, 2 moderate, 4 high)
Step 3: Npm Audit, Run: npm install react-scripts@4.0.3  to resolve vulnerabilities

## FIX BUGS
step 4: GameOver component set "props.wordGuessed" directly to true
step 5: the Bug should be in the higher order Component (App.js) where the function wordGuessed is declared
step 6: The problem is in the filter method, it should be "!guessedLetters"
step 7: BUG FIXED
# NCAA-Random-Bracket
Very inelegant R code for generating a full NCAA bracket. Uses the Firstround file (saved as a .csv) to create a random sample from the Bernoulli distribution with number of observations equal to the number of games in a round (RNG seed can be changed via the set.seed value), and then assigns high seed victories to games drawing a 1 and low seed victories to games drawing a zero (I interpret high seed to be <8 and low seed to be >8, etc.).

To use:
1. Download R (http://www.r-project.org/)
2. Save the Firstround file as a csv to your computer.
3. Open the Bracketgenerator file as a script in R.
3. Change line 3 of the R code to your working directory (wherever you saved the Firstround file. setwd() establishes the working directory in R).
4. Run the Bracketgenerator script. It will generate tables specifying region and seed victors for each round of games.

This is probably riddled with mistakes and such because I am bad at R. Feel free to improve. 

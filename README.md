# NCAA-Random-Bracket
R code for generating a full NCAA bracket. Uses the Firstround file (saved as a .csv) to pick regional champions through random sampling from the Bernoulli distribution (sample length for each round equals the number of games in that round). Regional champions then winnowed to nat'l championship game and tourney winner in a similar fashion. 

To use:
1. Download R (http://www.r-project.org/)

2. Copy paste the Firstround file into Notepad and save that file as a .csv (comma separated values).

3. Open the Bracketgenerator file as a script in R.

3. Give the R script your working directory, the filename of your first round file, and an integer seed in the specified locations.

4. Run the Bracketgenerator script. It will generate tables specifying region and seed victors for each round of games.

This is probably riddled with mistakes and such because I am bad at R. Feel free to improve. 

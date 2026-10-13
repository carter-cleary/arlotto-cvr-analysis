This GitHub repo contains my R code for the cleaning, tidying, and analyzing of 
CVR data for various elections, states, and counties for research under Dr. 
Arlotto at Duke University's Fuqua School of Business.

All data is stored on my MacBook, so code is reproducible with the data and some 
tweaks to the raw data import code so it can appease your device's storage of 
the files.

For Allen and Auglaize counties in 2024, the Republican running for state senate 
ran unopposed. Because of this, I removed the state senate choice as a condition 
for party-line voting for both counties in 2024, though this does cause a 
peculiarity where the amount of voters displayed in the table showing 
proportions presents the total amount of voters as half of the amount that 
voted in 2020.
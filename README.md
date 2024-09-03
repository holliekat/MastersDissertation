# MastersDissertation
The full VADER script used to process text comments to calculate a neutrality score. 

The script shown is the whole python script I have used to calculate a neutrality score from text via Instagram comments. I have put notes (# [note] ) throughout the script as this has helped me create and change the script from start up until the final script, but it will hopefully explain to whoever is viewing this my process too. 

I do not have a computer science background, and so some of this script is inefficient, but it worked successfully and provided me with accurate results. 

The only challenge and limitation I found with the final script was that the VADER I used did not process emojis, and as I was processing Instagram comments, there were emojis present in some of the comments, and so the comments which were solely emojis have been excluded from my data analysis results. The comments which contained both text and emojis have been included in my data analysis results as an emoji would give a neutral (0) value in this VADER script, and so does not impact the overall neutrality score of the text. 

I hope you enjoy looking through this script! 

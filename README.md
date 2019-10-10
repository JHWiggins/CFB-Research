# CFB-Research
A repository for the storage of all files pertaining to statistical analysis with College Football Games. Basically whenever I write up a game summary, the codes will be put here.

## Project Explination

The purpose of this project is to take an analytical approach to looking at football games in order to understand why certain coaching decisions were made, as well as how the game unfolded. These overviews will consist of the following parts:

- Preview of Game
- Play by Play Analysis
- Formational Statistics
- Full Game Statistics
- Final Thoughts

These reports / blogs / whatever I end up calling them, will get posted to a personal website, and probably linked on reddit in addition to being hosted here. The repository will remain public in order to allow the people to see the process and provide feedback and use the tools for themselves (If you're reading this hello!).

## Code Goals

All codes will be written in Python 3.7.4 (or the latest version), with the possibility of C# being used as well. The major goal is to be able to input the play by play and have it stored in a pandas dataframe. From this data frame, all the math and such will be calculated.

All code is valid that contains the following in the header:

	# CODE IS VALIDATED BY USER JHWIGGINS.
	# VALIDATION DATE XX-XX-XXXX

For streamlining purposes a GUI input will be used to track the inputs of the play by play in order to allow for faster data input. In order for replication purposes, a spreadsheet of all the reponses will be uploaded as well through a df.to_excel('fileName.xlsx') dump.

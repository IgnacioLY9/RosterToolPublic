# Use
Open the notebook in google colab and download the file rosterInput.csv.

## Running the notebook
Click "Run all" at the top of the notebook. After that, there are only two things the user must do. The first is changing the number of athletes that can compete, and the second is changing the number of athletes that compete on each event. This is done by changing the variables NumberOfAthletesOnTeam and NumberOfAthletesPerEvent, respectively. These variables are located in the second code cell of the notebook. The second thing is clicking the white "Choose Files" button under the third cell and selecting the filled out rosterInput.csv file.

## Creating the input
It is recommended that you use the provided rosterInput.csv as a template. The following instructions are written as if the csv is being viewed in Excel. The top left cell should be left empty. The first column consists of the name of the apparatus, followed by the names of the athletes with scores on that event. The names of the apparatus must be 'Floor', 'Horse', 'Rings', 'Vault', 'Pbars', 'Hbar' and appear in that order. The first row, except for the first cell which is empty, contains the names of the competitions. It does not matter what they are called. The row containing the name of the apparatus contains the weights assigned to each event. The weights are all relative. For example, 1,1,2 is the same as 2,2,4. For a competition that has not occurred yet, the weight MUST be set to 0. If the weight is not set to 0, the score calculation will produce incorrect results. The entry, except for the top left cell, should be thought of as a solid rectangle. There must be an entry in every cell. If an athlete did not compete on an apparatus at a specific competition, but has/will compete on that apparatus, the score needs to be entered as -1. A score of 0 indicates that the athlete scored a 0.

## Interpreting the output
The output is most easily interpreted if viewed in something like Excel. The output gives the best teams by final score up to the 10 best teams. For each event, the athletes are listed in order of their scores, with the highest expected score being placed at the top of the column.

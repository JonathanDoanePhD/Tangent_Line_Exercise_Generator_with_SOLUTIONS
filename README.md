# Tangent_Line_Exercise_Generator_with_SOLUTIONS
This .tex document utilizes Python (\usepackage{pythontex}) in order to generate NumProb=*Your Choice* many tangent line exercises, with SOLUTIONS!

Software that I use in this project:

LaTeX (compiled by TexStudio on Windows)
Python 3.9 (Windows)


To generate a number of tangent line exercises, simple open the .tex document and choose how many problems, e.g. NumProb=104, you would like to generate!  
NumProb is within the \begin{document}, and within the first \begin{sympycode}.  
NumProb is also within:

###################
#QUICK START


#END OF QUICK START
###################

Finally, after choosing your NumProb, compile the .tex file (with TexStudio or similar), 
open the command propmt and choose its directory to match the save location of the .tex document (e.g. cd doane\Documents\LaTeX\Example *ENTER* if my .tex document is located in the folder "Example" under the indicated folder path); type in python pythontex.py DOCUMENTname *ENTER* within the command propmt (having Python already installed on your device),
and lastly re-compile the .tex document!

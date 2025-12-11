# DNA-Hydrogel-Assistant
DNA Hydrogel Design Assistant: Toolkit for designing, predicting, and visualizing DNA-functionalized PEGDA hydrogels.

How to Run the Program

In order to run the program, open the .py file on your IDE. Because no mode is provided, the program will display a startup prompt: 

“No mode specified. Choose how you want to run the program:
Interactive Menu
Default Recipe Suggestion
GUI (Graphical Interface)
 Enter 1, 2, or 3 (default 1):”

Start with default (1) to launch the interactive menu.
Interactive Menu Mode
Run: python FinalProject1.py
Then choose from the menu:
Suggest a hydrogel recipe
Plot stiffness curve
Plot diffusion vs PEGDA wt%
Plot DNA crosslink effect
Run self-tests
Launch GUI
Exit


This mode allows you to explore all features without having to change the parameters of the file or utilize a terminal.

Default Recipe Suggestion

If you select option 2 at startup, the program will print a default hydrogel recipe using standard settings, along with predicted stiffness, mesh size, diffusion coefficient, and photopatterning resolution. A JSON copy of the recipe is then saved in: outputs/recipe_suggestion.json


Graphical Interface

To launch the GUI directly, press 3

A window will open that will allow you to input stiffness, crosslink level, and patterning priority. The GUI displays a formatted recipe with predicted properties.

Dependencies Needed

Python 3

Numpy
Pandas
Matplotlib
Tkinter

Note: All predicted properties/equations are based on simplified models from literature on hydrogel physics.


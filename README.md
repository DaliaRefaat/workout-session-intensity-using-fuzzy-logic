# workout-session-intensity-using-fuzzy-logic
Fuzzy Logic-Based Workout Session Intensity Calculator

This Python script employs fuzzy logic to determine an appropriate workout session intensity based on input parameters such as heart rate, sleep quality, and energy level. Fuzzy logic allows for a more human-like decision-making process by considering the uncertainty and ambiguity in these inputs.

Features:
Imaginary Dataset Generation:

Simulates a dataset with random values for heart rate, sleep quality, and energy level as input features.
Fuzzy Membership Functions:

Defines fuzzy membership functions for the input variables (heart rate, sleep quality, energy level) and the output variable (workout routine intensity).
Membership functions are visualized for better understanding.
Fuzzy Rules and Inference:

Defines fuzzy rules to interpret the input values and determine the workout intensity.
Example rules include considering low heart rate, poor sleep quality, or low energy level for a light workout, and combinations for moderate and intense workouts.
Defuzzification:

Utilizes the centroid method for defuzzification to obtain a crisp output from the fuzzy result.
Visualization:

Plots the assumed input values on the fuzzy membership functions for better interpretation.
Example Usage:

Includes a function (make_assumption_and_plot) for making assumptions about heart rate, sleep quality, and energy level, and visualizing the resulting workout routine intensity.
Example Usage:

![visualizations](https://github.com/DaliaRefaat/workout-session-intensity-using-fuzzy-logic/assets/125277143/c2bb0018-6b34-41ba-9ef7-db60f35b07e7)

# Example assumption and plot
make_assumption_and_plot(120, 1, 10)

Dependencies:
pandas
numpy
scikit-fuzzy
matplotlib

How to Run:
Ensure dependencies are installed (pip install pandas numpy scikit-fuzzy matplotlib).
Run the script, and modify assumptions as needed.

Note:
This script serves as a demonstrative tool for understanding how fuzzy logic can be applied to fitness-related decision-making. Users can adapt and extend the code for real-world scenarios by incorporating more sophisticated rules and additional input variables.

Feel free to explore, modify, and contribute to enhance the functionality and usability of this fuzzy logic-based workout intensity calculator!

Central Tendency Functions (Core)

1) Open a new Colab notebook.

2) Run a code cell with the lists of temperature data:

Lists of Fahrenheit temps
week_1 = [45, 55, 49, 60, 52, 55, 58]
week_2 = [51, 49, 62, 50, 53, 56, 59]
week_3 = [60, 60, 61, 62, 57, 59, 58]
week_4 = [59, 63, 62, 61, 65, 66, 62]
copy
3) Add the imports you will need to find the mean, median, and mode

4) Use functions from the imported packages to find the mean, median, and mode for the week_1 data.

5) Now, rather than having to call each of these functions separately to get the three measures of central tendency, write a custom function to return all three values in a single function call:

Name the function "central_tendency" and start with a single positional argument that accepts the list of temperatures.
Define three variables as mean_temp, median_temp, and mode_temp using the existing functions from NumPy and the statistics module.
Add a return statement to return all three variables.
6) Test the function by calling it on week_1 data.

7) Create a modified version of the central_tendency function to include a keyword argument with the default set to verbose = True

Add conditional statements within the function so that if verbose = True, the function will print:
The mean is ___.

The median is ___.

The mode is ___.

(Hint: use f-strings to fill in the blanks with the appropriate information)

If verbose = False, the function will just return the mean, median, and mode values without the print statements.
8) Test the function by calling it on week_2, using the function you created in task 7.

Note: you are not rewriting the function; you are calling the function with different arguments.

With "verbose = True" included as the second argument in the function call.
With no argument for verbose included in the functional call (to test the default).
With "verbose = False" included as the second argument in the function call.
Submit your notebook:

1. To submit your notebook, you will need to download it as .ipynb file first.

2. You can download it by going to the "File" pulldown menu.

3. Select "Download".

4. Arrow to "Download .ipynb".

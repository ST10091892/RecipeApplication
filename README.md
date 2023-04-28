RECIPE  CONSOLE APPLICATION BY ST10091892 (OATILE MDLELA)

This code creates a Recipe class that has fields for the ingredients, their quantities, their unit of measurement, and the steps needed to complete the recipe.

HOW TO COMPILE AND RUN THE APPLICATION:
-The Main method creates an instance of the Menu class and is used to call the viewMenu() method. The Menu class creates an instance of the Recipe Class and then enters an infinite loop that displays a menu of options for the user to select. 
-The user has a choice of  entering the recipe information, displaying the recipe, scaling the recipe by a factor, restoring the quantities to their starting values, clearing the data and exit the program.
-The switch statement is used to call the appropriate method based on the user's input.
-The software will invoke the EnterRecipeDetails() function of the Recipe class when the user chooses the "Enter recipe details" option. The user is prompted to enter the total number of ingredients, the names, quantities, and measurement units for each ingredient, as well as the total number of steps and the details of each one.
-Each ingredient and step's information must be entered by the user exactly as the application instructs. The ingredients, quantities, units, and steps arrays of the Recipe class will hold all the data once it has been entered.
-The user then has the option of displaying the recipe, scaling it, changing the quantities, erasing the data, or exiting the application.
-The Recipe object created in the  Menu method's Recipe() method is used when the user choose to display the data. The recipe information that was previously input by the user is displayed using this method.
-The DisplayRecipe() method first prints a header "Recipe" and a line of dashes, then prints the list of ingredients, followed by the list of steps.
-Using a for loop that iterates over the numOfIngredients variable, the ingredients list is printed. The quantities, units, and ingredients arrays are used in the loop to display the quantity, unit, and name of each ingredient, respectively.
-The 'ScaleRecipe()' method of the 'Recipe' class is invoked when the user decides to scale the recipe by a factor. The method accepts a 'double' parameter that specifies the scaling factor for the recipe. 
-The procedure repeatedly multiplies each element of the 'quantities' array of the 'Recipe' object by the scaling factor. The outcomes are then put back into the original array. 
-The user can choose to display the modified recipe after the scaling is complete by choosing the proper option from the menu.
-When the user chooses to reset the quantities, the ResetQuantities() method is called , and the existing recipe is overwritten with the newly entered recipe details.
-The ClearData function of the Recipe class is called when the user chooses the option to clear the data. This method basically deletes all previously input data for the recipe by setting all of the private fields of the Recipe object to their default settings. Particularly, the fields numOfSteps, steps, numOfIngredients, ingredients, quantities, units, and numOfUnits are all set to their default values (0 and null, respectively). The user can start entering a fresh recipe from scratch when the data has been cleaned.
When the user chooses to exit the application, the Environment.Exit(0) method is called, which terminates the program and returns the exit code 0 to the operating system. This will close the console window and end the program's execution.



## Identification
- **Name:ASSIL BENZAMIA** 
- **P-number:439663** 
- **Course code:IY499** 

I confirm that this assignment is my own work.
Where I have referred to academic sources, I have provided in-text citations and included the sources in the final reference list.


Liberaries used :
tkinter: This library is used for creating the graphical user interface (GUI) of the application. It provides widgets such as buttons, labels, and entry fields to interact with the user.
tkinter.messagebox: This module from the tkinter library is used to display message boxes for error handling and user notifications.
tkinter.filedialog: This module from the tkinter library is used to open file dialogs, allowing users to select files from their file system.


This application is a versatile tool combining a calculator and number sorter, built using the Tkinter library in Python. It allows users to perform basic arithmetic operations including addition, subtraction, multiplication, and division by entering two numbers and selecting the desired operation. The result is displayed within the application interface. Additionally, the app features a sorting function that accepts a list of 5 to 10 numbers, entered as a space-separated string, and sorts them using the bubble sort algorithm. The sorted result is shown on the GUI.

An added feature of the application is file handling, which allows users to load numbers from a text file for sorting. The user can select a file containing numbers, which the app reads, validates, and displays in the entry widget for sorting. This makes the app flexible for various numeric tasks, whether the data is entered manually or loaded from a file. The application includes error handling to manage invalid inputs and operations like division by zero, ensuring robust performance. Overall, this app is a handy tool for performing basic calculations and sorting tasks within a user-friendly interface.

running the app :
Open a Terminal or Command Prompt:

On Windows: Press Win + R, type cmd, and press Enter.
On macOS: Press Cmd + Space, type Terminal, and press Enter.
On Linux: Open your preferred terminal application.
Navigate to the Script Location:

Use the cd command to navigate to the directory where you saved the calculator_sorter.py file. For example:
sh
Copy code
cd path\to\your\script\directory
Replace path\to\your\script\directory with the actual path to your script file.
Run the Script:

Execute the script by typing the following command and pressing Enter:
sh
Copy code
python calculator_sorter.py
Use the Application:

A window will appear with the calculator and sorting interface.
For arithmetic calculations:
Enter the first number in the "Enter first number" field.
Enter the second number in the "Enter second number" field.
Select the desired operation (Add, Subtract, Multiply, Divide).
Click the "Calculate" button to see the result.
For sorting numbers:
Enter 5 to 10 numbers separated by spaces in the provided field.
Click the "Sort" button to see the sorted numbers.
To load numbers from a file:
Click the "Load from File" button and select a text file containing numbers separated by spaces.
The numbers will be loaded into the sorting field, ready to be sorted.

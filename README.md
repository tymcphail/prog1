# Boat Rental Form
Program Focus: A GUI application built using Windows Forms to calculate the total cost of renting a boat, including options for boats, people, life jackets, and rental days

Key GUI Techniques Used
- Windows Forms Framework
 - Utilizes controls like text boxes, dropdown menus, radio buttons, and labels for user input and output
- Event Handling
  - Event-driven interaction triggered by button clicks and selections
- Data Binding
  - Outputs results directly to GUI labels or text boxes
-  Input Validation
- Validates user inputs to ensure they are within acceptable ranges before performing calculations
  - Provides feedback to users through MessageBox.Show when inputs are invalid
- Dropdown and Radio Button Logic
  - Uses dropdown menus to allow users to select boat types and the number of people
  - Includes radio buttons (YesButton) for optional life jacket selection
- Conditional Logic
  - Implements if-else blocks to determine pricing based on the selected boat, number of people, and life jacket options
- Output Formatting
  - Formats numeric results as currency (e.g., $250.50) for display in output field

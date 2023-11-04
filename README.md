# Restaurant Management Program (C)

## Overview

This C program is a simple restaurant management system that allows users to place food orders, calculate bills, and make payments. The program is designed to run in a Windows environment due to its use of the `windows.h` library for screen clearing and color management.

The program includes the following key features:

- Main menu for selecting options: "New Order," "Bill Payment," and "Exit."
- Sub-menus for selecting food categories: "Breakfast," "Brunch," "Lunch," "Dinner," and "Ice cream and Milkshakes."
- Users can place orders, specify quantities, and calculate the total bill.
- Each order is assigned a unique token number.
- Users can make bill payments, and the program calculates and provides change if needed.

## Prerequisites

To run this program, you need:

- A C compiler (e.g., GCC for Windows)
- A Windows-based environment for full functionality
- Basic knowledge of compiling and running C programs

## Instructions

1. Open a C compiler in your Windows environment.

2. Copy and paste the program code into a new C source code file, for example, `restaurant.c`.

3. Save the source code file.

4. Compile the code using the following command (replace `restaurant.c` with your source code file if necessary):

   ```
   gcc -o restaurant.exe restaurant.c
   ```

5. Run the compiled program:

   ```
   restaurant.exe
   ```

6. You'll be presented with the main menu. Use the numeric keys to select your desired option:
   - `1` for "New Order"
   - `2` for "Bill Payment"
   - `3` to "Exit" the program

7. Depending on your choice, you'll be guided through the process of placing orders or making payments. Follow the on-screen prompts to enter food item IDs, quantities, and complete the transactions.

8. The program will keep track of the orders and provide a unique token number for each order.

9. For bill payments, enter the token number and the amount you wish to pay. The program will calculate the change.

10. You can continue to place new orders or exit the program at any time.

## Customization

- You can modify the food items and their prices by editing the `costs` and `items` arrays in the code.
- You may also customize the program's appearance by adjusting screen-clearing and color settings.

## References

The code may include references to books, websites, and class notes used during its development.

## Author

The program was written by Sanjay Ram R R.

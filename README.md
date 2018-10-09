# Bookstore-Clerk
# Introduction:

This is a program that can be used by a clerk in a bookstore. It allows the user to make changes to the database in multiple ways and returns simple statements to infrom the user that changes have taken place.

# Features:

Bookstore-Clerk allows the user to enter a book into a database, remove a book from said database and update any of the records individually. It also allows the user to search for book information using the id, title, author, or quantity of the book in the database. If the book isn't in the database a statement will be given to inform the user.

# Instructions:

Upon running the program the user is given 5 choices and can enter 1-5 to select the following options: 1. Enter a book, 2. Update a record, 3. Delete a record, 4. Search the database, or 5. Exit the program.

If they enter 1 they are prompted for the title, author, and quantity of the book they wish to add to the database. The book will be entered into the database with an ID of 1 above the current maximum ID in the database.

If they enter 2 they are prompted to enter the ID of the book they would like to update. They are then given another selection of 1-4: 1. Change the Title, 2. Change the author, 3. Change the quantity in stock, 4. Return to the main menu. After each selection aside from number 4 they are prompted to enter the new information they want to change the record's corresponding field to. The field is changed and they are then sent back to the update selection menu. They can proceed to change other fields of the current record or enter 4 to return to the main menu.

If they enter 3 they are prompted to enter the ID of the record they would like to delete. If entering the delete menu was a mistake simply enter an ID that isn't in the system and they will be told "No books have been deleted." The record is deleted otherwise and they are sent back to the main menu.

If they enter 4 they are prompted with another selection list of 1-5: 1. Search by ID, 2. Search by title, 3. Search by author, 4. Search by quantity, 5. Return to the main menu. If they enter 1 they are prompted to enter an ID and all information regarding that ID including the ID itself, the title, the author, and the quantity in stock are displayed. If they enter 2 or 3 they are prompted to enter a full, or partial, title or author respectively. All information regarding any records containing what was entered is shown. For example, entering "the" for the title will give every ID, title, author, and quantity in stock for each record containing "the" in the title. If they choose 4, search by quantity, they are prompted to enter a quantity. Every record with or below that quantity will be displayed with all the record's information. Finally choosing option 5 takes them back to the main menu.

Option 5 in the main menu will shut the program down.

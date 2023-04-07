# Flash-card
 
This is a Python program that creates a flashcard app using the Tkinter library for the graphical user interface (GUI), and the Pandas library for handling data.

Here is a brief overview of what the code does:

Import the necessary modules (Tkinter, pandas, and random)
Define the background color and create two dictionaries (current_card and to_learn) that will store the flashcard data
Attempt to read in data from a CSV file containing the flashcard information. If the file is not found, the original data is loaded instead.
Create functions for displaying the next flashcard, flipping the card to reveal the answer, and marking the card as "known" so that it is removed from the to_learn dictionary.
Create a Tkinter window and set its properties (title, background color, and padding)
Create a Canvas object to display the flashcards and add the front and back images to the card_background item.
Create two buttons for marking the card as "unknown" or "known"
Call the next_card() function to display the first flashcard, and start the main event loop with window.mainloop()
When the user runs the program, they will see a flashcard with a French word on one side and a button to flip the card. When they flip the card, the Turkish translation of the word will be revealed, and they can mark the card as "known" or "unknown". If the card is marked as "known", it will be removed from the to_learn dictionary and the next card will be displayed. If the card is marked as "unknown", the user can click the button to display the next card without removing the current card from the to_learn dictionary.

Overall, this program is a simple but effective way to help users learn new vocabulary words in a foreign language.

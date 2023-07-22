# French-FlashCard-Master

French FlashCard Master
French FlashCard Master is a Python-based language learning tool that helps you improve your French vocabulary through interactive flashcards. This repository provides a simple tkinter GUI application to make language learning engaging and effective.


## Features
-> Random Flashcards: Access a diverse collection of carefully selected French words with their corresponding English translations.

-> Interactive Interface: The tkinter-based GUI allows for seamless interaction and a user-friendly experience.

-> Flip Card Functionality: Easily flip the flashcards to reveal the English translation of the French word.

-> Progress Tracking: Keep track of your learning progress as you mark words as known.

-> Automatic Data Save: Your learning progress is automatically saved, enabling you to continue from where you left off.

## Usage
-> Install the required dependencies: Make sure you have Python installed, along with the pandas library.

-> Clone the repository: git clone https://github.com/Mahesh-Vardhan/french-flashcard-master.git

-> Run the application: Navigate to the cloned directory and execute the following command:
python flashcard.py

-> Flashcard Learning: Study the French words presented on the flashcards, and click on the card to reveal its English translation. Mark words you know by clicking the "Known" button.

-> Progress Saving: The app automatically saves your progress in a CSV file, enabling you to continue learning seamlessly.

## Data Source

->The initial set of French words comes from the data/french_words.csv file. As you mark words as known, they are moved to the data/words_to_learn.csv file for your learning journey.

## Note
-> In case you need to reset your progress, simply delete the words_to_learn.csv file, and the app will revert to the original set of words.

## Acknowledgments
The application is built using tkinter for the GUI and pandas for data handling. The initial set of French words is sourced from a curated dataset.

## Contributions
-> Contributions to enhance the application and add new features are welcome. Fork the repository, make your changes, and submit a pull request.

# German Verbs with Prepositions

This repository hosts a meticulously curated dataset featuring approximately 300 German verbs along with their corresponding prepositions. The dataset is available in CSV format and is specifically tailored for integration with the Anki application to facilitate efficient language learning.

## About the Project
The verbs compiled in this dataset have been gathered from various resources during my personal journey of learning the German language. With the assistance of ChatGPT, each verb has been translated into English and Persian, my native language. To enhance learning, each entry includes an example sentence showcasing the practical use of the verb with its preposition.

Although I have manually reviewed all entries for accuracy, minor errors may still exist. If you encounter any inaccuracies, please feel free to contribute by notifying me of any corrections.

## Project Goals
- **Comprehensive Coverage:** This dataset is designed to cover a broad range of practical verbs, from beginner to upper intermediate levels, making it a valuable resource for learners at various stages.
- **Multi-language Support:** Each entry offers translations in both English and Persian, catering to a wider range of learners.
- **Contextual Learning:** Each verb is demonstrated in a sentence that contextualizes its usage in real-life scenarios, enhancing comprehension and retention.

## Data Structure

The dataset consists of over 292 rows, each representing a unique German verb along with its associated preposition, organized into 11 columns with the following specifications:

- **original_order**: A numerical identifier, presumably indicating the original sequence of the verb items.
- **base_d (Base German)**: The base form of the verb in German.
- **full_d (Full German)**: The verb in its full or extended form, including its preposition in German.
- **base_e (Base English)**: The base form of the verb in English.
- **base_p (Base Persian)**: The base form of the verb in Persian.
- **verbformen**: A column intended for various verb forms.
- **s1**: A sample sentence in German using the verb and its preposition.
- **s1e**: Translation of the sample sentence in English.
- **s1p**: Translation of the sample sentence in Persian.
- **Note**: An intended column for notes.
- **Tag**: A tag or category associated with the verb, useful for sorting or filtering purposes.

## Handling Verbs with Multiple Prepositions

German verbs often pair with different prepositions, altering their meanings significantly. To clarify which preposition is associated with each verb on the initial card, I've omitted the preposition in the displayed sentence and replaced it with ellipses ("..."). This format is found in the Notes section of each card.

I suggest that users first try to recall the correct preposition by reviewing the context provided in the sentence. After making a guess, users can flip the card to check if their guess matches the correct preposition. This method helps differentiate verbs that use multiple prepositions, enhancing learning through active recall and verification.

Additionally, when viewing a card, if the verb is one that appears multiple times with different prepositions, the word "Notes" will appear on the screen below the verb. By tapping on "Notes," the example sentence is revealed, providing further context and aiding in the learning process.

## Continuous Improvement
As the primary user and creator of this Anki deck, I am continually refining and updating the cards based on my learning experiences. This ongoing process ensures that the dataset not only maintains high standards but also evolves to better meet the needs of language learners.

## Importing into Anki

To use this database with Anki, follow these steps:

- Convert the Excel file into a CSV format.
- Open the Anki desktop app and choose "Import File" from the main menu.
- Select the CSV file and specify the import settings based on your deck structure.

## Contributing
Contributions to this project are welcome! If you have suggestions for improvement, corrections, or would like to enhance the dataset, please submit a pull request or open an issue.

## License
This project is distributed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License, which allows for sharing, adapting, and building upon the material non-commercially as long as you credit me and license your new creations under the identical terms.

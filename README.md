# String Analyzer

This project, developed as part of the **Compiler Design** course, is a simple string analyzer tool. It analyzes a given string to determine its length and identify the parts of speech within the text.

## Features

- Calculate the length of a given string.
- Calculate the word size of the given string.
- Identify parts of speech (e.g., nouns, verbs, adjectives, etc.) in the string.

## Purpose

The project was designed to provide hands-on experience with string processing and basic natural language processing concepts, aligning with the objectives of the Compiler Design course.

## Technologies Used

- HTML: Structure and layout of the web page.
- CSS: Styling and animations (e.g., @keyframes, transitions, hover effects, dark mode).
- JavaScript: Client-side scripting for interactivity (e.g., event listeners, DOM manipulation, animations, and logic for analyzing text).
- DOM Manipulation: JavaScript is used to dynamically update the DOM (e.g., updating results, adding animations, toggling dark mode).
- CSS Animations: Animations like fadeIn, pulse, slideUp, and spin.
- Responsive Design: Includes techniques for mobile-friendly design, such as setting the viewport for proper scaling.
- Custom JavaScript Logic: Text analysis logic, including parts of speech detection and word categorization.
- Event Handling: JavaScript event listeners for user interactions (e.g., mouseenter, focus, DOMContentLoaded).

## How to Use

1. Input a string into the program.
2. The program will output:
    - The length of the string.
    - The word count of the string.
    - The identified parts of speech for each word in the string.

## Example

Input:

```plaintext
The quick brown fox jumps over the lazy dog.
```

Output:

```
Length: 44 characters
Word Count: 9 words
Parts of Speech:
- The: Determiner
- quick: Adjective
- brown: Adjective
- fox: Noun
- jumps: Verb
- over: Preposition
- the: Determiner
- lazy: Adjective
- dog: Noun
```

## Learning Outcomes

- Understanding Lexical Analysis:
  - The project demonstrates how to tokenize input text by splitting it into words and punctuation using regular expressions (wordRegex).
  - It introduces the concept of lexical analysis, where input is broken into meaningful tokens (e.g., words, punctuation).

- Categorization of Tokens:
  - The project categorizes tokens into parts of speech (e.g., nouns, verbs, adjectives) using a dictionary and heuristics.
  - This is analogous to syntax analysis in compilers, where tokens are classified based on grammar rules.

- Animation and Visualization:
  - The project uses animations (e.g., fadeIn, pulse) to visually represent the analysis process.
  - This helps in understanding how to present abstract concepts (like token classification) in a user-friendly way.

- Simulating Parsing:
  - The logic for determining parts of speech mimics parsing, where rules are applied to classify tokens.
  - The use of heuristics (e.g., checking word endings like -ly, -ing) is similar to how parsers handle ambiguous grammar.

- Dynamic DOM Manipulation:
  - The project dynamically updates the DOM to display results, simulating how compilers generate intermediate or final outputs.

- Performance Optimization:
  - The use of animations and delays (e.g., setTimeout) introduces the concept of simulating processing time, which can be related to optimizing compiler performance.

- Dark Mode and Theming:
  - The implementation of dark mode demonstrates how to toggle between different states, similar to how compilers handle different configurations or modes.

- Modular Thinking:
  - The project organizes functionality into reusable functions (e.g., getPartOfSpeech, animateCounter), promoting modular design, a critical skill in building compilers.

- Visualization of Results:
  - Highlighting parts of speech with colors and animations is analogous to how compilers provide visual feedback (e.g., syntax highlighting in IDEs).

## Acknowledgments

This project was completed as part of the **Compiler Design** course at Daffodil International University. Special thanks to the course instructor *Mushfiqur Rahman* for guidance and support. By working on this project, I gain a deeper understanding of compiler design principles while also improving your skills in HTML, CSS, JavaScript, and UI/UX design.

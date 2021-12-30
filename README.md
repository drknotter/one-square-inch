# One Square Inch
A project for picking and displaying interesting words, to be drawn in one square inch, every day.

## Interesting Word Generation
"Interesting" words are generated by choosing randomly from Webster's English Dictionary, weighted by the length of the definition. This heuristic was chosen based on the assumption that words with many different meanings, or words that just require a lot of verbiage to define, are generally more interesting.

The `interesting-word-picker.py` script performs the random picking of words, and presents them to the user one by one, with the option to "skip" the word. Chosen words are saved to a file specified by the user.

The `generate_interesting_site.py` script takes a file with a list of words, and generates a basic calendar HTML page for displaying the words, based on a start date.

An example list of 365 interesting words were generated, and are displayed in `index.html`. You can see the results at this project's [Github page](https://drknotter.github.io/one-square-inch).
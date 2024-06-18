
# Prince Lyrics Analysis

This project aims to analyze the lyrics of Prince's songs using text mining techniques. The analysis includes cleaning and preprocessing the lyrics, identifying popular words, and visualizing important words using TF-IDF and word counts per decade.

## Project Structure

- **Task 1**: Install and load required packages.
- **Task 2**: Load the dataset.
- **Task 3**: Inspect the dataset.
- **Task 4**: Select relevant columns.
- **Task 5**: Add decade and chart level information.
- **Task 6**: Inspect modified dataset.
- **Task 7**: Clean lyrics by fixing contractions.
- **Task 8**: Tokenize the lyrics into words and filter out undesirable words.
- **Task 9**: Count word frequencies.
- **Task 10**: Compute TF-IDF for words.
- **Task 11**: Visualize important words using TF-IDF by song.
- **Task 12**: Analyze and visualize popular words per decade.

## Installation

To replicate this analysis, you need to have R installed on your machine. Install the required packages using the following commands:

```r
install.packages('tidyverse')
install.packages('tidytext')
install.packages('gridExtra')
```

## Usage

1. **Load and Preprocess Data**:
   - Load the `prince_raw_data.csv` file.
   - Select relevant columns: lyrics, song, year, album, peak, US.Pop, US.R.B.
   - Add decade and chart level information based on the year and peak chart position.

2. **Text Cleaning and Tokenization**:
   - Fix contractions in the lyrics.
   - Tokenize the lyrics into individual words.
   - Remove stop words and undesirable words.

3. **Analysis**:
   - Count the frequency of words in the lyrics.
   - Compute the TF-IDF for words to identify important words in each song.
   - Visualize the most frequently used words and important words using TF-IDF.

4. **Visualization**:
   - Create bar plots to show the most frequently used words.
   - Visualize important words using TF-IDF by song.
   - Analyze and visualize popular words per decade.


## Contributing

If you have any suggestions or improvements, feel free to open an issue or submit a pull request.



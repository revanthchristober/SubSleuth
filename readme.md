# SubSleuth

SubSleuth is a web application that helps users seek subtitles for movies and TV shows quickly and easily.

## Features

- **Search**: Enter a dialogue or text snippet from a movie or TV show to find matching subtitles.
- **Download**: Directly download subtitles from OpenSubtitles.org.
- **Pagination**: Navigate through search results using pagination.
- **Animated UI**: Enjoy a visually appealing interface with animated transitions.

## Getting Started

To run SubSleuth locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the necessary dependencies using `pip install -r requirements.txt`.
3. Run the Flask application by executing `python3 app.py`.
4. Access the application in your web browser at `http://localhost:5000`.

## Dependencies

- Flask: Web framework for Python.
- ChromaDB: Database for storing and querying embeddings.
- Beautiful Soup: Library for web scraping.
- NLTK: Natural Language Toolkit for text preprocessing.
- Sentence Transformers: Library for generating sentence embeddings.
- tqdm: Library for displaying progress bars.

## Usage

1. Enter a dialogue or text snippet in the search bar and click "Search".
2. Browse through the search results and click "Download" to get the desired subtitle.
3. Navigate through multiple pages using the pagination controls.

## Contributing

Contributions are welcome! If you'd like to contribute to SubSleuth, please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for details.

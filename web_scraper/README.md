# Web Scraping Dog Breeds Information

This project involves web scraping dog breed information from a list of URLs using Python. The `BeautifulSoup` library is used to parse the HTML content of the web pages, and `pandas` is used for data manipulation and storage. The extracted data includes images and paragraphs describing the dog breeds.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)

## Installation

To use this project, you need to have Python installed on your system. Additionally, you need to install the required libraries using pip.

```bash
pip install -r requirements.txt
```

## Usage

1. **Prepare the Input CSV File:**

   Ensure you have a CSV file named `dog_breeds.csv` containing two main columns and other columns:
   - `breed`: The name of the dog breed.
   - `url`: The URL of the web page containing details about the breed.

2. **Run the Web Scraping Script:**

   Execute the provided script `scrape_dog_breeds.py` to scrape data from the provided URLs.

   ```bash
   main.ipynb
   ```

3. **Output:**

   The script will generate a CSV file named `dog_breeds_info.csv` containing the following columns:
   - `breed`: The name of the dog breed.
   - `image_url`: The URL of the dog breed's image.
   - `description`: A paragraph describing the dog breed.
   - and other prevailed details 

## Project Structure

- `docs/breeds.csv`: Input file containing dog breed names and URLs.
- `main/main.ipynb`: Python script to perform web scraping.
- `results/outputs.csv`: Output file containing scraped data.
- `README.md`: This README file.
- `requirements.txt`: List of required Python libraries.

## Contributing

Contributions are welcome! If you have any improvements or suggestions, please create a pull request or open an issue.


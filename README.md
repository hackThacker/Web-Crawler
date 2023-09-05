# Web Crawler and URL Parameter Extractor

This Python script serves as a versatile web crawler and URL parameter extractor. It enables users to explore web directories, gather information about subdirectories and files, and extract URL parameters from linked pages. This script can be particularly valuable for tasks such as website analysis, content indexing, and data collection.

## Features

- **Crawl Directories:** The script starts from a specified base URL and recursively crawls through linked directories. It identifies subdirectories and files within the target directory.

- **Avoid Duplicates:** To maintain data integrity, the script utilizes sets to track visited URLs, ensuring that duplicate entries are not added to the output files.

- **Extract URL Parameters:** The script extracts and organizes URL parameters found within the links it encounters. This can be useful for understanding how a web application or website processes and utilizes query parameters.

- **Standardized Output:** The script saves the results in separate text files, including `directories.txt`, `files.txt`, and `parameters.txt`, with clear labels and formatting for easy readability.

## How to Use

1. **Set the Base URL:** Modify the `base_url` variable in the script to specify the starting point for crawling.

2. **Run the Script:** Execute the script using Python. Ensure you have the required libraries (`requests`, `BeautifulSoup`, and `urllib`) installed.

3. **Review the Results:** After the script completes, check the `crawled_urls` folder for the generated text files. These files contain a structured representation of the crawled data, including directories, files, and URL parameters.

## Example Usage

Suppose you want to analyze the structure of a web directory, identify its contents, and extract URL parameters for further investigation. This script provides an automated and organized way to achieve these tasks.

## Note

- This script focuses on extracting information from publicly accessible web pages. Always ensure compliance with web scraping guidelines, terms of service, and legal regulations when using such tools.

- Customize the `base_url` variable to target the specific web directory or website you wish to explore.

## Dependencies

- [Requests](https://docs.python-requests.org/en/latest/): Python library for making HTTP requests.

- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/): Python library for parsing HTML and XML documents.

- [urllib](https://docs.python.org/3/library/urllib.html): Python library for working with URLs.

## License

This script is provided under the [MIT License](LICENSE), allowing for free and open use, modification, and distribution. However, please be aware of and respect the terms and conditions of the websites you crawl.

# WebCrawler
Developed a web crawler which can actively crawl through sites with active cpu monitorisation with an interface

# Web Crawling Project

## Project Overview
This project implements a web crawler designed to extract specific metrics and data from target websites. It employs multithreading and concurrency concepts to enhance performance and efficiency in data retrieval. The extracted data includes CPU and memory usage metrics from various system monitoring websites.

## Features
- **Multithreaded Crawling**: Utilizes concurrent threads to fetch data from multiple sources simultaneously.
- **Metric Extraction**: Parses HTML pages to extract CPU and memory usage metrics.
- **Error Handling**: Implements robust error handling to ensure data integrity and reliability.
- **Metrics Display**: Displays retrieved metrics in real-time for monitoring purposes.

## Requirements
- Python 3.x
- Required Python packages: requests, beautifulsoup4, concurrent.futures

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/your_username/web-crawler.git
   ```
2. Navigate to the project directory:
   ```
   cd web-crawler
   ```
3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. Run the main script:
   ```
   python main.py
   ```
2. Monitor the console output for real-time metrics retrieved from the specified websites.

## Configuration
- Customize the list of target URLs and other parameters in `config.py` according to your requirements.

## Contributing
Contributions are welcome! Fork the repository and submit a pull request with your enhancements.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

---

Feel free to customize the sections and details based on your specific project and preferences!

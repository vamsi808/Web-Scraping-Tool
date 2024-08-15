# Web-Scraping-Tool
This project features a web application built using Flask. It allows users to scrape data from websites by specifying a URL, HTML tag, and class name. The backend (app.py) handles the scraping using BeautifulSoup, while the frontend includes a simple, responsive interface (index.html) with a focus on usability, styled through CSS (style.css).
​
# Web Scraping Application

This project is a web application built using Flask that allows users to scrape data from websites by specifying a URL, HTML tag, and class name. The application extracts content from the specified web pages and presents it in a user-friendly interface.

## Project Structure

- **app.py**: The main Python application file that handles routing and web scraping functionality.
- **templates/index.html**: The HTML file that serves as the front-end of the application, allowing users to input URLs, tags, and class names.
- **static/style.css**: The CSS file that styles the HTML interface, ensuring a clean and responsive design.

## Features

- **Web Scraping**: Users can scrape data from any website by providing the URL, HTML tag, and class name of the elements they want to extract.
- **BeautifulSoup Integration**: The scraping functionality is powered by the BeautifulSoup library, making it easy to parse and extract HTML content.
- **Responsive Design**: The application features a responsive design, ensuring that it looks good on various screen sizes.
- **File Download**: The scraped data can be downloaded as a file for further use.

## Setup and Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/web-scraping-app.git
    cd web-scraping-app
    ```

2. **Install Dependencies**:
    Ensure you have Python installed, then install the required packages using pip:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Application**:
    Start the Flask application:
    ```bash
    python app.py
    ```

4. **Access the Application**:
    Open your browser and go to `http://127.0.0.1:5000/` to access the application.

## Usage

1. Enter the website URL you want to scrape.
2. Specify the HTML tag and class name of the content you want to extract.
3. Click the "Scrape" button to retrieve the content.
4. Download the scraped data as a file.

## Technologies Used

- **Python**: Core programming language.
- **Flask**: Web framework for building the application.
- **BeautifulSoup**: Library for scraping web content.
- **HTML/CSS**: Front-end technologies for creating the user interface.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- Inspired by various web scraping tutorials and resources.
- Special thanks to the open-source community for providing the tools and libraries used in this project.

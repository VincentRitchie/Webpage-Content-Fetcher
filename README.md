
# Web Content Fetcher

<a>
  <img src="https://github.com/VincentRitchie/Webpage-Content-Fetcher/blob/main/fetch%20webpage%20contents.webp" alt="Logo" height="350" width="650" />
</a>

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## Description
`Web Content Fetcher` is a Python script designed to fetch content from a user-provided URL and save it in either HTML or CSV format. This tool is ideal for web scraping Front-End scripts (HTML, CSS and JS) at the user interface. The script uses the `requests` library for fetching content and handles HTTP errors gracefully.

## Features
- **Content Fetching:** Retrieve content from a user-provided URL.
- **File Format Options:** Save content as either an HTML file or a CSV file.
- **Error Handling:** Gracefully handle HTTP and request errors.
- **User Interaction:** Simple and interactive prompts for input.

## Installation
To install and run this project, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/VincentRitchie/web-content-fetcher.git
   ```
2. Install the required dependencies:
   ```sh
   pip install requests
   ```

## Usage
To use the `Web Content Fetcher`, follow these steps:

1. **Run the Script:**
   ```sh
   python web_content_fetcher.py
   ```

2. **Enter the URL:**  
   Provide the URL of the website from which you want to fetch content.

3. **Choose the File Format:**
   Decide whether to save the content as an HTML or CSV file.

4. **Save the Content:**  
   The content will be saved in the chosen format with the specified filename.

### Example Usage:

```bash
Enter website URL: https://example.com
Enter the filename (without extension): example_content
Choose file format (html/csv): html
Content saved as example_content.html
```

## Screenshot

<a>
  <img src="https://github.com/VincentRitchie/Webpage-Content-Fetcher/blob/main/Webpage%20Content%20Fetcher%20Screenshot.png" alt="Screenshot" width="650" />
</a>

## Future Enhancements

### 1. **Advanced Content Parsing**
   - **Description**: Introduce content parsing to extract specific data, such as tables, headers, or paragraphs.
   - **Benefit**: Provides more flexibility for users to extract targeted content.

### 2. **Support for Other File Formats**
   - **Description**: Add support for saving content in JSON, XML, or plain text formats.
   - **Benefit**: Offers more options for users based on their needs.

### 3. **Automated URL Validation**
   - **Description**: Validate URLs before making the request to ensure they are well-formed.
   - **Benefit**: Reduces the likelihood of request errors due to invalid URLs.

### 4. **Asynchronous Requests**
   - **Description**: Implement asynchronous requests for faster content fetching, especially with multiple URLs.
   - **Benefit**: Improves performance when handling multiple requests.

### 5. **GUI Integration**
   - **Description**: Develop a graphical user interface for easier interaction with the script.
   - **Benefit**: Provides a more user-friendly experience for managing web content fetching.

## Contributing

Feel free to submit issues and enhancement requests. Pull requests are also welcome.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/VincentRitchie/web-content-fetcher/blob/main/LICENSE) file for details.

## Author

#### Vincent Chimaobi (CyberGhoxt)

Connect with me on 
- [GitHub](https://www.github.com/VincentRitchie/VincentRitchie)
- [LinkedIn](https://www.linkedin.com/in/vincent-chimaobi-53b458216?trk=contact-info)
- [X](https://x.com/vin_chimaobi042)

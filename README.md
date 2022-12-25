This repository is a simple web application written in Go that allows you to shorten long URLs into shorter, more convenient ones.

## Features
- Shorten any valid URL
- Customize the ending of the shortened URL (optional)
- Keep track of the number of clicks on the shortened URL
- Keep track of the date of latest click on the shortened URL
- Simple implementation of Rate Limiter
- Redirect to the original URL when the shortened URL is accessed

# Getting started
To get started with the URL Shortener, you'll need to have the following dependencies installed on your machine:

## Usage
Follow these steps to set up the URL Shortener:

1. Clone the repository: git clone https://github.com/bulutenesemre/url_shortener.git
2. Navigate to the directory: cd url_shortener
3. Build the application: go build
4. Run the application: ./url_shortener

The URL Shortener should now be running on your local machine at http://localhost:3000

You can use CURL for generate shortener URLs ;

```bash
curl -X POST http://localhost:3000/api/v1 -H "Content-Type: application/json" -d '{"url": "https://www.youtube.com/watch?v=4Tr0otuiQuU"}'
```



## Contributing
If you'd like to contribute to the URL Shortener, please fork the repository and make your changes in a separate branch. Once you're ready to submit your changes, open a pull request and include a description of your changes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.


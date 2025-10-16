# CAPTCHA Solver

A simple web-based CAPTCHA solver that displays and solves CAPTCHA images from URLs.

## Features
- Displays CAPTCHA image from URL parameter (`?url=`)
- Solves CAPTCHA text within 15 seconds
- Defaults to sample image if no URL provided

## Usage
1. Open `index.html` in a browser
2. Add `?url=your_image_url` to solve a specific CAPTCHA
3. View the solved text in the results section

## Implementation Details
This demo uses a hard-coded solution for the sample CAPTCHA image. In a production environment, this would connect to an OCR service or machine learning model to solve arbitrary CAPTCHAs.

## License
MIT
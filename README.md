# Sounny OSM Batch Geocoder

## Overview

Batch Geocoder is a simple, frontend-only web application that allows users to convert a list of addresses into geographical coordinates (latitude and longitude). The application utilizes the Nominatim API for geocoding services and is built using HTML, CSS, and JavaScript.

## Features

- **No Backend Required**: All the geocoding happens in the browser. No server-side code is needed.
- **Easy to Use**: Just paste your list of addresses into a textbox and click a button to get the geocoding results.
- **Rate Limiting**: To prevent abuse, the application limits the number of addresses to 100 per batch.
- **Results Table**: The geocoded results are displayed in an easy-to-read table format.

## How to Use

1. Open the `index.html` file in a web browser.
2. You'll see a textarea and a "Geocode" button.
3. Paste your list of addresses into the textarea. Each address should be on a new line, and you can add up to 100 addresses.
4. Click the "Geocode" button.
5. The table below the button will populate with the geocoded results, displaying the original address, latitude, and longitude.

## Limitations

- **Rate Limiting**: Nominatim has its own usage policies. Heavy usage may require a backend to handle API requests more responsibly.
- **Minimal Error Handling**: Addresses that return no results are listed after geocoding, but network errors are not yet handled.

## Future Enhancements

- Implement proper error handling for failed geocoding attempts.
- Add export options for the results, such as CSV or JSON formats.
- Integrate a backend for more robust rate limiting and caching.

## Contributions

Feel free to fork the project and submit a pull request for any enhancements.

## License

This project is open source and available under the [MIT License](LICENSE).

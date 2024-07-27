

# Lead Tracker Chrome Extension

Lead Tracker is a simple Chrome extension designed to help you save and manage links from your active tabs. Whether you're researching, browsing, or just collecting links for later, Lead Tracker keeps your saved links accessible and organized. Links are stored in the browser's local storage, so they remain available even after refreshing the page or restarting your browser.

## Features

- **Save Active Tab Links**: Easily save the link of the currently active tab with a single click.
- **Manual Link Input**: Add links manually to your list.
- **Persistent Storage**: Links are saved in local storage, ensuring they remain available even after browser refreshes or restarts.
- **Delete Links**: Remove saved link with a delete button.
- **User-Friendly Interface**: Simple and intuitive UI for easy management of your links.

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Soumajit-Roy/Basic-Chrome-Ext-JS.git
   ```

2. **Load the Extension:**

   - Open Chrome and go to `chrome://extensions/`.
   - Enable "Developer mode" at the top right corner.
   - Click on "Load unpacked" and select the directory where you cloned the repository.

## Usage

1. **Saving Links:**
   - To save the current tab's link, click on the Lead Tracker icon in your browser's toolbar and then click the "Save" button.
   - To manually add a link, input the URL in the text box and click the "Add" button.

2. **Managing Links:**
   - Your saved links are displayed in a list within the extension popup.
   - Each link entry includes a delete button that allows you to remove unwanted links from your list.

## Development

If you wish to contribute or modify the extension:

1. **Prerequisites:**
   - Basic knowledge of HTML, CSS, and JavaScript.
   - Familiarity with Chrome extension development.

2. **Structure:**
   - `popup.html`: The main UI of the extension.
   - `popup.js`: The JavaScript logic for managing the links.
   - `manifest.json`: The configuration file for the Chrome extension.

3. **Contributing:**
   - Fork the repository and create your branch: `git checkout -b feature/YourFeatureName`.
   - Commit your changes: `git commit -m 'Add some feature'`.
   - Push to the branch: `git push origin feature/YourFeatureName`.
   - Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the open-source community for their continuous contributions and inspiration.

## Contact

For any inquiries or suggestions, please reach out via the repository's [issue tracker](https://github.com/Soumajit-Roy/Basic-Chrome-Ext-JS/issues).

---

This README should give users a comprehensive understanding of your extension, its features, and how to use or contribute to it. You can customize it further based on specific needs or additional features.

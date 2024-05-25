# WhatsApp Group Creation Bot

This script automates the process of creating a WhatsApp group using Puppeteer, a Node.js library for controlling headless Chrome/Chromium.

## Prerequisites

Before running the script, ensure you have the following:

- Node.js installed on your machine.
- Google Chrome or Chromium browser installed.
- `puppeteer` Node.js package installed in your project. You can install it via npm:
  
  ```bash
  npm install puppeteer
  ```

## Usage

1. Clone this repository or create a new JavaScript file and copy the script into it.
2. Install Puppeteer as described above if you haven't already.
3. Customize the script according to your requirements:

   - Set the `groupName` variable to the desired name of the WhatsApp group.
   - Optionally, set the `contactNames` variable to the name(s) of the contacts you want to add to the group. If you leave it empty, you'll need to manually search and select contacts.
   - Adjust any other settings in the script if needed.

4. Run the script using Node.js:

   ```bash
   node your_script_name.js
   ```

## Notes

- This script opens WhatsApp Web in a headful mode, meaning you'll see the browser window while the script runs. If you want it to run silently, you can set `headless: true` in the `puppeteer.launch()` options.
- Make sure to provide the correct path to the Chrome/Chromium executable in the `executablePath` option.
- The script will interact with WhatsApp Web to create a new group, add contacts (if specified), and set the group name.
- Error handling is implemented to catch and log any errors that occur during the process.

Feel free to customize and extend the script further according to your needs!

![Tiktok-views-bot](images/banner.png)

## Bot Automation

This project is a Python-based automation bot that interacts with the Zefoy website to automate tasks such as gaining followers, views, hearts, shares, and other social media-related actions. It uses Selenium WebDriver for browser automation and is designed to handle tasks in the background, including solving captchas and choosing services.

## Features

- **Browser Automation:** Automates interactions with the Zefoy website using the Firefox browser.
- **Captcha Solving:** Prompts the user to complete a captcha before proceeding with automation.
- **Service Management:** Supports multiple services such as followers, views, hearts, and more, allowing the user to choose and automate these actions for a video.
- **Error Handling:** Includes error handling for various issues such as missing elements or stale references.

## Requirements

- Python 3.x
- Selenium
- Firefox browser
- GeckoDriver (Managed by `webdriver_manager`)
- `base64`, `re`, `os`, `time` libraries (included in Python)

To install the required libraries, run the following command:

```bash
pip install selenium webdriver-manager
```

## Setup

1. Install [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/) on your machine.
2. Download and install the necessary dependencies by running:
   ```bash
   pip install selenium webdriver-manager
   ```

3. Clone the repository or download the script:
   ```bash
   git clone https://github.com/0xc000000f/Tiktok-views-bot.git
   ```

4. Edit the script to use your own Firefox installation path, if necessary.

## Usage

To run the bot, execute the script as follows:

```bash
python main.py
```

### Steps:

1. The bot will load the Firefox browser and navigate to the Zefoy website.
2. It will prompt you to complete a captcha manually.
3. After solving the captcha, the bot will check the status of available services (followers, views, hearts, etc.).
4. You will be asked to choose a service to automate, as well as a video URL.
5. The bot will start the service and send the chosen video URL.

## Services

The following services are available:

- **Followers**
- **Hearts**
- **Comments Hearts**
- **Views**
- **Shares**
- **Favorites**
- **Live Stream [VS+LIKES]**

## Contributing

Contributions are welcome! If you have improvements, bug fixes, or new features, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

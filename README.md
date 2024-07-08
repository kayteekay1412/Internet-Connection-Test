# Internet Connection Test Utility

## Overview

The **Internet Connection Test Utility** is a simple Python script that checks for an active internet connection by attempting to connect to Google's homepage. The script uses the `requests` library to perform the connection test and provides feedback on the connection status.

## Features

- **Internet Connection Test**: Attempts to connect to Google's homepage to determine if an active internet connection is available.
- **Error Handling**: Catches connection errors and other exceptions, providing appropriate feedback.
- **Simple Output**: Prints the status of the connection attempt to the console.

## How to Use

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/kayteekay1412/internet-connection-test.git
    cd internet-connection-test
    ```

2. **Install Dependencies**:
    Ensure you have the required libraries installed:
    ```bash
    pip install requests
    ```

3. **Run the Script**:
    ```bash
    python internet_connection_test.py
    ```

4. **Output**:
    The script will attempt to connect to Google's homepage and print one of the following messages to the console:
    - "Connection to (https://www.google.com/) was successful."
    - "Failed to connect to (https://www.google.com/)."
    - "Failed with unparsed reason."

## Example

Here is an example of the script output:

```
Attempting to connect to (https://www.google.com/) to determine internet connection status.
Connection to (https://www.google.com/) was successful.
```

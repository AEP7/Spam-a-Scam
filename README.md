# spam-a-scam

This Jupyter Notebook contains a Python script that is designed to perform repeated POST requests to a specified URL with random data. It can be used for testing and experimenting with POST requests to a target URL. Please note that this code should be used responsibly and only on systems and URLs that you have permission to test.

## Usage

1. Open the Jupyter Notebook `spam-a-scam.ipynb`.

2. Modify the `url` variable in the notebook to specify the target URL where you want to send the POST requests.

3. Modify the `times` variable to specify the number of POST requests you want to send.

4. Run the notebook cell by cell.

The notebook will send the specified number of POST requests with random data to the target URL. If a request is successful (HTTP status code 200), it will be indicated in the notebook's output. Otherwise, the HTTP status code indicating the failure will be displayed.

**Note:** Before running the notebook, ensure that you have the necessary Python packages (e.g., requests) installed. You can install them using pip if needed.

Please use this notebook responsibly and only on systems and URLs for which you have proper authorization. Sending large numbers of requests to a website without permission may be illegal and unethical. Always respect the terms of service of the target website and ensure you have the necessary permissions to perform testing. The creators of this script are not responsible for any misuse or legal consequences arising from its use.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

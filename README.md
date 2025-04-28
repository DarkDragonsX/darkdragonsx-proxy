# darkdragonsx-proxy
لأن السرعة والقوة لا تأتي صدفة — darkdragonsx-proxy، أداة البروكسي التي تتفوق على الجميع.

تمام، إليك التصميم النهائي الذي يمكنك وضعه على ملف README.md بشكل أنيق ومنظم:

# DarkDragonsX | Proxy Checker Tool

**DarkDragonsX** is a powerful tool to validate proxies against a target website. It takes a list of proxies, checks their functionality against the provided URL, and saves the working proxies in a file for future use.

## How to Use

### Step 1: Prepare Proxy List
- Ensure you have a text file containing the proxies you want to check.
- Each line should contain one proxy in the format `ip:port`.

### Step 2: Run the Tool
1. Open your terminal and run the tool with the following command:
   ```bash
   python3 proxy_checker.py

2. The tool will prompt you to enter the path to your proxy file. Enter the correct path.


3. Next, it will ask you to input the target website URL. Ensure the URL is correct (e.g., https://www.instagram.com/).



Step 3: Review the Results

The tool will check the proxies one by one and display the results in the user interface.

Working proxies will be saved in a file named txt.proxy-darkdragonsx.

A summary table with the count of working and failed proxies will be displayed.


Features

User Interface: Interactive and beautiful interface using the rich library.

High Performance: Uses ThreadPoolExecutor for parallel proxy checking to speed up the process.

Reports: Displays a neat summary table showing the count of working and failed proxies.

Easy to Use: Simple command-line interface with clear prompts.


Example Usage
 ```bash
$ python3 darkdragonsx-proxy.py
```
The tool will prompt you to enter the path to your proxy file:

Enter path to your proxy file:

Then, it will ask for the target website URL:

Enter target website URL (example: https://www.instagram.com/):


Requirements

Python 3

requests library: To install, run the following command:
 ```bash
pip install requests
```
```bash
rich library: To install, use:
```
```bash
pip install rich
```
```bash

Expected Results

```

After the check is complete, you will see a summary of the working and failed proxies in a table format, and the working proxies will be saved in the txt.proxy-darkdragonsx file.

Notes

Please ensure that the proxies you use comply with local laws and the target website's policies.


Contact Me

Name: Mohamed Lamine

Facebook: darkdragonsx

Instagram: @_darkdragonsx

Twitter: @darkdragonsx

Facebook Group: DarkDragonsX Group


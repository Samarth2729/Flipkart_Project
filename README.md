## Author

**Samarth Rathore**

- **Email**: [samarthrathore2729@gmail.com](mailto:samarthrathore2729@gmail.com)
- **LinkedIn**: [Samarth Rathore](https://www.linkedin.com/in/samarth-rathore-4b410226a/)
- **GitHub**: [Samarth2729 ](https://github.com/Samarth2729)




### Flipkart Add to Cart Automation Test

### Overview

This project is a Selenium-based automation script designed to test the "Add to Cart" functionality on the Flipkart website. The script searches for the "iPhone 16", adds it to the cart, validates the price, removes the item from the cart, and checks if the cart is empty afterward.

### Prerequisites

Before running the script, ensure you have the following installed:

- Python 3.x
- Chrome WebDriver
- Selenium package

### Installation

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd <repository-directory>

### Install Selenium

To install the Selenium package, you can use pip. Open your command line or terminal and run the following command:

```bash
pip install selenium
```
### Download Chrome WebDriver

- Download the appropriate version of Chrome WebDriver 
- Ensure that the Chrome WebDriver is in your system's PATH or specify the executable path in the script.

### Usage

1. Open the script in your favorite code editor
2. Run the Script:
```bash
python test_flipkart_add_to_cart.py
```
3. The script will:
- Open the Flipkart homepage.
- Close the login popup if it appears.
- Search for "iPhone 16".
- Click on the desired product.
- Add the product to the cart.
- Validate the price of the product.
- Remove the product from the cart.
- Confirm that the cart is empty.

4. You should see the message:<span style="background-color: lightgrey;">Test completed successfully!</span> in the console output.

### Imports Used
The following libraries are imported in the project:
```bash
from selenium import webdriver
from selenium.webdriver.common.by import By
from selenium.webdriver.common.keys import Keys
from selenium.webdriver.support.ui import WebDriverWait
from selenium.webdriver.support import expected_conditions as EC
from selenium.common.exceptions import TimeoutException, StaleElementReferenceException, ElementClickInterceptedException
import time
```

### Error Handling
- The script handles common exceptions such as<span style="background-color: lightgrey;">TimeoutException,StaleElementReferenceException,</span> and<span style="background-color: lightgrey;">ElementClickInterceptedException</span>
- If any step fails, an appropriate message is printed to the console.

### Notes

- Ensure that your internet connection is stable while running the test.
- The script is designed for educational purposes and may require updates based on changes to the Flipkart website's layout or structure.

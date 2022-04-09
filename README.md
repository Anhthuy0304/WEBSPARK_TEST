# Introduction

1. Download Python and run on the "Python.org"

Open Terminal/Cmd and Write Command as written Below:
2. Ensure Python is installed:
# For macOS: 
python3
# For Windows:
python
3. Ensure the following libraries (Selenium language bindings) are installed:
# If pip is not installed, you can install it using:
python -m install pip 
# If you prefer pip, then use the following command:
python -m pip install selenium

4. Installing Webdrivers
One Can Install Firefox, Chromium, PhantomJs(Deprecated Now), etc. 
# For using Firefox you may need to install GeckoDriver 
 
# For using Chrome you may need to install Chromium 

5. Import the following library:
pip install beautifulsoup4

6. Open the WEBSPARK_TEST.py

7. Input the Path of Chromedriver file on your computer. Refer to the syntax below:
# driver=webdriver.Chrome("/Users/anhthuy/Documents/GitHub/chromedriver")

8. Input the 'username' and the 'password'. Refer to these syntax below:
# email = driver.find_element_by_id("login_field").send_keys('username')
# password = driver.find_element_by_id("password").send_keys('password')

9. Run the file.



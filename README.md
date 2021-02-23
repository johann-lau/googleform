# Automatically Fill Google Forms?

This tutorial will teach you how to automatically fill Google Forms with Python, from different types of questions to clicking on the submit button.

## Initial Setup

Go to your Terminal (Command Prompt if you are using Windows) and type `pip install selenium`. If that doesn't work, use `pip3 install selenium`.

Once you see a message like "download complete" or so, you are completed with the setup! Let's write our very first script.

Create a new Python file and enter the following:

```py
from selenium import WebDriver
driver = WebDriver()
driver.get('[GOOGLE FORM URL]')
```

## Radio

The radio buttons are global

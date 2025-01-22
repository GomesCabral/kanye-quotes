# Kanye Says... App

This is a simple Tkinter-based application that fetches and displays random quotes from Kanye West. It uses the **Kanye REST API** to retrieve quotes and presents them in a graphical user interface (GUI) built with Tkinter.

## Features
- **Random Kanye Quotes**: The app fetches a random quote from Kanye West using the **Kanye REST API**.
- **Tkinter Interface**: The app has a user-friendly GUI where a button fetches and displays quotes on the screen.
- **Customizable Background**: The app allows you to display custom background and button images.

## Technologies Used
- **Python**: The programming language used for the application.
- **Tkinter**: A Python library for creating graphical user interfaces.
- **Requests**: A Python library for making HTTP requests to the Kanye REST API.

## Requirements
Before running the script, make sure you have the following libraries installed:

```bash
pip install requests
````

1 - Usage
  git clone https://github.com/your-username/kanye-says-app.git
2- Make sure you have the necessary image files (background.png and kanye.png) in the same directory as the script.
3 - Run the application:
  python kanye_says_app.py
4 - Click the Kanye button to get a random Kanye West quote displayed in the center of the window.


How the App Works
The app initializes a Tkinter window and sets up the layout with a canvas that displays a background image and a placeholder for the quote.
When the user clicks the button, the get_quote() function is called.
The function makes a request to the Kanye REST API to retrieve a random quote.
The quote is then displayed on the screen by updating the text in the Tkinter canvas.
Example Output
Once the app is running, you will see a GUI with a button and an area where Kanye's quote will appear. After clicking the button, a random quote will be displayed in the center of the window.

# kayne-quote-GUI
python api to genrate random quote
1) The given code is a Python program that uses the Tkinter library to create a graphical user interface (GUI) application. The application is designed to display random quotes from Kanye West.

2) The code imports the necessary modules from the Tkinter library, such as Tk and Canvas, and also imports the requests module for making HTTP requests to an API.

3) The main functionality of the program revolves around the get_quote() function. This function sends a GET request to the "https://api.kanye.rest" API to retrieve a random Kanye West quote. The response from the API is then processed, and the extracted quote is displayed on the GUI.

4) The Tkinter window is created with a specific title and padding. It includes a canvas, which serves as the background of the window, and a text area within the canvas to display the quote. Initially, a placeholder text is set for the quote.

5) Additionally, there is a button in the GUI that features an image of Kanye West. When this button is clicked, it triggers the get_quote() function, which fetches a new quote from the API and updates the text area with the retrieved quote.

6) Finally, the main event loop is started using the window.mainloop() function, which allows the GUI to be displayed and interacted with by the user

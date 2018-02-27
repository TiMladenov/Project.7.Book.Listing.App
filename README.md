# Project 7: Book Listing App
v2.0 of Udacity Project 7 - Book Search App

# Description
The goal of building this application was to design and create the structure of a Book Listing app which would allow a user to get a list of published books on a given topic. I had to use Google Books API in order to fetch results and display them to the user.

This project was about combining various ideas and skills that I have been practicing throughout the course. They include:
- Fetching data from an API.
- Using an AsyncTask.
- Parsing a JSON response.
- Creating a list based on that data and displaying it to the user.
- When taped on, each list element forwards the user to the corresponding book at Google Books website.
- Notify the user if no internet connection was detected.

# Requirements
The design must include:
- Layout:
  - The app contains a ListView which becomes populated with list items.
  - List Items display at least author and title information.
  - The code adheres to all of the following best practices:
    - Text sizes are defined in sp.
    - Lengths are defined in dp.
    - Padding and margin are used appropriately, such that the views are not crammed up against each other.
  - Information displayed on list items is not crowded.
  - Upon device rotation:
    - The layout remains scrollable.
    - The app should save state and restore the list back to the previously scrolled position.
    - The UI should adjust properly so that all contents of each list item is still visible and not truncated.
    - The Search button should still remain visible on the screen after the device is rotated.
- Functionality:
  - The code runs without errors. 
  - The user can enter a word or phrase to serve as a search query. The app fetches book data related to the query via an HTTP request from the Google Books API, using a class such as HttpUriRequest or HttpURLConnection.
  - The app checks whether the device is connected to the internet and responds appropriately. The result of the request is validated to account for a bad server response or lack of server response.
  - The network call occurs off the UI thread using an AsyncTask or similar threading object.
  - The JSON response is parsed correctly, and relevant information is stored in the app.
  - The ListView is properly populated with the information parsed from the JSON response.
  - When there is no data to display, the app shows a default TextView that informs the user how to populate the list.
  - The intent of this project is to give you practice writing raw Java code using the necessary classes provided by the Android framework; therefore, the use of external libraries for core functionality will not be permitted to complete this project.
- Code Readability:
  - All variables, methods, and resource IDs are descriptively named such that another developer reading the code can easily understand their function.
  - The code is properly formatted i.e. there are no unnecessary blank lines; there are no unused variables or methods; there is no commented out code. The code also has proper indentation when defining variables and methods.
  
# Screenshots
[Screenshot 1](https://drive.google.com/open?id=1cTH2ZGpoF-1ayBE9nzr0VTUTB69UcK1X) |
[Screenshot 2](https://drive.google.com/open?id=1A7rwDUWpSp_T9XTKo3Mos-7pJUHz4u4O) |
[Screenshot 3](https://drive.google.com/open?id=1SvgkhA-k5GF-QaBsvFxH26gAnZIqE0X6) |
[Screenshot 4](https://drive.google.com/open?id=1Lvd8D8E6y_VhDmE_6MdqBgnTKTEDHQZ0) |
[Screenshot 5](https://drive.google.com/open?id=1hXqeKrfAOguhx2OwnHZZuBYC0gq3gKem)

# Video
- Video presentation of v2.0 of the application:

[![ScreenShot](https://i.ytimg.com/vi/9TeM_aPnEA0/hqdefault.jpg)](https://youtu.be/9TeM_aPnEA0)

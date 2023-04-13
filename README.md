
# Pokemon Scrapping App


This is an android app that allows users to view and get information on different pokemon.




## Features

- Users can view a grid of pokemon images and their names.
- Users can click on any of the pokemon images to view the details of the selected pokemon.
- The details of the selected pokemon include the pokemon's name, image, description,height, weight, catch rate, egg group, and gender.


## Technologies Used

The app was built with the following technologies:

- Android Studio IDE
- Java programming language
- PHP language for web scrapping API
- Glide Library to load and display images
- Volley Library to fetch data from the web API

## API 

#### Get all items

A web scraping API was created using PHP to extract information about the different pokemons from a website. This API was chosen because it was the only available option to extract the information needed for this app. It provides the name, image, description, height, weight, catch rate, egg group, and gender of each pokemon.

The URL used for the API is **http://10.0.2.2/scrapping_api/pokemon.php**


## Installation

To run the app, download the source code from this Github repository and open it in Android Studio. Run the app on an emulator or a connected android device.

Note that the app requires an active internet connection to fetch data from the API.
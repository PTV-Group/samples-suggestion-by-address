# Suggestions by Address sample

Demonstrates how to get suggestions for the input fields of a Location by Address request based on a possibly incomplete input.

The main focus of the suggestions is on the content of a specified input field. But the content of all other fields provided is also taken into account.

It is intended to use a Suggestions by Address request to help a user fill out an address form which can then be used to generate a Location by Address request. This sample demonstrates how this can be implemeneted by executing the request after each new character that the user types into the input field. The resulting suggestions are then presented in dropdown list to allow the user to select one. 

PTV Developer APIs used in this sample:

- <a href="https://developer.myptv.com/en/documentation/geocoding-places-api">Geocoding & Places API</a>
- <a href="https://developer.myptv.com/en/documentation/vector-maps-api">Vector Maps API</a>


## Getting started
- Open the index.html file with a web browser.
- Insert your ApiKey in the bottom left of the page. Don't forget to press ENTER afterwards.
- Type in the input boxes in the top left corner and get suggestions.
- Choose an entry from the dropdown list
- Press the 'SearchAddress' button to make submit a geocoding
- see markers in the map for each result.

## How it works
The country, postal code, locality and street input fields will suggest matching and existing values.



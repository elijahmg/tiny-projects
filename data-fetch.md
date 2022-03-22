# General information

## Simple approach

During fetching data, you will always need a place where to ask for data in the code and where to store this data.
Start from very simple approach use useEffect and useState in the component where data is required.
Keep in mind that you can't use async function inside useEffect hook.

## More advanced approach

Create custom hook which will take api url and return data from api.


## Project idea

Use [Star Wars api](https://swapi.dev/documentation) to display list of Star Wars planet. 

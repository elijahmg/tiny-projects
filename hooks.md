# General information

First read about hooks in general

[React hooks introduction](https://reactjs.org/docs/hooks-intro.html)

# Simple hooks 

## useState project

Simple counter. There are two elements on the page: button and any text field.
By pressing button, counter is increasing.


## useRef project

useRef mostly used for reference to HTML. You can combine useRef and useEffect in one project.

Connect reference with div element, which will have mousemouve event, which on trigger will console mouse coordinates

## useEffect project
 
...see more in [fetch data](data-fetch.md)

# Custom hooks

The most amazing thing about custom hooks is possibility to use React hooks inside custom.
For inspiration check [useHooks](https://usehooks.com/).

## Project idea

Lets extended an idea from useRef project. Imaging that you will need to re-use mousemove listener on number of HTML throughout a project.
This time create custom hook, which will have functionality for adding and removing listeners. State which will keep mouse coordinates. As an input for hook, reference to HTML elements will be used.
Hook will return coordinates (state).





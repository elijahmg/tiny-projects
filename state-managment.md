# General information

State management is one of the crucial and difficult topics in development.
Sometimes managing state can lead to over-bloated code. One of the leaders within state management some time ago was Redux.
After sometime mobX came into the game. And react from version 16.8 introduced useContext where state can be localized to
specific part of the components tree.

[Article how to use React context](https://kentcdodds.com/blog/how-to-use-react-context-effectively)

## Project idea

Very often in web applications we need to maintain translations of the web pages. Create context for sharing translation
across all components in the project. Use may also use [get](https://lodash.com/docs/#get) from lodash library for easy access of
nested values.



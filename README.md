## Morr Challenge - Jaideep Lalchandani



### Q & A:
<b>1. How did you decide on the technical and architectural choices used as part of your solution?</b>

After reading the project requirements in the README file, I decided to develop this app using the following technologies:

- http://webpack.io/webpack.io/webpack.io (for code compling at runtime)

- Building up atomic design concepts
The construction of React components (previous experience)
- styled-components to make it easy to create my own custom components
- React hooks, which I used to develop my own hooks for dealing with API requests. 
- `react-testing library` I have been thinking of doing unit tests.

<b>2. Are there any improvements you could make to your submission?</b>
  - Unit tests need to be covered
  - CSS needs to be improved [trying to follow with design as much as I can]
  - Need to setup eslint and husky for pre-checking before commit
  - Will refactor `useFetch` function to extract the data filter as an independent function to make code more cleaner
  - Forgot to include `prop-types` (need to add in)

<b>3. What would you do differently if you were allocated more time?</b>
  - Defnitely add unit tests (eg: test the custom hook function I wrote)
  - Polish `webpack.config.js` file
  - Make pixel prefect css (eg: top head bar ingradiant and bottom shadow effect and button styling etc)
  - Separate CSS into few files.
## Whiteboard Challenge 03

Complete today's whiteboard challenge and follow the submission instructions below:

*You're the junior conductor on a commuter train, and have been asked by the senior conductor to do a head count of passengers on the train.*

*Write a function `const traverse = (engine) => {...` which takes the engine as a starting location. Travel from the engine to the caboose, and total the number of passengers in each car as your progress. `return` the final total once your traversal is complete.*

*Each car, including the engine will have the following signature:*
    ```js
    { <engine>
        value: 2,
        next: {  <next car>
            value: 16,
            next: { <next car>
        }
    }
    ```


## Whiteboard Challenge Submission Instructions

## Root Repository Configuration
Configure the root of your repository with the following files and directories.
* **README.md** - contains documentation
* **.gitignore** - contains a [robust](http://gitignore.io) `.gitignore` file
* **.eslintrc** - contains the course linter configuratoin
* **.eslintignore** - contains the course linter ignore configuration

Configure each daily whiteboard solution directory with the following files and directories. Thoughtfully name any other directories or files.
* **pseudo-solution.jpeg** (or other image file format) - containers a picture of your pseudocoded solution from the whiteboarding exercise
* **package.json** - contains npm package config
  * configure a `test` script for running tests with Jest
* **index.js** - contains the executable entry point for your solution
* **lib/** - contains module definitions (if applicable)
* **\_\_test\_\_/** - contains unit tests for any solution code in `index.js` or other modules in the `lib` directory

1. With your assigned partner, pseudocode your solution on the whiteboard. Take a picture of your proposed solution for your repo.
1. Make a new branch and folder in your whiteboard challenge repository on Github. The name of the folder should be the same as the name of the challenge.
1. Complete the whiteboard challenge in your text editor, and verify that it's functional.
1. Include at least three unit tests for each function that you write for your solution.
1. Make a pull request from your working branch to your master branch.
1. Submit a link to your PR on Canvas.
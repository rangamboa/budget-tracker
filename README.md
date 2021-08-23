# Budget Tracker 📊
Budget Tracker is an application that can receive and store input for an account balance both on- and offline. This application demonstrates the importance of an app to be able to store data locally if internet connectivity is lost, and to update data once connectivity has been restored.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents

  1. [Description](#description)
  2. [Installation](#installation)
  3. [Usage](#usage)
  4. [Contribution](#contribution)
  5. [Testing](#testing)
  6. [Questions](#questions)
  7. [Screenshots](#screenshots)
  8. [License](#license)
  
## Description

Budget Tracker is coded using information that the user seeds into a MongoDB database and managed with Mongoose. I made use of the the service worker and manifest files to work behind-the-scenes to be able to store any new information locally should connectivity be throttled or temporarily disabled. As the deployed site is active through Heroku, the Mongo database has been set up and connected with a MongoDB Atlas account.

## Installation

This project uses MongoDB, mongoose, morgan and Express.js. Install these packages if you do not have them on your local machine. 

## Usage

Launch the application with  ``node .\server.js`` in your terminal.

## Contribution

Pleae feel free to contribute and always follow the [Contributor Covenant](http://contributor-covenant.org/version/1/3/0/):

* Fork the reposition
* Create a new branch (``git checkout -b improve-feature``)
* Make, add and commit the appropriate changes in the files
* Push to the branch (``git push origin improve-feature``)
* Create a Pull Request

Thanks!

## Testing

Testing of code was conducted in-browser and the VS Code command line interface.

## Questions

Please don't hesitate to reach out to me via [GitHub](https://github.com/rangamboa) or [email](mailto:rangamboa@gmail.com) if you've got any questions.
## Screenshots

![Screenshot](./assets/images/screenshot-01.jpg 'screenshot')

## License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---
@2021 [Ran Gamboa](https://rangamboa.github.io/portfolio/). ``- Thanks for reading!``
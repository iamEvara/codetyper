# codetyper
This is a project by members of the KalleTech discord server. We are making a website where you can practice your programming speed.

## Links
Website: https://christofferholmesland.github.io/codetyper/

Code: https://github.com/ChristofferHolmesland/codetyper

Discord: https://discord.gg/S6VfJ8jzey

## Setup

Read the contribution [guide](./CONTRIBUTING.md).

Requirements: Node.js and npm

#### Download and install
```bash
# Download the code
$ git clone git@github.com:ChristofferHolmesland/codetyper.git
$ cd codetyper
# Install dependencies
$ npm install
```

Note: Because we are using javascript modules you need a web server set up to serve the files. A simple server you can use is the one that is included with python. Example:
```bash
# Navigate to the project folder
$ cd codetyper
# Start http server
$ python3 -m http.server
# You can access the app from a browser at http://localhost:8000
```

#### Before creating a pull request
```bash
# Format the code
$ npm run prettier
# Run tests
$ npm run tests
```

Pull requests are only accepted if they pass every test and the code formatting is consistent.
# Iron-react
A starter crate for using Rust crate [Iron](https://crates.io/crates/iron) as backend and [ReactJs](https://reactjs.org/) as frontend, built using [webpack](https://webpack.js.org/).

# Prerequisites

* Make sure you have the necessary [Rust toolchain](https://www.rust-lang.org/en-US/install.html) available on your computer.

* Make sure you have the latest version of [Node.js' package ecosystem installed `npm`](https://nodejs.org/en/)

# Install using npm scripts

* Go to your `iron-react` local directory
    > cd my/path/to/iron-react/
* Install every dependencies locally by running
    > npm install
* Run the `npm` script (defined in the `package.json` file)
    > npm run build

The last command should run webpack to compile ReactJs file and build the Rust server side.

# Runing server

* Go to your `iron-react` local directory
    > cd my/path/to/iron-react/
* Run the `npm` script (defined in the `package.json` file)
    > npm run server

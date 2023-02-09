
<div id="top"></div>

![badge](https://img.shields.io/badge/license-MIT-brightgreen)

# [Jest Another RPG](https://github.com/apatheticjedi/jest-another-RPG)

### Table of Contents

1. [Description](#description)
2. [Built With](#built-with)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [Tests](#tests)
7. [Questions](#questions)

## Description

This is a project that was completed for class. It was designed to gain experience in Object-Oriented Programming (OOP) and Test-Driven Development (TDD). This application is an RPG game where a user starts the game by entering their name, then are prompted through a series of 3 battles. During each battle the player's turn is completed by selecting to attack or use a potion. There are 3 potions available. Defeating an enemy grants the player a random potion, of which there are 3 types (strength, agility, and health). After each player turn, the enemy attacks the player, dealing damage. If the player defeats 3 enemies, they win. If they lose all health during a battle, they lose.

### Built With


* JavaScript
* Node.js 
* Inquirer.js
* Jest

## Installation

To install this application, clone this repo, then type
~~~
npm i
~~~
in the command line in the root directory to install all dependencies.

<p align="right">(<a href="#top">back to top</a>)</p>

## Usage

To use, type 
~~~
node app
~~~ 
in the command line to start the application. The player is then presented with their starting stats and an enemy. The player then chooses to attack or use a potion. Potions can either increase attack strength, improve agility, or increase their health. After every player turn, the enemy then attacks the player, dealing damage. Repeat these actions until 3 enemies are defeated, or until the player loses all health and is defeated.

## Contributing

If you wish to contribute to this application, contact me at [GitHub](https://github.com/apatheticjedi).

<p align="right">(<a href="#top">back to top</a>)</p>


## Tests

To run tests, type 
~~~
npm run test
~~~ 
to initiate jest. 3 test suites include a total of 17 tests.


## Questions

Reach out to me with questions at [LinkedIn](https://www.linkedin.com/in/davidlundt/)


## License

[MIT License](https://spdx.org/licenses/MIT.html)


<p align="right">(<a href="#top">back to top</a>)</p>

# Generate unique password

Generate unique password is a library for generating random and unique passwords.

# Installation

```
$ npm install generate-unique-password
```

# Usage

generatePassword([option])

* Generates one password with a given option (number). The passed option determines the length of the password.
* Returns a string.

Example:

```
const generator = require('generate-unique-password');
generator.generatePassword(8);
Output: uiayfofy 
```

# Keywords

generate random unique password
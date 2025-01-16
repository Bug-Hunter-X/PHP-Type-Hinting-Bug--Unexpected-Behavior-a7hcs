# PHP Type Hinting Bug

This repository demonstrates a common bug related to type hinting in PHP. The bug arises from a mismatch in the type of arguments passed to a function and the type of parameters expected by the function. The code in `bug.php` will produce an unexpected output. The corrected code is provided in `bugSolution.php`. 

## How to reproduce the bug

1. Clone the repository.
2. Run `bug.php` using a PHP interpreter. 

## Solution

The solution involves carefully checking the types of arguments passed to functions to ensure they match the declared types of the parameters. The corrected code in `bugSolution.php` demonstrates a proper type handling solution.
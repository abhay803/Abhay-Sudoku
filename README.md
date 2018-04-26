# Abhay-Sudoku
This sudoku app has been developed in vanilla javascript

A fun sudoku game in vanilla javascript.

### Compile

```$ gulp build```

You will find the build inside the folder named ``build/``.


### Test

```$ gulp test``` or ```$ make test-all```

### Implementation

There's a ``client/js/app.js`` that serves as the controller between the UI and the Sudoku class.  The ``Sudoku`` class is a standalone module that could be used with any interface such as CLI. It's based on backtracking, so it considers all the possible configurations until it finds the answer for the sudoku. Because the problem size is relatively small, we can use this approach. For more information about Sudoku solving algorithms visit http://en.wikipedia.org/wiki/Sudoku_solving_algorithms
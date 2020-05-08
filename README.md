# Sudoku solver 

HTTP Server REST in Golang to solve Sudoku
Implementation of a client python to send one or more sudokus to the server. 

## Installation

To install the private repo

```
$ cd $GOPATH/src/github.com/alaouibs
$ git clone https://github.com/alaouibs/sudoku.git
```
## How to get started?

### To start the server

```
$ cd $GOPATH
$ git build github.com/alaouibs/sudoku/
$ ./sudoku
```

### To use the Python client

```
$ cd $GOPATH/src/github.com/alaouibs/sudoku/
$ python client/main.py
```
## How does it work?

The solver uses [backtracking](https://en.wikipedia.org/wiki/Backtracking#Examples) and recursion to find a solution
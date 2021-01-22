# BTree implementation for Go

## Why i am forked:

Unfortunately we are using an old btree implementation of this repo (See commit hash in rotator). On updates of the library version the tests start to fail. 
Rather rewriting the logic in rotator we considered on forking the original repo and just using it. DO NOT UPDATE THE COMMIT HASH OR IT WILL CAUSE THE TESTS TO FAIL. On refactoring and deleting btree usage in rotator, this repo can be archived.


![Travis CI Build Status](https://api.travis-ci.org/google/btree.svg?branch=master)

This package provides an in-memory B-Tree implementation for Go, useful as
an ordered, mutable data structure.

The API is based off of the wonderful
http://godoc.org/github.com/petar/GoLLRB/llrb, and is meant to allow btree to
act as a drop-in replacement for gollrb trees.

See http://godoc.org/github.com/google/btree for documentation.

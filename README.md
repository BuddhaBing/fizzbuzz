# Fizz Buzz

[![Build Status](https://travis-ci.org/treborb/fizzbuzz.svg?branch=master)](https://travis-ci.org/treborb/fizzbuzz)
[![codecov](https://codecov.io/gh/treborb/fizzbuzz/branch/master/graph/badge.svg)](https://codecov.io/gh/treborb/fizzbuzz)

## [Makers Academy](http://www.makersacademy.com) - Pre-course - Week 4 Challenge

## Technologies
* [Ruby v2.3.3](https://www.ruby-lang.org/en/)
* [Rspec](http://rspec.info/)

## Jump To
* [Installation](#install)
* [Usage](#usage)
* [Tests](#tests)

## The Brief

Fizzbuzz is a simple coding challenge, often described as a [code kata](http://codekata.com/).  The objective of Fizzbuzz is to create a program with the following specification:

* The program can be passed a number.
* When passed a number that is a multiple of 3, the program returns the message 'Fizz'.
* When passed a number that is a multiple of 5, the program returns the message 'Buzz'.
* When passed a number that is a multiple of *both* 3 and 5, the program ignores the previous 2 rules and returns the message 'Fizzbuzz'.
* In all other cases, the program simply returns the given number.

## <a name="install">Installation</a>
```
$ git clone https://github.com/treborb/fizzbuzz.git
$ cd fizzbuzz
$ rvm use 2.3.3 --install --binary --fuzzy
$ gem install bundler
$ bundle
```

## <a name="usage">Usage</a>

#### Load up your favourite REPL (e.g. irb)

```
$ irb
```

#### In the REPL
```ruby
$ require "./lib/fizzbuzz"
$ fizzbuzz(3) # "fizz"
$ fizzbuzz(5) # "buzz"
$ fizzbuzz(15) # "fizzbuzz"
$ fizzbuzz(67) # 67
```

## <a name="tests">Running the tests</a>
```
$ rspec
```

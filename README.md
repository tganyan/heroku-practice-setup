# Linked Lists With Recusrion ![travis build status](https://travis-ci.com/tganyan/10-recursion.svg?branch=master)

This is a project for understanding and working with linked lists. Particularly, the objective here is to take an existing bit of code that is manipulating a linked list, add a method for removing an item from the linked list, and test that method.

This is a rehash of the original lab, but removing an item with recursion rather than looping.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You must have NodeJS installed along with either NPM or Yarn.

### Installing

Copy the link from the github repository
In the command line, navigate to the parent directory where you want to store this project
In the command line, type:
```
git clone <repository url>
```
Once the project files are there, type:
```
npm install
```
or
```
yarn i
```

To test the LinkedList methods within scope of linked-list.js, use:
```
const newList = new LinkedList();

for (let i = 0; i < LIST_LENGTH; i++) {
  newList.insertAtHead(`SOME_VALUE`);
}

newList.METHOD_NAME
```

## Running the tests

There are two tests for this program:

1. One test to ensure the correct value is removed from the linked list with the .remove() method
2. One test to ensure an exception is thrown if trying to remove an item from an empty list

I chose to just use the same tests as the original lab, with some slight adjustments so that the method is working off the offset and not a direct value.

To run the tests, from the command line type:
```
npm run test
```
or
````
yarn run test
````

## Built With

* [NodeJS](https://nodejs.org) - The javascript runtime used
* [Jest](https://jestjs.io/) - Testing platform used
* [Eslint](https://eslint.org/) - Coding style linter

## Authors

* [**Tyler Anyan** ](http://tyleranyan.com/)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

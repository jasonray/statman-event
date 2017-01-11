# statman-event [![Build Status](https://travis-ci.org/jasonray/statman-event.svg?branch=master)](https://travis-ci.org/jasonray/statman-event) [![on npm](http://img.shields.io/npm/v/statman-event.svg?style=flat)](https://www.npmjs.org/package/statman-event)
statman-event is one of the capabilities from the statman library. It is a simple help your system record system events for logging and diagnostic purposes

# Install it!
## Option 1: access directly
Install using npm:
```
npm install statman-event
```

Reference in your app:
TODO

## Option 2: access from `statman`
Install using npm:
```
npm install statman
```

Reference in your app:
TODO

# Use it!
## Event Data Model
* id: automatically generated internal identifier
* ref: publisher created unique identifier
* parentId: (optional) points to a parent of this event
* date: date of this event
* delta: if this event represents the conclusion in regards to the parent, then it represents the millliseconds since the parent
* result.status
* result.mesage

## record(event)
Record a single event

## startRecord(event), stopRecord(event)
TODO

## Example
TODO

### Basic usage


 
# Build it!
- Make sure that you have `node` and `npm` installed
- Clone source code to you local machine
- Setup dependencies: `npm install`
- run tests: `npm test`


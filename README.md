node-then
=========

[![Build Status](https://travis-ci.org/node-then/node-then.png)](https://travis-ci.org/node-then/node-then)

Thin wrapper arround Node.js modules that makes the async functions promise
aware. The wrapped methods return a promise the represents the value of the
async operation. Traditional callbacks still work, allowing for a transparent
drop-in.

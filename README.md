# Unhandled Exception in Node.js HTTP Server

This repository demonstrates an example of an unhandled exception in a Node.js HTTP server and how to properly handle it.

## Bug

The `bug.js` file contains a simple HTTP server that throws an unhandled exception if the request URL is `/error`. This causes the server to crash without providing any useful information to the user.

## Solution

The `bugSolution.js` file demonstrates the correct way to handle exceptions in a Node.js HTTP server. It uses a `try...catch` block to catch the exception and gracefully handle it, preventing the server from crashing.
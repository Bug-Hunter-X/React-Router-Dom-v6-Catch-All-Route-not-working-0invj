# React Router Dom v6 Catch All Route Issue
This repository demonstrates a problem with the catch-all route ("/*") in React Router Dom v6.  The catch-all route, intended to handle all unmatched paths, is not functioning correctly, failing to capture routes that don't match explicitly defined routes.

## Problem Description
When navigating to a path that doesn't match any defined routes, the catch-all route fails to render, resulting in unexpected behavior.  This issue only occurs when using the Routes component in v6.

## Solution
The solution involves ensuring that the catch-all route is placed last within the Routes component.  This ensures that it acts as a true catch-all, capturing any routes not matched by preceding routes.

## Setup
1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
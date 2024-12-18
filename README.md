# React Native FlatList Performance Issue

This repository demonstrates a common performance issue encountered when using the `FlatList` component in React Native with a large dataset. The application becomes unresponsive or crashes due to inefficient key extraction or improper data updates.

## Problem

The provided `bug.js` file contains a `FlatList` implementation that struggles to handle a large dataset efficiently.  This inefficiency results in excessive re-renders, leading to performance degradation and potential crashes.

## Solution

The `bugSolution.js` file offers a solution to the problem by optimizing the key extraction and data update processes. By implementing efficient keys and making use of techniques to minimize re-renders, improved performance can be achieved.

## How to Run

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install` to install the dependencies.
4. Run `npx react-native run-android` or `npx react-native run-ios` to run the application.
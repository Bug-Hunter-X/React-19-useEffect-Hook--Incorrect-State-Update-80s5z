# React 19 useEffect Hook: Incorrect State Update

This repository demonstrates a common error when using the `useEffect` hook in React 19, specifically concerning incorrect usage of the previous state value in a functional state update.  The `bug.js` file shows the problematic code, while `bugSolution.js` provides the corrected version.

## Problem

The original code attempts to increment the state using a functional update, but the `prevCount` is not used correctly.  This can lead to unexpected results or infinite loops, especially when the update is asynchronous or depends on external factors.

## Solution

The corrected code ensures that the functional update correctly utilizes the previous state value, guaranteeing that the update is applied sequentially and accurately.

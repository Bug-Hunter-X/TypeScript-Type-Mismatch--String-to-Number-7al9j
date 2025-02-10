# TypeScript Type Mismatch: String to Number

This repository demonstrates a common TypeScript error: type mismatch between string and number.

## Problem

The `add` function is defined to accept two numbers and return their sum. However, it is called with a string argument ('2') leading to a type error because TypeScript's type checking detects the mismatch. 

## Solution

The solution involves converting the string argument to a number using parseInt() or parseFloat() before performing addition.  This ensures type safety and prevents unexpected behavior.
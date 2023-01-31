# Workshop-Expo-2-2

## Project setup

Before starting the project, set it up following the instructions in the [setup](./SETUP.md) section.

## Introduction

The current workshop is a continuation of the Expo Workshop, and without attendance to the first part, it may prove challenging. In a two-hour session, you will aim to develop a login/signup process incorporating advanced features such as `AsyncStorage` and `redux`.

## First step

1. Try to create a fully working login page with the two next requirements :
   - The design must be fully understandable.
   - When the user successfully login, you need to change the page to an home page.

## Second step

1. Now you can do the same with signup page but this time add a field for name and an other field of your choice.

## Third step

1. Implement the `AsyncStorage` feature to store the user's credentials so they don't have to log in every time they open the app.
2. Integrate `redux` to manage the global state of the app, such as the user's authentication status.
3. Add error handling for invalid login/signup attempts.

## Fourth step

1. Implement the forgotten password feature, where users can reset their password if they've forgotten it.
2. Secure the user's data by hashing the password before saving it to the `AsyncStorage`.

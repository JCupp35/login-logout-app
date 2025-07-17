# Login-Logout React App

## Introduction

In this lab, learners will build a simple React app to understand key concepts like state management, props passing, and conditional rendering. State management in React allows components to track and update dynamic data, such as whether a user is logged in or not. Props passing enables parent components to send data or functions to child components, like passing login and logout functions to buttons. Conditional rendering controls what appears on the screen based on the current state, such as showing a login button when logged out or a home page with a logout button when logged in.

## Goal

To practice using React’s useState hook to manage the logged-in state and conditionally render components based on that state. Learners will learn how to create and manage interactions between different components and how to pass functions as props to handle user actions (such as login and logout).

## Objectives

By the end of this lab, learners will:

- Understand how to use useState to manage state in a React application.
- Learn how to conditionally render components based on state.
- Pass functions as props between components.
- Practice component-based architecture and organizing code into multiple files.

## Problem Statement

In this lab, learners will be building a simple application where the user can toggle between a logged-in and logged-out state. Based on the state, different components will be displayed. If the user is not logged in, they will see a Login button. Once they click Login, the app will display a home page along with a Logout button. By clicking Logout, the app will return to the logged-out state.
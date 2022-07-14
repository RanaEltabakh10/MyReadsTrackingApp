# MyReads Project

This is Rana M. El-Tabakh MyReads tracking app for the final assessment project for Udacity's React fundamentals course.

-These two commands will install all of the dependencies needed for this project and will start the server:
* `npm install`
* `npm start`

## project
```bash
├── CONTRIBUTING.md
├── README.md - This file.
├── SEARCH_TERMS.md # The whitelisted short collection of available search terms for you to use with your app.
├── package.json # npm package manager file. It's unlikely that you'll need to modify this.
├── public
│   ├── favicon.ico # React Icon, You may change if you wish.
│   └── index.html # DO NOT MODIFY
└── src
    ├── components
        ├──Book
        ├──Header
        ├──Shelf
        ├──Shelves
    ├──hooks
        ├──useQuery
    ├── App.css # Styles for your app. Feel free to customize this as you desire.
    ├── App.js # This is the root of your app. Contains static HTML right now.
    ├── App.test.js # Used for testing. Provided with Create React App. Testing is encouraged, but not required.
    ├── BooksAPI.js # A JavaScript API for the provided Udacity backend. Instructions for the methods are below.
    ├── icons # Helpful images for your app. Use at your discretion.
    │   ├── add.svg
    │   ├── arrow-back.svg
    │   └── arrow-drop-down.svg
    ├── index.css # Global styles. You probably won't need to change anything here.
    └── index.js # You should not need to modify this file. It is used for DOM rendering only.
```
## How to Use the App
-Books are sorted into three categories: "Currently Reading", "Want to Read" and "Read".
-Every book features green button to change the shelf of the book. Setting option to none hides the book from the shelf.
-New Book can be added to the shelf using purple + button given at the bottom right corner.

--Starter project: https://github.com/udacity/reactnd-project-myreads-starter
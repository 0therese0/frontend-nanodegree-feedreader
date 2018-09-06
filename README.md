# Feed Reader Testing

In this project you are given a web-based application that reads RSS feeds. In this project Jasmine testing framework is used to create a series of test suites.

## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!

## Built with

* Jasmine

## Installation

* Clone the project from Github
* Open index.html file from your browser
* Test suites are at the bottom of the Feeds

## The Tests

1. Tests to make sure that allFeeds variable has been defined and is not empty.
2. Loops through each feed and determines if the URL is defined and not empty.
3. Loops through each feed and determines that each feed has a name and not empty.
4. Ensures the menu element is hidden by default.
5. Ensures that menu changes visibility when menu icon is clicked.
6. Tests that there is at least one entry in feed.
7. Tests that new content is loaded by loadFeed().

## Resources

* [List of Resources](https://www.diigo.com/outliner/fjsk23/Udacity-Feed-Reader-Testing-(project-%234)?key=i5xqspbzvg)
# Project Overview

In this project i was given a web-based application that reads RSS feeds. And using [Jasmine](http://jasmine.github.io/) i started writing test suite. 

## Documentation
* Download the github repository of this project on your machine or clone it from the github, then run it from `index.html` document.
Or 
* Try running the project from this [online Link](https://nadamabrouk.github.io/Feedreader-master-Jasmine/).

# Test Cases included
1. A test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
2. A test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
3. A test suite named `"The menu"`.
4. A test that ensures the menu element is hidden by default. 
5. A test that ensures the menu changes visibility when the menu icon is clicked. 
6. A test suite named `"Initial Entries"`.
7. A test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
8. A test suite named `"New Feed Selection"`.
9. A test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.



## Feed Reader Testing
web-based application that reads RSS feeds tested in Jasmine.Js

## how to run the App:
1. Clone the repository
2. Open the  index.html file .
3. you will fine the tests at the bottom if the page
4. Open the jasmine/spec/feedreader.js file in your editor to start testing.

## What included in the test:
The test is includes 4 suites as follow:
* RSS feeds suite inspecting :
    1- allFeeds variable has been defined and that its not empty.
    2-each feed has a defined URL.
    3-each feed has a defined Name

* The menu suite inspecting :
    1- the menu element is hidden by default.
    2-the menu changes visibility when the menu icon is clicked.and have two expectations:
        A- the menu display when clicked 
        B- the menu is hide when clicked again.

* Initial Entries  suite inspecting :
    1- at least a single .entry element  is called within the .feed container

* New Feed Selection suite inspecting :
    1- a new feed is loaded the loadFeed function that the content actually changes.

## resources used:
udacity.com 
jasmine documentation
youtube tutorials

## needs help:
you can reach me in my e-mail: sma_ez@hotmail.com

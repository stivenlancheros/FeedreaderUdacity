# Project Overview

In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.


Review the Feed Reader Testing [Project Rubric](https://review.udacity.com/#!/projects/3442558598/rubric)

In order to open the web based feedreader you must open in your browser the index.html which you can find inside the project's folder.

To test the feedreader we used Jasmine, doing the following:

1. We created a RRS feeds test suite which includes the "allFeeds are define" test, the idiea is to check whether these feeds are defined or not. 
2.Also the second test is to check if these feedreader which we checked before have an url and the url is not empty.
3. Other test is to go through all these feeds and check if they have an actual name, it is important to have names to make it clear to the public.
4. The next test suite is "the menu" and it first test is to find out if it is hidden by default, in this one we checked the class on the index "menu-hidden". It has to match to "true" since it is actually hidden by default.
5. The next text indide the "the menu " suite is to see if the behaviour when clicked is as expected, it was analized by checking if it shows when hidden = true and if it hides when hidden = False.
6. "initial Entries" is the next following suite, we had to use loadFeed() and done () since this required of asynchronous functions techniques to see if the loadFeed function loaded the contect and the .entry element are shown in the feed that why we used the test "loadFeed adds entries" and to be more than 0 entries.
7. New test suite now: "New Feed Selection" and its first test will ensure that the content changes once the loadFeed function is called and again asynchronous functions so we used done and beforeEach to loop through them


8. Finally Jasmine shows that it passes all the tests

Feel free to try it and test as you wish. Best regards

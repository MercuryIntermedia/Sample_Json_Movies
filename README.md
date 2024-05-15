***IMPORTANT***
Please do not post your code publicly on github/bitbucket/etc. You don't want other developers taking credit for your work by submitting it as their own.

Project description
-------

Build a simple Android app, following Kotlin and Android best practices, that displays movie information. Use your choice of architecture and libraries. The goal is to demonstrate a level of Android competency and code quality. 

No consideration will be given to the aesthetics of the app since this is to be used as a sample of code, and not a "designed" product, but a well thought out approach to the UI code is expected.

App requirements
-------

0. Display a list of movies items that scroll vertically. Each item should display the movie's poster art and all available summary info included in the JSON.
0. The user will be able to tap a movie from the list to show detailed information about that movie on a second screen. The detail information should include all detail information included in the JSON.
0. Images should be cached to reduce load on the server
0. In the case of an image loading error (highly likely), display a red box instead of the image.
0. The app must support landscape and portrait orientations
0. The app must handle any data or connectivity errors gracefully by displaying an error message to the user
0. The minimum Android OS supported is 10

Data sources
-------

The data should be pulled from the raw json files in this repo using
the most recent commit. Use the following pattern for the base API url:
https://raw.githubusercontent.com/MercuryIntermedia/Sample_Json_Movies/[commitId]/

The list of top movies is available in the file "top_movies.json" in
this repo: [baseUrl]/top_movies.json

For example:
https://raw.githubusercontent.com/MercuryIntermedia/Sample_Json_Movies/35cccb4bb96bc00575f34ab49bb0f56bf7c77f0e/top_movies.json

The details for each movie are available under that base using the patterns: [baseUrl]/by_id/[imdbId].json

For example:
https://raw.githubusercontent.com/MercuryIntermedia/Sample_Json_Movies/35cccb4bb96bc00575f34ab49bb0f56bf7c77f0e/by_id/tt0035575.json

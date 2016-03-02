Build a simple app that lists the top 100 movies in a list with more
details provide on clicking a movie. Use your choice of architecture and
libraries.


The data should be pulled from the raw json files in this repo using
the most recent commit. Use the following pattern for the base API url:
https://raw.githubusercontent.com/MercuryIntermedia/Sample_Json_Movies/[commitId]/

The list of top movies is available in the file "top_movies.json" in
this repo: [baseUrl]/top_movies.json

For example:
https://raw.githubusercontent.com/MercuryIntermedia/Sample_Json_Movies/35cccb4bb96bc00575f34ab49bb0f56bf7c77f0e/top_movies.json

The list should show the poster, summary info and when clicking on the row should open a details screen.

The details for each movie are available under that base using the patterns: [baseUrl]/by_id/[imdbId].json

For example:
https://raw.githubusercontent.com/MercuryIntermedia/Sample_Json_Movies/35cccb4bb96bc00575f34ab49bb0f56bf7c77f0e/by_id/tt0035575.json


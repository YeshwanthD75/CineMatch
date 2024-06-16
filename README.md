# CineMatch
Movie Recommendation System


CineMatch is a simple in-memory movie recommendation system that allows users to add, search, recommend, and delete movies. This application is built using Python with a Tkinter graphical user interface.

Features
1. Add Movie: Users can add movies with details such as title, genre, rating, actors, year, industry, and OTT platform.
2. Search Movie: Users can search for movies by title, genre, actor, or industry.
3. Recommend Movies: Users can get top N movie recommendations based on rating or industry.
4. Delete Movie: Users can delete movies from the list by title.

Usage

Adding a Movie:
1. Navigate to the "Add Movie" tab.
2. Fill in the movie details: title, genre, rating, actors (comma-separated), year, industry, and OTT platform.
3. Click "Add Movie" to add the movie to the list.
4. The list of movies added will be displayed at the bottom of the tab.

Searching for a Movie:
1. Navigate to the "Search Movie" tab.
2. Enter a search term and select a search criteria (title, genre, actor, or industry).
3. Click "Search" to find matching movies.
4. The search results will be displayed below.

Recommending Movies:
1. Navigate to the "Recommend Movies" tab.
2. Enter the number of movies you want to be recommended.
3. Select a recommendation criteria (rating or industry).
4. Click "Recommend" to get the top N movie recommendations.
5. The recommendations will be displayed below.

Deleting a Movie:
1. Navigate to the "Delete Movie" tab.
2. Enter the title of the movie you want to delete.
3. Click "Delete Movie" to remove the movie from the list.

Sorting Algorithm

CineMatch uses the Merge Sort algorithm to sort movies by rating for the recommendation feature. Merge Sort is a comparison-based sorting algorithm with an average and worst-case time complexity of O(n log n).

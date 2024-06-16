# CineMatch
Movie Recommendation System

CineMatch
CineMatch is a simple in-memory movie recommendation system that allows users to add, search, recommend, and delete movies. This application is built using Python with a Tkinter graphical user interface.

Features
Add Movie: Users can add movies with details such as title, genre, rating, actors, year, industry, and OTT platform.
Search Movie: Users can search for movies by title, genre, actor, or industry.
Recommend Movies: Users can get top N movie recommendations based on rating or industry.
Delete Movie: Users can delete movies from the list by title.

Usage
Adding a Movie:

Navigate to the "Add Movie" tab.
Fill in the movie details: title, genre, rating, actors (comma-separated), year, industry, and OTT platform.
Click "Add Movie" to add the movie to the list.
The list of movies added will be displayed at the bottom of the tab.
Searching for a Movie:

Navigate to the "Search Movie" tab.
Enter a search term and select a search criteria (title, genre, actor, or industry).
Click "Search" to find matching movies.
The search results will be displayed below.
Recommending Movies:

Navigate to the "Recommend Movies" tab.
Enter the number of movies you want to be recommended.
Select a recommendation criteria (rating or industry).
Click "Recommend" to get the top N movie recommendations.
The recommendations will be displayed below.
Deleting a Movie:

Navigate to the "Delete Movie" tab.
Enter the title of the movie you want to delete.
Click "Delete Movie" to remove the movie from the list.
Sorting Algorithm
CineMatch uses the Merge Sort algorithm to sort movies by rating for the recommendation feature. Merge Sort is a comparison-based sorting algorithm with an average and worst-case time complexity of O(n log n).

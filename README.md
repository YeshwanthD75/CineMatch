# CineMatch
Movie Recommendation System

CineMatch is a simple in-memory movie recommendation system that allows users to add, search, recommend, and delete movies. This application is built using Python with a Tkinter graphical user interface.

<h2>Features</h2>

1. Add Movie: Users can add movies with details such as title, genre, rating, actors, year, industry, and OTT platform.
2. Search Movie: Users can search for movies by title, genre, actor, or industry.
3. Recommend Movies: Users can get top N movie recommendations based on rating or industry.
4. Delete Movie: Users can delete movies from the list by title.

<h3>Usage</h3>

<h4>Adding a Movie:</h4>
1. Navigate to the "Add Movie" tab.<br>
2. Fill in the movie details: title, genre, rating, actors (comma-separated), year, industry, and OTT platform.<br>
3. Click "Add Movie" to add the movie to the list.<br>
4. The list of movies added will be displayed at the bottom of the tab.

<h4>Searching for a Movie:</h4>
1. Navigate to the "Search Movie" tab.<br>
2. Enter a search term and select a search criteria (title, genre, actor, or industry).<br>
3. Click "Search" to find matching movies.<br>
4. The search results will be displayed below.

<h4>Recommending Movies:</h4>
1. Navigate to the "Recommend Movies" tab.<br>
2. Enter the number of movies you want to be recommended.<br>
3. Select a recommendation criteria (rating or industry).<br>
4. Click "Recommend" to get the top N movie recommendations.<br>
5. The recommendations will be displayed below.

<h4>Deleting a Movie:</h4>
1. Navigate to the "Delete Movie" tab.<br>
2. Enter the title of the movie you want to delete.<br>
3. Click "Delete Movie" to remove the movie from the list.

<h3>Sorting Algorithm</h3>

CineMatch uses the Merge Sort algorithm to sort movies by rating for the recommendation feature. Merge Sort is a comparison-based sorting algorithm with an average and worst-case time complexity of O(n log n).

# personal_movie_watchlist_analytics

## Overview
This repository contains a personal learning project aimed at:
1. **Ingesting movie data** from external APIs (TMDb, optionally OMDb).
2. **Storing** the data in a relational SQL database.
3. **Performing analytics** to compare and contrast different ratings (e.g., TMDb vs. IMDb).
4. **Tracking a personal watchlist** where I can can mark movies as watched, rate them personally, and generate insights.

## Features
- **API Data Ingestion**: Python scripts that call TMDb (for rich metadata, cast/crew) and optionally OMDb (for IMDb/Rotten Tomatoes/Metacritic ratings).
- **SQL Database Schema**: A normalized set of tables (Movies, Genres, Movie_Genres, People, Movie_Cast, Watchlist, etc.) demonstrating relational integrity and indexing.
- **Advanced Queries**: Analytical queries to find top directors, interesting rating discrepancies, actor collaborations, etc.
- **Watchlist Functionality**: A user-centric table or feature for keeping track of watched/unwatched movies, personal ratings, etc.

## Project Structure

movie-watchlist-analytics/
│
├── README.md              # Main project overview
├── docs/
│    └── ERD.md            # Entity Relationship Diagram & schema details
├── scripts/
│    ├── ingest_tmdb.py    # Python script to call TMDb API
│    ├── ingest_omdb.py    # Optional Python script for IMDb/RT ratings
│    └── ...
├── sql/
│    ├── schema.sql        # Contains CREATE TABLE statements
│    ├── sample_queries.sql # Contains advanced queries for demonstration
│    └── ...
└── .gitignore             # Ignore logs, etc.


## Getting Started

### API Keys
**API Keys**: 
- [TMDb API Key] (https://developer.themoviedb.org/reference/intro/authentication)

- [OMDb API Key](http://www.omdbapi.com/) 


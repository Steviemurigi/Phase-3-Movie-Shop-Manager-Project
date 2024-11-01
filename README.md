# MovieShop Manager

## Description

**MovieShop Manager** is a command-line application designed to manage movie shops and their inventory of movies. Users can create, update, delete, and search for movie shops and movies based on various criteria such as genre and title.

## Features

- List all movie shops
- Find movie shops by name or ID
- Create, update, and delete movie shops
- List all movies in the database
- Find movies by title, genre, or ID
- Create, update, and delete movies
- View all movies available at a specific movie shop

## Project Structure

```
│
├── 📂 lib/                   
│   ├── 📂 models/
│   │   ├── 📄 __init__.py            
│   │   ├── 📄 movie.py
│   │   └── 📄 movieshop.py            
│   │   
│   ├── 📄 cli.py   
│   ├── 📄 helpers.py
│   └── 📄 seed.py
│      
├── movies.db                 
├── Pipfile
├── Pipfile.lock
└── README.md                

```

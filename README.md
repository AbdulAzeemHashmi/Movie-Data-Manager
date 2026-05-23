# Movie Data Manager (C++ No-STL)

This project is a comprehensive **Movie Management System** developed as part of the Data Structures course (Fall 2025) at **FAST-NUCES, Islamabad**. It is designed to handle, search, and analyze the IMDb 5000 movie dataset efficiently.

## 👥 Team Members
- **Abdul Ghafoor** (24I-0118)
- **Abdul Azeem** (24I-2013)

## 📌 Project Overview
The system provides a robust interface to manage movie records. A key constraint of this project was the **strict prohibition of the C++ Standard Template Library (STL)**. Every data structure used, from Linked Lists to Graphs, has been implemented manually from scratch.

## 🛠️ Core Data Structures Implemented
- **AVL Tree**: Used for storing movie records to ensure balanced $O(\log n)$ search, insertion, and deletion.
- **Hash Table**: Implemented for fast indexing of actors and genres, allowing for near-instant filtering.
- **Graph (Adjacency List)**: Used to model relationships between movies (shared actors, directors, etc.) and for the recommendation engine.
- **Custom Templates**: Manually built Linked Lists, Stacks, and Queues.

## 🚀 Key Features
- **Dataset Parsing**: Custom CSV parser to load and process 5000+ records from `movie_metadata.csv`.
- **Search Engine**: Search movies by title, actor, or genre.
- **Graph-Based Recommendations**: Suggests movies based on connectivity in the graph (BFS/DFS).
- **Degrees of Separation**: Finds the shortest path between two movies or actors using Breadth-First Search (BFS).
- **CRUD Operations**: Complete support for adding, updating, and removing movie records.

## 💻 Installation & Usage
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/AbdulAzeemHashmi/MOVIE-DATA-MANAGER.git](https://github.com/AbdulAzeemHashmi/MOVIE-DATA-MANAGER.git)
   ```
   
## Compile:
   ```bash
   g++ 24I-0118_24I-2013_DS Project.cpp -o MovieManager
   ```

## Run:
   ```bash
   ./MovieManager
   ```

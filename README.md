# Movie Data Manager (C++ No-STL)

This project is a comprehensive **Movie Management System** developed as part of the Data Structures course (Fall 2025) at **FAST-NUCES, Islamabad**. It is designed to handle, search, and analyze the IMDb 5000 movie dataset efficiently.

---

## 👥 Team Members

| Name | Roll Number |
|------|-------------|
| Abdul Ghafoor | 24I-0118 |
| Abdul Azeem | 24I-2013 |

---

## 📌 Project Overview

The system provides a robust interface to manage movie records. A key constraint of this project was the **strict prohibition of the C++ Standard Template Library (STL)**. Every data structure used, from Linked Lists to Graphs, has been implemented manually from scratch.

---

## 🛠️ Core Data Structures Implemented

| Structure | Purpose |
|-----------|---------|
| **AVL Tree** | Stores movie records for balanced O(log n) search, insertion, and deletion |
| **Hash Table** | Fast indexing of actors and genres for near-instant filtering |
| **Graph (Adjacency List)** | Models relationships between movies and powers the recommendation engine |
| **Custom Templates** | Manually built Linked Lists, Stacks, and Queues |

---

## 🚀 Key Features

- **Dataset Parsing** -- Custom CSV parser to load and process 5000+ records from `movie_metadata.csv`
- **Search Engine** -- Search movies by title, actor, or genre
- **Graph-Based Recommendations** -- Suggests movies based on graph connectivity using BFS/DFS
- **Degrees of Separation** -- Finds the shortest path between two movies or actors using BFS
- **CRUD Operations** -- Full support for adding, updating, and removing movie records

---

## 💻 Installation & Usage

### 1. Clone the repository

```bash
git clone https://github.com/AbdulAzeemHashmi/MOVIE-DATA-MANAGER.git
cd MOVIE-DATA-MANAGER
```

### 2. Compile

```bash
g++ "24I-0118_24I-2013_DS Project.cpp" -o MovieManager
```

### 3. Run

```bash
./MovieManager
```

> **Note:** Make sure `movie_metadata.csv` is present in the same directory as the executable before running.

---

## 📁 Project Structure

```
MOVIE-DATA-MANAGER/
├── 24I-0118_24I-2013_DS Project.cpp   # Main source file
├── movie_metadata.csv                  # IMDb 5000 dataset
└── README.md
```

---

## 🏫 Course Info

- **Course:** Data Structures (Fall 2025)
- **University:** FAST-NUCES, Islamabad

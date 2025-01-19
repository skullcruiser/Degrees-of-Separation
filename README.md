# Degrees of Separation

This project finds the shortest connection between two actors using IMDb data. It models actors as **nodes** and movies as **edges**, implementing **Breadth-First Search (BFS)** to determine the minimal degrees of separation. 

## Usage
1. **Download & Setup**  
  Download and unzip degrees.zip.
  In terminal, change directory to the folder in which degrees.py and testing_data folder exist.
  
3. **Run the Program**  
   ```bash
   $ python degrees.py testing_dat
   ```

4. **Example Output**  
   ```bash
   $ python degrees.py testing_data
    Loading data...
    Data loaded.
    Name 1: Tom Hanks
    Name 2: Demi Moore
    2 degrees of separation.
    1: Tom Hanks and Kevin Bacon starred in Apollo 13
    2: Kevin Bacon and Demi Moore starred in A Few Good Men
   ```

## Implementation
- **Graph Representation**: Actors (nodes) are connected by movies (edges).  
- **Algorithm**: BFS ensures the shortest path between two actors.  

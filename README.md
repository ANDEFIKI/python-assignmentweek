andefiki assigment week2 

A simple Python script demonstrating fundamental list operations and manipulation techniques. This educational project showcases various methods to create, modify, and work with Python lists.

## 📋 Project Overview

This project contains a single Python file (`index.py`) that demonstrates essential list operations through a practical example. The script creates a list, performs various manipulations, and outputs the final results.

## 🚀 Features

- **List Creation**: Initialize empty lists and populate with elements
- **Element Addition**: Use `append()` and `extend()` methods
- **Element Insertion**: Insert elements at specific positions
- **Element Removal**: Remove elements using `pop()`
- **List Sorting**: Sort lists in ascending order
- **Index Finding**: Locate specific elements using `index()`
- **Comprehensive Output**: Clear demonstration of each operation's effect

## 🛠️ Technologies Used

- **Python 3.x**: Core programming language
- **Standard Library**: No external dependencies required

## 📁 Project Structure

```
python-assignment-week2/
├── index.py          # Main script demonstrating list operations
└── README.md         # Project documentation
```

## 🎯 Learning Objectives

By examining this code, you'll learn:
- How to create and initialize Python lists
- Different methods to add elements to lists
- How to insert elements at specific positions
- Techniques for removing elements from lists
- List sorting and searching operations
- Understanding list indices and their usage

## 🔧 Code Breakdown

### 1. List Creation
```python
my_list = []
```
Creates an empty list to start with.

### 2. Adding Elements
```python
my_list.append(10)  # Adds single elements
my_list.extend([50, 60, 70])  # Adds multiple elements
```

### 3. Inserting Elements
```python
my_list.insert(1, 15)  # Inserts 15 at index 1
```

### 4. Removing Elements
```python
my_list.pop()  # Removes and returns the last element
```

### 5. Sorting
```python
my_list.sort()  # Sorts the list in ascending order
```

### 6. Finding Elements
```python
index_of_30 = my_list.index(30)  # Returns the index of value 30
```

## 🏃‍♂️ Getting Started

### Prerequisites
- Python 3.x installed on your system

### Running the Script
1. Clone or download the project files
2. Navigate to the project directory
3. Run the script using:
   ```bash
   python index.py
   ```

### Expected Output
```
Index of 30 in my_list: 4
Final my_list: [10, 15, 20, 30, 40, 50, 60]


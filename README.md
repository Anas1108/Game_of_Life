# Game_of_Life
The Game of Life is a simple yet powerful simulation that demonstrates how complex behavior can emerge from a small set of simple rules.


**PROGRAMMING FUNDAMENTAL PROJECT: Game of Life**

**Libraries**

**#include "stdafx.h"**

**“Header stdafx.h is basically used in Microsoft Visual Studio to let the  compiler know the files that are once compiled and no need to  compile it from scratch”.**    

**#include <iostream>**

**“To include input output functions in our program”.**

**#include "conio.h"**

**“This header declares several useful library functions for performing "console input and output".**

**#include "fstream"**

**“It represents both output Stream and input Stream. So this library is used to read from files and write to files.”**

**#include<math.h>**

**“This header file in the standard library designed for basic mathematical operations.”**

**Functions**

**void Game(int genrs, int numOfIniLiveCells,int\* int\* liveLocX,int\* liveLocY);**

**“Populate grid with 0's and 1's or Populate UnInit Array (Array of Locations of Live Cells”**

**void Start();**

**“Starts the game, and simulates the grid up to "generations" generations.”**

**void PopulateGrid();**

**“Populates two-dimensional dynamic array "grid".**

` `**Instantiates two-dimensional dynamic array "neighborsCountGrid”**

**void PopulateLiveCells();**

**“Populates UnInit Array "liveCells" with the locations of initial live cells”**

**bool IsLiveLocation(int locationX, int locationY);**

**“Returns true if location is a live location.**

` `**Return false, otherwise.”**

**bool IsLocationOutOfBounds(int locationX, int locationY);**

**“Returns true if location is out of bounds, false otherwise.”**

**int CountLiveNeighbors(int locationX, int locationY);**

**“Returns the number of live neighbors of given location.**

**This method uses 8-Neigbor Connectivity.”**

**void InsertLiveCell(int locationX, int locationY);**

**“Inserts location of a live cell in "liveCells" array.”**

**void DeleteLiveCell(int locationX, int locationY);**

**“Delete a live cell at location "location”**

**void AddNeighbors();**

**Updates "neighborsCountGrid" in each generation**

**void PropagateCells();**

**“Propagates the cells and applies the rules of life.”**

**void Display();**

**“Displays the grids and UnInitialized array.”**


**Workflow**

At start, the Program reads a file through command line arguments.

The file provides the number of iterations, Number of coordinates and coordinate values.

After reading the file, it initially populates the grid with the given coordinates.

Then find the neighbors and apply the rules, as given accordingly, on the cells. 

Also maintains the count and record of updated coordinates in Un Initialized array.

At the end it displays the result at once.

**Output Screenshot**




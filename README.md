# CPP_SortingAlgorithm_Templates
Different sorting algorithm templates for C++, with optional multithreading.


## Included algorithms:
  - cycle sort
  - bubble sort
  - bubble sort recursivly
  - shell sort
  - comb sort
  - gnome sort
  - gnome sort with jump to last correct position (insertionsort)
  - radix sort
  - slow radix sort  (without move semantics)
  - radix sort in-place and mixed with insertionsort (multithreading)
  - bogo sort
  - bozo sort
  - selection sort
  - insertion sort
  - insertion sort with binary search
  - odd-even-sort (multithreading)
  - shaker sort
  - quick sort (multithreading)
  - merge sort (multithreading)
  - heap sort 
  - intro sort (multithreading)


## How to use

```
  #include "Sorting_Algorithms.h"
  //do stuff
  std::vector<int> data(100);
  //do stuff
  sorting::combsort(data.begin(),data.end());
  //optional with custom compare
  //sorting::combsort(data.begin(),data.end(),[](const int & a, const int & b){ return a > b;});
```

![](https://github.com/Kevger/SortVisualization/blob/master/Screenshots/Example1.png "My other project")
This library is used in my other project  [SortVisualization](https://github.com/Kevger/SortVisualization)

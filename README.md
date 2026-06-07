# Sorting Methods

A collection of common sorting algorithms implemented in C.

## Overview

This repository contains implementations of fundamental sorting methods, demonstrating different algorithmic approaches to sorting data. Each implementation is designed to be educational and easy to understand.

## Sorting Methods

| Method | Status | Description |
|--------|--------|-------------|
| Bubble Sort | ✅ Complete | Simple comparison-based sort with O(n²) time complexity |
| Insertion Sort | ✅ Complete | Builds sorted array one item at a time with O(n²) worst case |
| Selection Sort | ✅ Complete | Selects minimum element repeatedly with O(n²) complexity |
| Merge Sort | ⏳ Pending | Divide-and-conquer approach with O(n log n) time complexity |
| Shell Sort | ✅ Complete | Generalization of insertion sort with O(n log n) average case |
| Quick Sort | ⏳ Pending | Partition-based sorting with O(n log n) average case |

## Project Structure

```
sorting-methods/
├── README.md
└── [source files]
```

## Getting Started

### Prerequisites

- C compiler (gcc, clang, etc.)
- Make or equivalent build tool (optional)

### Compilation

To compile the sorting methods:

```bash
gcc -o sorting_program <source_files.c>
```

## Algorithms Explained

### Completed Implementations

- **Bubble Sort**: Repeatedly steps through the list, compares adjacent elements, and swaps them if they're in the wrong order.
- **Insertion Sort**: Builds the final sorted array one item at a time by inserting elements into their correct position.
- **Selection Sort**: Divides input into sorted and unsorted regions, repeatedly selecting the minimum from the unsorted region.
- **Shell Sort**: An optimization of insertion sort that allows the exchange of items that are far apart.

### In Progress

- **Merge Sort**: Recursively divides the array in half and merges sorted subarrays.
- **Quick Sort**: Uses a pivot element to partition the array and recursively sorts the partitions.

## Contributing

Contributions are welcome! Feel free to:
- Complete pending implementations
- Optimize existing algorithms
- Add additional sorting methods
- Improve documentation

## License

This project is open source and available under the MIT License.

## Author

Created by gustavoscheffer

# StockAnalyser

A C# console application for stock data analysis built as part of university coursework. The application allows users to load stock datasets, search for specific shares, and sort them using a variety of algorithms — with a clear, menu-driven interface.

---

## About

This project was developed as part of a coursework assignment. It demonstrates the practical application of classic searching and sorting algorithms on real-world-style data, using stock share prices as the dataset.

---

## Features

- Load and display stock data from `.txt` dataset files
- **Search** for shares using multiple algorithms
- **Sort** share data using multiple algorithms
- Interactive menu-driven console interface
- Visual output for results

---

## Project Structure

```
StockAnalyser/
├── Menu.cs               # Main navigation menu logic
├── Program.cs            # Application entry point
├── Search.cs             # Search algorithm implementations
├── Solution.cs           # Core solution logic
├── Sort.cs               # Sort algorithm implementations (merge sort, descending)
├── User.cs               # User interaction and input handling
├── Visuals.cs            # Display and output formatting
├── Share_1_2048.txt      # Dataset: Share 1 (2048 data points)
├── Share_1_256.txt       # Dataset: Share 1 (256 data points)
├── Share_2_2048.txt      # Dataset: Share 2 (2048 data points)
├── Share_2_256.txt       # Dataset: Share 2 (256 data points)
├── Share_3_2048.txt      # Dataset: Share 3 (2048 data points)
├── Share_3_256.txt       # Dataset: Share 3 (256 data points)
└── StockAnalyser.csproj  # Project file
StockAnalyser.sln         # Solution file
```

---

## Search Algorithms

The application supports multiple search methods, selectable from the menu:

- **Linear Search** — iterates through all data points sequentially
- **Binary Search** — efficient search on sorted data using divide and conquer

---

## Sort Algorithms

The application supports multiple sorting methods, selectable from the menu:

- **Merge Sort (Descending)** — divide and conquer sorting, implemented to order from highest to lowest

---

## Getting Started

### Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) (version 6.0 or later recommended)

### Running the Application

1. Clone the repository:
   ```bash
   git clone https://github.com/nixonthefourth/StockAnalyser.git
   cd StockAnalyser
   ```

2. Build and run:
   ```bash
   dotnet run --project StockAnalyser
   ```

---

## Datasets

The project includes six pre-loaded stock datasets across three shares, each available in two sizes:

| Dataset | Data Points |
|---|---|
| Share 1 | 256 / 2048 |
| Share 2 | 256 / 2048 |
| Share 3 | 256 / 2048 |

The larger datasets (2048 points) are useful for benchmarking the performance differences between search and sort algorithms.

---

## Coursework Note

This project was submitted as part of university coursework on the "Algorithms and Complexity" module. The codebase follows a structured development workflow – changes were developed on a separate `dev` branch and merged into `main` via pull requests after review.

---

## Author

**Mykyta 'Nick' Kho...** — [@nixonthefourth](https://github.com/nixonthefourth)

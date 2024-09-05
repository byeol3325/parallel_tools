# Parallelism Tool for C++

This repository contains a tool designed to optimize and experiment with **parallel processing in C++** using `std::thread`. The primary objective of this tool is to identify which functions or computations can be parallelized safely without causing data races, deadlocks, or other concurrency-related issues.

## Features

- **Thread Management**: Efficiently manage threads by reusing them where possible to minimize overhead and improve performance.
- **Safe Parallelization**: Identify functions that can be safely parallelized and those that should remain sequential.
- **Concurrency Error Handling**: Provides mechanisms to detect and prevent common concurrency issues such as data races and deadlocks.
- **Experimental Setup**: Easily run experiments with different levels of parallelism to determine the most effective configurations for specific workloads.

## Getting Started

### Prerequisites

- C++17 or later is required to use `std::thread` and other concurrency features.
- A compatible C++ compiler such as GCC, Clang, or MSVC.

### Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/byeol3325/parallel_tool.git
cd parallel_tools
```

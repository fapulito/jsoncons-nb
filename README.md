# Notebooks using ``jsoncons`` and other libraries to manipulate data structures in Python

# Serializable Dictionaries in Python 
## A Comprehensive Guide with Interactive Jupyter Notebooks 📖

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.7%2B-blue.svg)](https://www.python.org/)

<!-- [![Build Status](https://travis-ci.org/your_username/your_repo.svg?branch=main)](https://travis-ci.org/your_username/your_repo) -->

Welcome! This repository provides a comprehensive guide and practical examples for understanding and using serializable dictionaries in Python. Dictionaries are fundamental, and knowing how to effectively serialize (save/transmit) and deserialize (load/receive) them is a key skill for any Python developer.

This guide covers everything from basic concepts to advanced techniques, performance considerations, security implications, and real-world applications.

## ✨ Features

*   **Clear Explanations:** Understand *what* serialization is and *why* it's essential.
*   **Multiple Formats:** Explore and compare popular formats:
    *   **JSON:** The web standard – lightweight and human-readable.
    *   **Pickle:** Python's native format – powerful but with security caveats.
    *   **YAML:** Highly readable, great for configuration.
    *   **MessagePack:** Fast and compact binary format.
    *   **HDF5:** High-performance format for large numerical datasets (often used with NumPy arrays within dictionaries).
*   **Advanced Techniques:** Learn how to handle custom objects, circular references, optimize performance, and manage large data streams.
*   **Practical Examples:** See serialization in action for:
    *   Configuration Management (`yaml`)
    *   API Data Exchange (`json`, `requests`)
    *   Caching (`pickle`)
    *   Data Persistence (Simple Inventory System using `json`)
*   **Security Focus:** Understand the critical security risks of deserialization (especially `pickle`) and the importance of input validation (`jsonschema`).
*   **Best Practices:** Actionable advice on choosing formats, versioning data, handling errors, and testing your code.
*   **Jupyter Notebooks:** Interactive learning experience through three detailed notebooks:
    1.  `1_Introduction_to_Serialization.ipynb`: Basics and common formats.
    2.  `2_Advanced_Serialization_Performance.ipynb`: Custom objects, performance, HDF5 comparison.
    3.  `3_Practical_Applications_Best_Practices.ipynb`: Real-world use, security, best practices.
*   **(Optional) `serial-json` Package:** A companion utility package providing a simple CLI for JSON handling (see details below).

## 🚀 Getting Started

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/fapulito/serial-json-nb.git
    cd serial-json-nb
    ```
2.  **Set up a virtual environment (Recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
3.  **Install dependencies:**
    *   For core notebooks (JSON, Pickle): No external dependencies needed beyond Python 3.
    *   For advanced examples:
        ```bash
        pip install -r requirements.txt
        ```
        *(You'll need to create a `requirements.txt` file listing `pyyaml`, `msgpack-python`, `requests`, `jsonschema`, `h5py`, `numpy`)*
4.  **Launch Jupyter:**
    ```bash
    jupyter notebook
    # or
    jupyter lab
    ```
5.  Open and run the notebooks (`.ipynb` files) in order. Happy Serializing! 🎉

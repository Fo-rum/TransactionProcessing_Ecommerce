# 🛒 Transaction Processing in E-commerce Systems

## Project Overview

This project simulates transaction processing in a distributed e-commerce system. It models transaction execution across interconnected servers using Python, and explores key concepts such as concurrency, task scheduling, and distributed coordination. Each transaction passes through a series of "hops," simulating real-world communication and task distribution in e-commerce platforms.

The project includes multiple modules for simulating transaction hops, managing server connections, and implementing scheduling strategies with and without threading.

---

## Files Included

| File | Description |
|------|-------------|
| `main.py` | Main entry point that orchestrates the transaction simulations. |
| `connections.py` | Defines the server or node connections used for transaction routing. |
| `scheduling.py` | Contains logic for sequential scheduling of transactions. |
| `threadScheduling.py` | Implements concurrent/threaded scheduling for better performance. |
| `Transaction1_hops.py` to `Transaction9_hops.py` | Simulate different transaction paths and hops across systems. |
| `Output.txt` | Output logs from a sample run of the simulation. |
| `Transaction Research Paper.pdf` | Supplementary document detailing the underlying concepts and approach. |

---

## Getting Started

### Prerequisites

- Python 3.6 or higher  
- Works on any OS (Linux recommended for testing multithreading performance)

### Installation

Clone this repository:

```bash
git clone https://github.com/your-username/transaction-processing-ecommerce.git
cd transaction-processing-ecommerce
```

No external packages required. Ensure you’re using Python 3.6+.

---

## Usage

Run the main simulation:

```bash
python3 main.py
```

### Key Components

#### `main.py`
- Initializes the environment and executes transaction paths.

#### `scheduling.py`
- Runs transactions in a sequential (non-threaded) manner.

#### `threadScheduling.py`
- Executes transactions concurrently using threading for improved efficiency.

#### `TransactionX_hops.py`
- Each module contains the logic for a specific transaction’s path (X = 1 to 9).
- These scripts simulate how transactions "hop" from one system to another.

---

## Project Structure

```
├── main.py
├── connections.py
├── scheduling.py
├── threadScheduling.py
├── Transaction1_hops.py
├── ...
├── Transaction9_hops.py
├── Output.txt
├── README.md
└── Transaction Research Paper.pdf
```

---

## Technologies Used

- **Python 3**: Core programming language for simulation.
- **Threading Module**: For handling concurrent transaction processing.

---

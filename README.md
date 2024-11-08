# PyPlaneTicket

**PyPlaneTicket** is a Python library designed to search and compare airplane ticket prices across various airlines. With a modular and scalable structure, PyPlaneTicket allows easy integration with multiple airline APIs, enabling users to fetch and display flight prices, schedules, and more.

## Features

- **Multi-Airline Support**: Each airline has its own module, following a standard interface for consistent functionality.
- **Customizable Search**: Search for flights based on origin, destination, date, and other parameters.
- **Flexible Data Extraction**: Easily retrieve flight prices, schedules, and other essential flight details.
- **Modular Structure**: Extensible and well-organized, allowing for easy addition of new airlines.

## Installation

To install PyPlaneTicket, just type:

```bash
pip install PyPlaneTicket
```

## The Lib File Structure

```bash
PyPlaneTicket/
├── pyplaneticket/
│   ├── __init__.py
│   ├── flights.py
│   ├── utils.py
│   ├── exceptions.py
│   └── airlines/                  # Directory for airline modules
│       ├── __init__.py
│       ├── airline_base.py        # Base class (or interface) for airlines
│       ├── azul.py                # Specific module for the Azul airline (Azul)
│       ├── latam.py               # Another module for the Latam airline(Latam)
│       .
│       .
│       .
└── tests/
    ├── __init__.py
    ├── test_azul.py               # Specific tests for the Azul airline
    ├── test_latam.py              # Specific tests for the Latam airline
    .
    .
    .
```

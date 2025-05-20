# 🧠 GroundedPL: Toolkit for Knowledge Representation

**GroundedPL** is a modular toolkit designed to facilitate knowledge representation and logical inference using grounded predicate logic. It provides auxiliary classes and tools for transforming formulas in First-Order Logic (FOL) into finite domain Propositional Logic, enabling effective reasoning and inference in computational systems.

---

## 📚 Overview

The primary goal of GroundedPL is to bridge the gap between abstract logical representations and practical computational applications. By grounding FOL formulas into propositional logic within finite domains, this toolkit allows for:

- **Modular Knowledge Representation**: Define and manage logical statements in a structured manner.
- **Logical Inference**: Perform reasoning tasks using grounded logic suitable for computational processes.
- **Integration with Other Systems**: Serve as a foundational layer for systems requiring logical inference capabilities.

---

## 🗂️ Repository Structure

```

groundedPL/
├── src/                   # Core source code for grounding logic
│   ├── codificacion.py    # Parses FOL statements and handles grounding of FOL to propositional logic
│   ├── logClases.py       # Classes and utility functions to handle FOL formulas
│   ├── logic_tester.py    # Inference module
│   ├── tseitin.py         # Class to perform Tseitin transformation
│   └── logUtils.py        # Utility functions
├── examples/              # Example scripts demonstrating usage
├── LICENSE                # License information
└── README.md              # Project documentation

````

---

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher

### Installation

Clone the repository:

```bash
git clone https://github.com/EAndrade-Lotero/groundedPL.git
cd groundedPL
````

Install the required packages:

```bash
pip install -r requirements.txt
```

### Usage

Explore the `examples/` directory for more comprehensive examples and demonstrations.

---

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your enhancements. For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for details.

---

## 📬 Contact

For questions or suggestions, feel free to open an issue or contact the repository maintainer.
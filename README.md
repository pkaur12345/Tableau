# Assembly Language CPU Registers Dashboard

An interactive Tableau dashboard that visualizes the architecture and functionality of CPU registers used in Assembly Language programming. The dashboard helps students and beginners understand different register types, their purposes, and their relationships within the CPU.

---

## Dashboard Preview

> Add a screenshot here.

![Dashboard Preview](images/dashboard-preview.png)

---

## Project Overview

Understanding CPU registers is one of the most important topics in Assembly Language. This dashboard provides a visual representation of:

- General Purpose Registers
- Segment Registers
- Index Registers
- Special Purpose Registers
- Register hierarchy (8-bit, 16-bit, 32-bit and 64-bit)
- Purpose of each register

The dashboard is designed as an educational aid for students studying Computer Organization, Microprocessors, and Assembly Language.

---

## Features

- Interactive visualization of CPU register architecture
- Classification of all register types
- Register purpose and functionality
- Easy-to-understand layout
- Educational dashboard for beginners
- Clean and organized visual design

---

## Register Categories Included

### General Purpose Registers

| Register | Purpose |
|----------|---------|
| AX / EAX / RAX | Accumulator Register |
| BX / EBX / RBX | Base Register |
| CX / ECX / RCX | Counter Register |
| DX / EDX / RDX | Data Register |

---

### Segment Registers

- Code Segment (CS)
- Data Segment (DS)
- Stack Segment (SS)
- Extra Segment (ES)

---

### Index Registers

- Source Index (SI)
- Destination Index (DI)

---

### Special Purpose Registers

- Instruction Pointer (IP)
- Stack Pointer (SP)
- Base Pointer (BP)
- Flag Register (FLAGS)

---

## Technologies Used

- Tableau Desktop
- Microsoft Excel / CSV Dataset
- Data Visualization
- Assembly Language Concepts

---

## Files

```
Assembly-Registers-Dashboard/
│
├── dashboard/
│   └── Assembly Registers Dashboard.twbx
│
├── data/
│   └── registers.csv
│
├── images/
│   └── dashboard-preview.png
│
├── README.md
└── LICENSE
```

---

## Learning Outcomes

This dashboard helps users understand:

- CPU register organization
- Difference between AX, EAX, and RAX
- Purpose of General Purpose Registers
- Segment Register functionality
- Stack-related registers
- Index registers
- Register sizes (8-bit, 16-bit, 32-bit, 64-bit)

---

## Dashboard Insights

- Registers are grouped according to their functionality.
- General Purpose Registers perform arithmetic and logical operations.
- Segment Registers store memory segment addresses.
- Index Registers assist in string and array operations.
- Special Purpose Registers control program execution and stack management.

---

## How to Open

1. Clone the repository

```
git clone https://github.com/yourusername/Assembly-Registers-Dashboard.git
```

2. Open the `.twbx` file using Tableau Desktop or Tableau Public.

---

## Future Improvements

- Interactive register comparison
- Search functionality
- CPU execution flow visualization
- Assembly instruction demonstrations
- Register animation using Tableau Story

---

## Author

**Ansh Sahni**

MIT World Peace University (MIT-WPU)

Computer Science Engineering

---

## License

This project is licensed under the MIT License.

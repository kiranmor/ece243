# ECE243 — Computer Organization Projects

Course projects completed as part of **ECE243 at the University of Toronto**, covering processor architecture, digital systems, FPGA deployment, and hardware–software integration.

---

## Projects

### 1. Enhanced Processor (Verilog)
📁 `lab8-enhanced_processor/`

Designed and implemented an enhanced processor architecture with custom instruction execution and control logic.

Highlights:
- FSM-based control unit
- Instruction fetch/decode/execute pipeline
- ALU operations (add, subtract, logical AND)
- Load/store instructions
- Program counter and memory interface
- Conditional branching and flag registers

**Technologies:**  
Verilog • Digital Logic • Processor Architecture • FSM Design

→ See project details inside `lab8-enhanced_processor/`

---

### 2. Neural Network on FPGA
📁 `final_project/`

Designed and implemented a feedforward neural network in C and deployed it on the **DE1-SoC FPGA** to classify urinary tract infection (UTI) cases.

Features:
- Forward propagation with sigmoid activation
- Backpropagation and configurable learning rate
- Hardware-controlled configuration
- Real-time VGA visualization
- Live inference mode

**Technologies:**  
C • FPGA (DE1-SoC) • Embedded Systems • Neural Networks • VGA Interface

→ See project details inside `final_project/`

---

## Repository Structure

```plaintext
ece243-finalproject/
│
├── README.md
├── lab8-enhanced_processor/
│   ├── README.md
│   └── prov.v
│
└── final_project/
    ├── README.md
    ├── nn.c
    └── screenshots/
```

---

## Learning Outcomes

- Processor and digital system design
- Hardware–software integration
- Embedded system development
- FPGA deployment workflows
- Debugging and verification
- Visualization of computational systems

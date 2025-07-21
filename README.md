# RTL-Design-with-Verilog-
🔷**Key Features of Verilog:**

➤Used for digital design and verification

➤Supports multiple modeling styles: gate-level, dataflow, behavioral, and structural

➤Can simulate, synthesize, and implement digital hardware on FPGAs and ASICs

Verilog is IEEE standardized (IEEE 1364) and widely adopted in the semiconductor and VLSI design industry.

🔷**What is RTL Design?**

RTL (Register Transfer Level) is a design abstraction that defines how data flows between registers and the logical operations performed on that data.

At the RTL level:

➤Registers store data using flip-flops or latches.

➤Combinational logic performs operations (e.g., addition, shifting, logical comparison).

➤Designs are written using sequential and combinational logic constructs in HDL (like Verilog).


  **RTL design** is the first and most critical step in digital hardware design and synthesis. It is used for:

➤Functional simulation

➤Synthesis into gate-level netlists for FPGA or ASIC design

➤Timing analysis and hardware implementation

#
💻 **Platform Used**: [EDA Playground](https://www.edaplayground.com/)

🧾 **Focus Area**: Writing and simulating Verilog RTL designs
#

The following Verilog examples were implemented and tested:

| Module Name              | Description                                                     |  Link |
| ------------------------ | --------------------------------------------------------------- | ------------------- |
| Ripple Carry Adder       | Implements a 4-bit ripple carry adder using structural modeling | [Click ](https://www.edaplayground.com/x/KVPc)|      |
 | Whitespace               | Shows how whitespace affects/verifies formatting in Verilog     | [Click](https://www.edaplayground.com/x/ueNP)      |
| Comments                 | Demonstrates single-line and multi-line comments                | [Click](https://www.edaplayground.com/x/Uu7Q)      |
| Unary Operators          | Uses unary operators like `~`, `!`, etc.                        | [Click](https://www.edaplayground.com/x/VyfB)      |
 | Binary Operators         | Demonstrates binary arithmetic and logical operations           |[Click](https://www.edaplayground.com/x/9g3z)     |
 | Real Number              | Shows usage of real number constants                            | [Click](https://www.edaplayground.com/x/Mxyb)     |
 | Identifiers and Keywords | Differentiates identifiers and reserved keywords                | [Click](https://www.edaplayground.com/x/dUt5)      |
 | Escape Identifiers       | Uses escaped identifiers with special characters                | [Click](https://www.edaplayground.com/x/DHza)     |
| Tri                      | Implements tri-state buffer behavior                            | [Click](https://www.edaplayground.com/x/9USa)   |
 | Real                     | Explores the `real` data type                                   |[Click](https://www.edaplayground.com/x/8TJY)      |
 | Integer                  | Uses `integer` data type in assignments and arithmetic          |    [Click](https://www.edaplayground.com/x/sTtm) |
 | Time                     | Demonstrates time data type and delay usage                     |[Click](https://www.edaplayground.com/x/iaqH)      |
 | Real Time                | Combines real and time types for precision delays               | [Click](https://www.edaplayground.com/x/HS9z)    |
 | Scalar                   | Explains scalar value declaration and usage                     | [Click](https://www.edaplayground.com/x/abJN)    |
 | Concatenation            | Concatenates multiple bits or signals                           | [Click](https://www.edaplayground.com/x/biwa)     |
 | Vector                   | Declares and uses vector signals like buses                     |[Click](https://www.edaplayground.com/x/g4Af)       |
 | Slicing                  | Extracts portions of vectors (bit slicing)                      |    [Click](https://www.edaplayground.com/x/L5MP)  |
| Vector Part Selection    | Selects specific parts from a vector                            | [Click](https://www.edaplayground.com/x/gpue)      |
 | 1D Array                 | Demonstrates one-dimensional array usage                        |[Click](https://www.edaplayground.com/x/VXy2)      |
 | 2D Array                 | Demonstrates two-dimensional array declaration and access       |[Click](https://www.edaplayground.com/x/6Uy3)      |
 | 4:1 MUX (Gate Level)     | Implements a 4:1 multiplexer using gate-level modeling          |[Click](https://www.edaplayground.com/x/W_LM)      |
| String Concatenation     | Shows how to join strings in Verilog                            |[Click](https://www.edaplayground.com/x/DfKN)      |
 | String Comparison        | Compares strings using equality operators                       |  [Click](https://www.edaplayground.com/x/JZWQ)    |
 | String Length            | Calculates string length                                        | [Click](https://www.edaplayground.com/x/bJeN)     |
| Fase 5 "2.0"             | \[Clarify what this module does]                                | [Click](https://www.edaplayground.com/x/WeDA)    |
 | `$finish`                | Demonstrates simulation end with `$finish`                      |[Click](https://www.edaplayground.com/x/9MFE)      |
 | `$write`                 | Uses `$write` for formatted console output                      |[Click](https://www.edaplayground.com/x/w7nq)      |
 | `$strobe`                | Uses `$strobe` to display values after delta cycles             | [Click](https://www.edaplayground.com/x/gNWT)     |
| Triple Equal Operator    | Compares values with `===` including unknowns (`x`, `z`)        |   [Click](https://www.edaplayground.com/x/p72z)   |
 | 4:1 MUX (Dataflow)       | Implements a 4:1 multiplexer using dataflow modeling            | [Click](https://www.edaplayground.com/x/JUFa)    |
 | Full Adder (Dataflow)    | 1-bit full adder using dataflow style                           | [Click](https://www.edaplayground.com/x/G49q)   |
 | Multiple Initial Blocks  | Demonstrates multiple `initial` blocks in a module              | [Click](https://www.edaplayground.com/x/uucr)   |
 | Basic Gates              | Implements basic gates: AND, OR, NOT, etc.                      |[Click](https://www.edaplayground.com/x/mYjX)     |
| Buffer and NOT           | Uses buffer and NOT gate examples                               |[Click](https://www.edaplayground.com/x/g2G5)     |
| Format Specifiers        | Shows how to use format specifiers with `$display`/`$write`     |[Click](https://www.edaplayground.com/x/VhJU)      |
 | Parameter Declaration    | Declares and uses parameters in Verilog                         |[Click](https://www.edaplayground.com/x/VejR)       |
 | Module Parameter         | Passes parameters through module instantiation                  |[Click](https://www.edaplayground.com/x/pUSA)      |
 | Parameter Pi             | Defines the mathematical constant π as a parameter              |[Click](https://www.edaplayground.com/x/GAvc)      |

> ⚠️ All codes are simulated and verified on [EDA Playground](https://www.edaplayground.com/).

#
 🤝 Feel free to reach out to me on  [LinkedIn](https://www.linkedin.com/in/sirisha-theetla) for discussions on Verilog, RTL, or VLSI.


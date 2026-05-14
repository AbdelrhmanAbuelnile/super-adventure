Chapter 12: Instruction Sets: Characteristics and Functions

1. Multi-Address Machine Code Comparison
   Raw Equations:
   Expression A: Y=A+B/[C∗(D−E)]
   Expression B: Y=(A−B)/[C+(D∗E)]
   Expression C: X=(A+B∗C)/(D−E∗F)
   Years & Points:
   2025/2026 midterm: Question 3, 17 points
   2025/2024 final: Question 1a, 12 points
   2023/2024 final: Question 2, 10 points
   2023/2024 midterm: Question 3, 16 points
   2021/2022 final: Question 3b, 12 points
   2021/2022 midterm 2: Question Q-3, 20 points
2. Instruction Set Design Issues
   Raw Question: "Briefly explain five important instruction set design issues."
   Years & Points:
   2021/2022 final: Question 3a, 5 points
   2021/2022 midterm: Question Q-5, 20 points
3. User-Visible Register Data Types
   Raw Question: "What are the main types of user-visible registers? What categories of data are commonly supported by user-visible registers?"
   Years & Points:
   2025/2026 midterm: Question 5a, 10 points
   2025/2024 final: Question 1b, 8 points

---

Chapter 13: Instruction Sets: Addressing Modes and Formats

1. Main Addressing Modes for x86
   Raw Question: "What are the main Addressing Modes for x86 processor?"
   Years & Points:
   2025/2026 midterm: Question 1, 16 points
   2025/2024 final (Nov Round): Question Q-2b, 15 points
   2023/2024 midterm 2: Question Q-3, 12 points
   2023/2022 midterm 2: Question Q-3a, 8 points
2. Effective Address (EA) Calculation Table
   Raw Data Block:
   Location 200: [Load to AC | Mode]
   Location 201: 500
   Location 202: [Next instruction]
   State: R1=400, Base Register =100.
   Assumptions: Location 399 =999, location 400 =1000, and so on.
   Years & Points:
   2023/2024 midterm: Question 4, 24 points
   2022/2023 final: Question 4b, 16 points
3. Instruction Format Design Factors
   Raw Question: "What are the basic design factors that affects the length of machine instruction? What are the trade-offs between these factors?"
   OR "What are the factors that can determine the allocation of the addressing bits in fixed length instructions?"
   Years & Points:
   2025/2024 final: Question 2a, 10 points
   2023/2024 midterm 2: Question Q-4, 18 points
   2021/2022 final: Question 2a, 6 points
   2021/2022 midterm: Question Q-2, 24 points
4. Stack Operation Sequence
   Raw Code Sequence: PUSH 4, PUSH 7, PUSH 8, ADD, PUSH 10, SUB, MUL.
   Years & Points:
   2023/2022 midterm 2: Question Q-3b, 8 points

---

Chapter 14: Processor Structure and Function

1. Handling Conditional Branches
   Raw Question: "One of the problems in designing an instruction pipeline is conditional branches, Describe different approaches for dealing with conditional branches?"
   Years & Points:
   2025/2024 final (Nov Round): Question Q-2a, 15 points
   2023/2024 midterm 2: Question Q-2, 15 points
   2021/2022 midterm 2: Question Q-4, 20 points
2. Instruction Cycle & Intel 80486 Pipelining
   Raw Question: "Define stages of an instruction cycle? Draw the instruction cycle state diagram with Interrupt?"
   OR "What are the main stages of Intel 80486 Pipelining?"
   Years & Points:
   2025/2024 final (Nov Round): Question Q-3b, 15 points
   2023/2024 midterm (Inst Cycle): Question 1, 12 points
   2023/2024 midterm (80486): Question 5, 15 points
   2023/2022 midterm 2 (Inst Cycle): Question Q-2, 12 points

---

Chapter 15: Reduced Instruction Set Computers (RISC)

1. Register File vs. Cache Organizations
   Raw Question: "Compare between the use of large register file and cache memory organizations?"
   Years & Points:
   2025/2024 final (Nov Round): Question Q-1b, 15 points
   2025/2024 final: Question 4a, 12 points
   2023/2024 midterm 2: Question Q-5, 18 points

---

Chapter 16: Instruction-Level Parallelism (ILP) and Superscalar

1. Identifying Data Dependencies
   Raw Instruction Sequences:
   Sequence 1:
   Sequence 2:
   Sequence 3:
   Years & Points:
   2025/2024 final (Seq 1 & 2): Question 5b, 10 points
   2022/2023 final (Seq 1 & 2): Question 1b, 12 points
   2021/2022 final (Seq 3): Question 1b, 10 points
2. Superscalar Elements and Parallelism Limitations
   Raw Question: "What are the key elements of superscalar processors organization?"
   OR "Explain the fundamental limitations of instruction level parallelism?"
   Years & Points:
   2025/2024 final (Nov Round): Question Q-4a (Limitations) & Q-4b (Elements), 15 points each
   2023/2024 final: Question 3a (Limitations) & Question 3b (Elements), 10 points each
   2022/2023 final (Elements): Question 1a, 8 points
   2021/2022 midterm 2 (Limitations): Question Q-2, 20 points

---

Chapter 20: Control Unit Operation

1. Instruction Micro-operation Sequences
   Micro-operation Lists:
   List A: ADD R1, X, ISZ X, BSA X
   List B: AND R1, X, ISZ X, BSA X
   List C: Load Accumulator, Store Accumulator, Add to Accumulator, AND to Accumulator
   Cycles: Fetch, Indirect, and Interrupt cycles
   Years & Points:
   2025/2024 final (Nov Round - List A): Question Q-1a, 15 points
   2025/2024 final (Bus AC Add): Question 3b, 12 points
   2023/2024 final (Cycles): Question 1a, 9 points
   2023/2024 final (List B): Question 1b, 11 points
   2023/2024 midterm 2 (List A): Question Q-6, 12 points
   2022/2023 final (Subtraction): Question 3a, 6 points
   2022/2023 final (Bus AC Add): Question 3b, 12 points
   2023/2022 midterm 2 (Cycles): Question Q-5b, 10 points
   2021/2022 midterm 2 (List C): Question Q-5, 20 points

---

Chapter 21: Microprogrammed Control

1. Control Unit Implementation Logic
   Raw Question: "What is the difference between a hardwired implementation and a microprogrammed implementation...?"
   OR "How can a horizontal microinstruction be executed?"
   Years & Points:
   2023/2024 midterm 2: Question Q-7, 12 points
   2023/2022 midterm 2: Question Q-6a, 8 points

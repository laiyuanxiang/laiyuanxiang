
graph TD
    T[Task Node]
    T --> P1[Process Node]
    P1 --> G1[Generator Node]
    P1 --> T1[Tool Node]
    P1 --> P2[Process Node]
    P2 --> A1[Action Node]
    P2 --> T2[Tool Node]

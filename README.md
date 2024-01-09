# mux2->1
A 2-to-1 multiplexer (mux) selects one of two inputs (A or B) based on a control signal (SEL). The output is the selected input: if SEL is true, output is B; otherwise, it's A. Used for data routing in digital systems.

| SEL | A | B | Output |
|-----|---|---|--------|
|  0  | X | X |   A    |
|  1  | X | X |   B    |

In this truth table, the Output column represents the selected output based on the control signal (SEL). If SEL is 0, the output is A; if SEL is 1, the output is B.

# VHDL Integer Overflow in Counter

This repository demonstrates a potential integer overflow bug in a simple VHDL counter. The counter increments on each rising clock edge.  However, it lacks proper handling of the case when the counter reaches its maximum value (15 in this example).  This leads to undefined behavior when the count attempts to exceed the maximum value.  The solution shows how to correctly manage the counter to prevent overflow.
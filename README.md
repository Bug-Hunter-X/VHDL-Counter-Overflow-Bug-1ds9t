# VHDL Counter with Overflow Bug

This repository demonstrates a common VHDL coding error: an integer counter that lacks overflow protection.  The original `counter.vhdl` code increments without bounds, potentially causing unpredictable behavior when the counter reaches its maximum value.

The solution, provided in `counter_fixed.vhdl`, addresses the overflow issue by adding a check to prevent the counter from exceeding its defined range.
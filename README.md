# Area Efficient FIR Filter

## Problem

Existing FIR filters use Carry Select Adders (CSLA), which introduce higher delay and hardware complexity.

## Existing Solution

The existing architecture uses a CSLA-based FIR filter.

## Proposed Solution

The CSLA is replaced with a Kogge-Stone Adder (KSA), which reduces critical path delay through parallel prefix computation.

## Tools Used

- Verilog HDL
- Icarus Verilog
- GTKWave
- Ubuntu Linux

## Result

The waveform below compares the existing and proposed architectures.

- y_before → Existing FIR Filter
- y_after → Proposed FIR Filter

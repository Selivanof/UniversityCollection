# Low Level HW Digital Systems II 2023-2024

This repository contains the assignments that I completed for the Low Level HW Digital Systems II 2023-2024 Course, as part of my undergraduate studies at Aristotle University of Thessaloniki.

|   Course Information     |                                  |
|--------------------------|----------------------------------|
| Semester                 | 8                                |
| Attendance Year          | 2023-2024                        |
| Project Type             | Optional                         |
| Team Project             | No                               |
| Language Used            | SystemVerilog                    |
| Software Used            | Intel Quartus/Questa/ModelSim    |

## Description

A simple floating point multiplier, based on the IEEE 754 standard. The following simplifications were made (as per the project's instructions):
- All NaN's are treated as infinites (a NaN flag still exists).
- All Denormals are treated as zeroes.

The multiplication.sv file was given to us as a way to confirm correct operation of our module. 

Verification was also performed using SVAs.

## Notes

Some files that were provided by the professor are **not** included in this repository (fp_mult_top.sv, multiplication.sv).

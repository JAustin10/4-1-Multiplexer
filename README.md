# 4-1-Multiplexer-In-Tanner
There are multiple ways to design a 4:1 Multiplexer.This specific design was constructed using NAND and NOt gates instead of the traditional method which consists of AND and OR gates.

The 4:1 Multiplexer consists of 4 input lines A,B,C,D and two selection lines S0,S1 and 1 output line.
The Boolean Function for the 4:1 Multiplexer can be written as:
Out=S1'S0'A+S1'S0B+S1S0'C+S1S0D

The Logic gates were designed individually and were tested before implementing it in the final design.The symbols were then constructed and this allowed for multiple use of a single design.
Given below is the schematic of the 4:1 Multiplexer.
SCHEMATIC
--
![4](https://github.com/JAustin10/4-1-Multiplexer/assets/133579820/d4969aeb-fbc5-44d6-9110-f8245119c003)

One Input NOT Gate
--
![1](https://github.com/JAustin10/4-1-Multiplexer/assets/133579820/eb027117-d17b-43cb-bfca-0cd4f4fca3af)

Three Input NAND Gate
--
![2](https://github.com/JAustin10/4-1-Multiplexer/assets/133579820/3b5723fd-3519-4e4e-90c9-cfc432b3a2e7)

Four Input NAND Gate
--
![3](https://github.com/JAustin10/4-1-Multiplexer/assets/133579820/2d0bc436-d1e1-42b1-81a6-fbe8a86cb9ba)

Given below are the output for the 4:1 Multiplexer circuit.

CASE 1:When S0=0 and S1=0
--
![5](https://github.com/JAustin10/4-1-Multiplexer/assets/133579820/9338fb70-80be-4115-b872-71e08422e0a8)

CASE 2:When S0=0 and S1=1
--
![6](https://github.com/JAustin10/4-1-Multiplexer/assets/133579820/f57b0bc6-3cbc-4e63-b753-62139dedc967)

CASE 3:When S0=1 and S1=0
--
![7](https://github.com/JAustin10/4-1-Multiplexer/assets/133579820/75e5f762-3aef-4604-9d45-952af83a307a)

CASE 4:When S0=1 and S1=1
--
![8](https://github.com/JAustin10/4-1-Multiplexer/assets/133579820/cc9c4bc1-3a19-4608-b014-5808774875dd)



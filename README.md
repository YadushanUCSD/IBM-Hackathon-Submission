# IBM-Hackathon-Submission
Nikki Sanglimsuwan, Samantha Reap, Yadushan Thilianathan, Zhiyang Ying

Language: Qiskit
Platforms Used: Jupyter, VS Code, Pycharm

Incorporated Quantum computing using the logic gates and understanding quantum's probable and efficient thinking.

Track 1: Feynman's dream - Reversible computing
-------------
Our program reads four decimal numbers, encodes them into bits, and builds a reversible sorting network. The list is sorted and then unsorted to demonstrate reversibility. Finally, the circuit converts qubits to classical bits, compiles, simulates, and outputs the sorted list.


Track 2: Quantum Optimization for Impact
----------------------
The program starts by parsing through a csv containing information on large deposits of plastics in the ocean over a period of time. It then takes all unique locations that had plastic reported and creates an adjacency matrix with the corresponding longitudes and latitudes. After arranging the different locations in a model, it performs the QAOA to find the most efficient route and the least amount of time. Finally, the solution is optimized and compared with another algorithm that brute forces the shortest path to see how accurately the QAOA performed. The QAOA method consistently finds the path faster and is only ever marginally slower than the perfect path. This has very big implications as finding these paths in less time is extremely energy efficient thanks to the use of quantum algorithms.

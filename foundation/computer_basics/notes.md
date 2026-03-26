Module 1 – Computer Basics

1. Computer Components

A computer mainly consists of:
	•	CPU (Central Processing Unit) – executes instructions and performs calculations.
	•	Memory (RAM) – temporarily stores data that the program is currently using.
	•	Storage (Disk/SSD) – stores data permanently.

When a program runs, the CPU processes instructions while the memory holds the data needed for those instructions.

⸻

2. Values, Variables, and Types

A value is the actual data (example: 5, "hello").

A variable is a named location that stores a value in memory.

Example in Python:

x = 5
name = "Akash"

Here:
	•	x stores an integer value.
	•	name stores a string value.

The type defines what kind of data the value is (integer, string, boolean, etc.).

3. Memory Size of Types

Different types of data occupy different amounts of memory.

Examples:
	•	Integer → fixed number of bytes
	•	Float → more memory than integers
	•	Boolean → very small memory
	•	String → depends on number of characters

Understanding memory size helps when designing efficient algorithms and data structures.

⸻

4. Stack vs Heap Memory

Programs mainly use two types of memory areas:

Stack

Used for:
	•	function calls
	•	local variables

Characteristics:
	•	very fast
	•	automatically managed
	•	limited in size

Heap

Used for:
	•	dynamically allocated memory
	•	objects and complex data structures

Characteristics:
	•	larger memory
	•	slower than stack
	•	manually managed by program or language runtime

⸻

5. References vs Values

Some variables store values directly, while others store references to memory locations.

Example concept:

Value:

a = 5
b = a

Both a and b store the value 5.

Reference:
When working with objects or data structures, variables may store a reference to where the data is located in memory.

This allows multiple variables to point to the same object.

⸻

6. Why Data Structures Matter

Data structures help organize data efficiently so programs can:
	•	store information
	•	retrieve information quickly
	•	modify data efficiently

Choosing the correct data structure can reduce algorithm complexity from O(n²) to O(n) or even O(log n).

Examples:
	•	Arrays → fast indexed access
	•	Hash tables → fast lookup
	•	Stacks → last-in first-out operations
	•	Queues → first-in first-out operations

Efficient data structures are essential for writing scalable and performant software.

⸻

Key Takeaways
	•	Programs store data in memory using variables.
	•	The stack manages function calls and local variables.
	•	The heap stores dynamically allocated objects.
	•	References allow multiple variables to access the same data.
	•	Understanding memory and data structures helps write efficient algorithms.

    26/03/2026
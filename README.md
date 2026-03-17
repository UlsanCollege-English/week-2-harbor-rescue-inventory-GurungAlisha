Week 2 README Template
Summary

This assignment is about managing a Harbor Rescue Inventory using Python lists.
We created functions to access, search, and modify list data safely.
Each function performs a specific task like finding items, slicing lists, or counting occurrences.
The goal is to understand list operations, loops, and indexing in Python.

Approach

mission_snapshot:
Returns the first and last items using indexing (items[0] and items[-1]).
If the list is empty, it returns (None, None).

cargo_window:
Uses list slicing to return a portion of the list from start to start + size.
Returns an empty list if the start is invalid or size is not positive.

first_supply_index:
Loops through the list using range() and checks each item.
Returns the index when the target is found, otherwise -1.

supply_report:
Iterates through the list to count how many times the target appears.
Also tracks the first index where the target is found.

priority_load (stretch):
Creates a new list by adding the urgent item at the front using list concatenation.
Does not change the original list.

Complexity reasoning
Function	Time complexity	Why
mission_snapshot	O(1)	Direct access to first and last elements
cargo_window	O(k)	Slicing copies up to size elements
first_supply_index	O(n)	May check all elements in worst case
supply_report	O(n)	Iterates through entire list to count
priority_load (stretch)	O(n)	Creates a new list with all elements
Edge-case checklist

 empty list

 one-item list

 target missing

 repeated values

 slice goes past end

 size is zero

 size is negative

 original list unchanged in priority_load

Assistance / Sources

Person / tool / website: ChatGPT

Help received: Helped explain logic, provided code examples, and guided how to structure the README.
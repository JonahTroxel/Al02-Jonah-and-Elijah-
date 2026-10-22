# AL02: Library Catalog Lookup and Big-O Recognition

Name: [Elijah Ferrer]
Partners: [Jonah Troxel]
Shared repository: []
My contribution: []

## Run

Keep main.py, test_assignment.py, catalog_data.py, growth_examples.py,
and any other imported modules together.

```powershell
py -3.14 main.py
py -3.14 test_assignment.py
```

## Work Notes and Reflections
Tuesdays
I helped with creating this index look up program that scans through the database and displays them as available books inside the terminal. the first one in the growth_example.py is an O(1) type as it goes through and runs it, the second bit is an O(n) as it collect ID through the database to make a list one, the third bit O(n^2) as it runs through the database twice to create a pair for each of it, and lastly the fourth bit O(log n) as for each step it takes, it's starting slowly decreases until it reaches to one.

As the functions scan through the database in order, the program stops as soon it has it's target id and goes through the other one in an order. the best case is the user inputs B1 as it scans it as O(1) which is faster than having scan it as O(n) in B4 

Thursday
1. it would be much faster for the program to use O(1) than O(n + 1) for it doesn't need to do extra steps to extract the information and just simply look up it's tag instead of the entire index
2. it would be much easier to look at it's label rather than looking at all of it's content to streamline the process much smoother
3. what the program does it fetches the catalog to look for a tag that is related to the target id and adds them to a list to display out to the user. it is better to reuse the index rather than rebuilding the index itself again, for it already has a pre-made list to modify with. 
4. 

## Assistance

[Support used, or none. For AI, identify the tool/task and what you checked,
changed, or rejected. Identify supplied files as supplied.]

## Instructor Comments

[Reserved for instructor feedback.]
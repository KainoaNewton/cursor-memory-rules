# Cursor Memory
Easily manage AI context for your projects using the Memory Bank technique. 

## Setup
This workflow can be set up in two ways: you can install it in a project or in all of Cursor.

### In a project
1. Press ``shift+cmd+P``
2. Search for ``New Cursor Rules`` and press enter
3. Type ``memory-rules`` and press enter
4. Delete all the text thats already there and paste in [memory-bank-rules](https://github.com/KainoaNewton/cursor-memory-rules/blob/main/memory-rules-per-project.md)

### In all of Cursor
1. Press ``shift+cmd+P``
2. Search for ``Cursor Settings`` and press enter
3. Navigate to the "Rules" tab on the left
5. In the input box under "User Rules" paste in [memory-bank-rules](https://github.com/KainoaNewton/cursor-memory-rules/blob/main/memory-rules-global.md)

## Usage
At the start of a project tell cursor to:

```
Initialize the memory bank
```

To implement a new feature:

```
/plan
Help me make...
```
And then you will probably answer some questions for cursor and follow up a few times to edit the plan. Then when you're happy with its plan, type:
```
/act
implement it
```

## Contributions
If you have a suggestion for this project, feel free to open a pull request, and I’ll do my best to review it within a few days.

## Credits
The original rule files were created here by [ipenywis](https://github.com/ipenywis/aimemory).

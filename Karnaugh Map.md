A Karnaugh map makes it easier to create an efficient design for a [[Logic Gate]].

# Creating a Karnaugh Map
Take a truth table ([[And Gate]] in this case):

| X | Y | Out |
| - | - | --- |
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

And "flip" it:

| X / Y | 0 | 1 |
| ----- | - | - |
| 0     | 0 | 0 |
| 1     | 0 | 1 |

# Usage
Select 1s in the largest power-of-two blocks. This way it is easier to make out what a [[Logic Gate]] is supposed to do and therefore simpler and more compact gates.
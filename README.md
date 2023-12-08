# Storage

## Data Volumes

- https://www.eecis.udel.edu/~amer/Table-Kilo-Mega-Giga---YottaBytes.html

Unit              | Value	             | Example
------------------|----------------------|--------------------------------------------------------------------
Kilobytes (KB)	  | 1,000 bytes	         | a paragraph of a text document
Megabytes (MB)	  | 1,000 Kilobytes	     | a small novel
Gigabytes (GB)	  | 1,000 Megabytes      | Beethoven’s 5th Symphony
Terabytes (TB)	  | 1,000 Gigabytes	     | all the X-rays in a large hospital
Petabytes (PB)	  | 1,000 Terabytes	     | half the contents of all US academic research libraries
Exabytes (EB)	  | 1,000 Petabytes	     | about one fifth of the words people have ever spoken
Zettabytes (ZB)	  | 1,000 Exabytes	     | as much information as there are grains of sand on all the world’s beaches
Yottabytes (YB)	  | 1,000 Zettabytes     | as much information as there are atoms in 7,000 human bodies

## Examples

### Storing all permutations of [0, 1, ..., 9]

- There are `10! = 3'628'800` permutations
- Storing one permutation per line, as a string of digits, in a `.txt` file uses `38MB`
- `38'000'000 / 3'628'800 ~= 10`: each permutation uses 10 bytes
- Each character uses 1 byte

```
0123456789
0123456798
...
```

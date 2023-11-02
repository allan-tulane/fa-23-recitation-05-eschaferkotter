# CMPS 2200 Recitation 6
## Answers

**Name:**Ethan Schaferkotter


Place all written answers from `recitation-06.md` here for easier grading.



- **d.**

| File | Fixed-Length    | Huffman   | Ratio |
| :---:   | :---: | :---: | :---: |
| f1.txt | 1340   | 826  | 0.616 |
|alice.txt | 1039367   | 676374   | 0.651
| asyoulik.txt | 876253   | 606448   | 0.692
| grammar.lsp | 26047   | 17356   | 0.666
| fields.c |  	78050   | 56206   | 0.720

Fixed-length coding is usually greater than huffman coding, and usually only 2/3 as efficient.

- **e.**

If all characters had the same frequency, then they would all be at leaf level. The expected cost would be frequency * the encoding lengths, so, with a balanced tree, n*logn which is equal to nlogn.

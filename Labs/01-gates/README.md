# Dostal jsem první bod!



## De Morgans Laws simulation

### EDA Playground
https://www.edaplayground.com/x/h2Cc

### Code
```vhdl

architecture dataflow of gates is
begin
    f_o  <= ((not b_i) and a_i) or ((not c_i) and (not b_i));
    fnand_o <= a_i;
    fnor_o <= a_i and b_i;

end architecture dataflow;

```

### Screenshot:

![ScreenShot](https://github.com/markolukicluk99/VUT-Digital-Electronics-1/blob/main/Labs/01-gates/images/Capture.PNG)



### Table:
| c | b | a | f(c,b,a) |
|---|---|---|----------|
| 0	| 0 | 0 |	0      |
| 0 | 0 | 1	|   0      |
| 0 | 1 | 0	|   1      |
| 0	| 1 | 1	|   1      |
| 1 | 0 | 0 |   1      |
| 1 | 0 | 1	|   1      |
| 1	| 1 | 0	|   0      |
| 1	| 1 | 1 |   0      |

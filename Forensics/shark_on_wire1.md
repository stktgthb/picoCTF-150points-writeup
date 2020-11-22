# Shark_on_wire1

## Description

We found this packet capture. Recover the flag.

## Solution

​Check Statistics - > hierarchy and we found that we need to investigate this UDP packet since there are bunch of 
​​UDP packet. Then, ​Check Follow->UDP stream. We searched with "picoCTF" on the stream 0 page, but the flag was 
​​not found. We continued to search with picoCTF in order Stream1, Stream2, Stream3, and We got an answer with 
​​Stream6.​
​​
## Flag

picoCTF{StaT31355_636f6e6e}
